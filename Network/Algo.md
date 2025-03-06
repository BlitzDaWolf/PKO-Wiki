# Algo



## C# code example

```C#
public class Encryption
{
public string Chap { get; set; } = "";

byte[] rcvKey = new byte[4];
byte[] sndKey = new byte[4];

public Encryption()
{
}

public void SetKeys(string chap)
{
	Chap = chap;
	var initialNoise = GetNoise(chap);

	init_Noise(initialNoise, rcvKey);
	init_Noise(initialNoise, sndKey);
}

int GetNoise(string chapStr)
{
	short version = 171;
	short g_sKeyData = (short)((version * version) * 0x1232222);

	var r = chapStr.EndsWith("\0") ? chapStr.Substring(chapStr.Length - 5, 4) : chapStr.Substring(chapStr.Length - 4, 4);
	var keyBytes = Encoding.UTF8.GetBytes(r);

	var data = BitConverter.ToInt32(keyBytes, 0);

	return g_sKeyData * data;
}

void init_Noise(int nNoise, byte[] szKey)
{
	var bytes = BitConverter.GetBytes(nNoise);
	var test = BitConverter.ToUInt32(bytes, 0);

	var k1 = (byte)((test)
		^ 0xe3);
	var k2 = (byte)((test >> 8)
		^ 0xbc);
	var k3 = (byte)((test >> 0x10)
		^ 0x33);
	var k4 = (byte)((test >> 0x18)
		^ 0x12);


	szKey[0] = k1; // 83
	szKey[1] = k2; // 57
	szKey[2] = k3; // ED
	szKey[3] = k4; // 9A
}
static byte[] UpdateKey(byte[] currentKeyBytes, byte[] currentByteValue)
{
	byte[] result = new byte[4];

	for (int i = 0; i < 4; i++)
	{
		// if (i == 1)
		{
			var k = (sbyte)currentKeyBytes[i];
			int rotation = (int)(k & 0x80000007);
			if (rotation < 0)
			{
				rotation = (int)(((rotation - 1) | 0xfffffff8) + 1);
			}
			var useRotaion = (byte)rotation;
			result[i] = useRotaion;

			var l = currentByteValue[i] ^ k;

			var ta = (byte)((sbyte)(l) >> ((byte)rotation & 0x1f));
			var tb = (l) << (8 - (byte)rotation & 0x1f);
			var tc = tb | ta;

			currentKeyBytes[i] = (byte)tc;
		}
	}

	return result;
}

public void Encrypt(Packet pk, bool UpdateKy = true)
{
	byte[] tmpKey = sndKey.ToArray();
	if (UpdateKy)
	{
		UpdateKey(tmpKey, pk.data.Skip(8).ToArray());
	}
	pk.Decrypt(sndKey);
	sndKey = tmpKey;
}

public void Decrypt(Packet pk, bool UdpateKey = true)
{
	pk.Decrypt(rcvKey);
	if (UdpateKey)
	{
		UpdateKey(rcvKey, pk.data.Skip(8).ToArray());
	}
}
}
```