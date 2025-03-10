|Start|Name|Type|DataType|Description|Example|
|---|---|---|:---:|:---:|---|
|0|Exist|Int32|`Record`|Should be used in the game|1|
|4|index|Int32|`Record`|Main search index|1093|
|8|DataName|string(72)|`CRawDataInfo`|Data name|`Icy Dragon`|
|80|LastUseTick|Int32|`CRawDataInfo`||0|
|84|Enabled|Int32|`CRawDataInfo`|Is the data enabled|1|
|88|Data|Int32|`CRawDataInfo`||0|
|92|PackOffset|Int32|`CRawDataInfo`||0|
|96|DataSize|Int32|`CRawDataInfo`||0|
|100|ID|Int32|`CRawDataInfo`|Data ID|1093|
|104|LoadCnt|Int32|`CRawDataInfo`||0|
|108|ID|Int32|`Character`||1093|
|112|level|Int32|`Character`|Entity level|104|
|116|Name|string(40)|`Character`|The Entity name|`Icy Dragon`|
|156|ClassName|string(40)|`Character`|Class type name|`Icy Dragon`|
|196|Skip2|byte[] (236)|`Character`|`Data that is not yet known`|`040538000000010001000000000000000000000000000000D101000000000000010000000000000001004A006400340135013601000000000000FFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFF643B1141A470A540713DF640C2010105000205008F018B0100000000000000000000000000000000010100000000000000000000E301000046000000120100001E000000FFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFF`|
|432|DropItems|DropItem[] (20)|`Character`|Normal item drops|`(ItemID=6246, A1=142)`, `(ItemID=4746, A1=400)`, `(ItemID=1644, A1=2000)`, `(ItemID=6148, A1=333333)`, `(ItemID=6128, A1=333333)`, `(ItemID=-1, A1=-1)`, `(ItemID=-1, A1=-1)`, `(ItemID=-1, A1=-1)`, `(ItemID=-1, A1=-1)`, `(ItemID=-1, A1=-1)`, `(ItemID=-1, A1=-1)`, `(ItemID=-1, A1=-1)`, `(ItemID=-1, A1=-1)`, `(ItemID=-1, A1=-1)`, `(ItemID=-1, A1=-1)`, `(ItemID=-1, A1=-1)`, `(ItemID=-1, A1=-1)`, `(ItemID=-1, A1=-1)`, `(ItemID=-1, A1=-1)`, `(ItemID=-1, A1=-1)`|
|432|DropQuest|DropItem[] (20)|`Character`|Item drop when quest is active|`(ItemID=0, A1=0)`, `(ItemID=-1, A1=-1)`, `(ItemID=-1, A1=-1)`, `(ItemID=-1, A1=-1)`, `(ItemID=-1, A1=-1)`, `(ItemID=-1, A1=-1)`, `(ItemID=-1, A1=-1)`, `(ItemID=-1, A1=-1)`, `(ItemID=-1, A1=-1)`, `(ItemID=-1, A1=-1)`, `(ItemID=-1, A1=-1)`, `(ItemID=-1, A1=-1)`, `(ItemID=-1, A1=-1)`, `(ItemID=-1, A1=-1)`, `(ItemID=-1, A1=-1)`, `(ItemID=-1, A1=-1)`, `(ItemID=-1, A1=-1)`, `(ItemID=-1, A1=-1)`, `(ItemID=-1, A1=-1)`, `(ItemID=-1, A1=-1)`|
|432|Skip3|byte[] (40)|`Character`|`Data that is not yet known`|`0000000000000000000000000A00000001000000E803000000000000000000000100000000000000`|
|472|HP|Int32|`Character`||21000|
|476|SkipA1|Int32|`Character`|`Data that is not yet known`|0|
|480|SP|Int32|`Character`||10000|
|484|SkipA2|Int32|`Character`|`Data that is not yet known`|0|
|488|MinAttack|Int32|`Character`||1200|
|492|Recs|Int32|`Character`||1340|
|496|Resostance|Int32|`Character`||20|
|500|Defence|Int32|`Character`||190|
|504|HitRate|Int32|`Character`||220|
|508|Doge|Int32|`Character`||190|
|512|Critical|Int32|`Character`||10|
|516|SkipA3|Int32|`Character`|`Data that is not yet known`|90|
|520|HPRecovery|Int32|`Character`||40|
|524|SPRecovery|Int32|`Character`||1000|
|528|AttackSpeed|Int32|`Character`||1400|
|532|PrivateSpace|Int32|`Character`||700|
|536|ChaseSpace|Int32|`Character`||2000|
|540|MovementSpeed|Int32|`Character`||250|
|544|SkipA4|Int32|`Character`|`Data that is not yet known`|0|
|548|STR|Int32|`Character`||150|
|552|AGI|Int32|`Character`||150|
|556|ACC|Int32|`Character`||150|
|560|CON|Int32|`Character`||150|
|564|SPR|Int32|`Character`||150|
|568|Skip4|byte[] (92)|`Character`|`Data that is not yet known`|`2300000014000000300000000000000000000000000000000000000000000000000000000000000000300000000000000000000000000000000000000000000000000000000000000000300000000000000000000000000000000000`|
|660|EXP|Int64|`Character`|`base EXP drop on death`|32000|
|668|Skip5|byte[] (148)|`Character`|`Data that is not yet known`|`0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000803F0000803F0000803F00000000`|
