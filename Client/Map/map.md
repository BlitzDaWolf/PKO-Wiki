# `.map` Reading

## Header

|Name|Data type|Example|
|---|---|---|
|Version|int|780,627|
|Width|int|4,096|
|Height|int|4,096|
|XTiles|int|8|
|YTiles|int|8|
|XSections|`Width / XTiles`|512|
|YSections|`Height / YTiles`|512|
|Sections|`XSections * YSections`|262,144|


## Offset

Using tile offset.
```
SectionOffset = (X / XTiles) * YSections + (y / YTiles);
Section.TileOffset = (Y % YTiles) * XTiles + (X % XTiles)
```

The offsets are right after the [Header](#Header).
The size of wich is from the Sections.


If a offset = 0 that means there is no data for that section and should be skipped

Otherwise you can jump to that file offset.

## Section

The offset is calculated as followed `y * xSections + x`

Each section has `XTiles * YTiles` of 15 bytes long.
Each tile has the following data compresed structure.

|Name| Type|
|---|---|
|TileInfo|int|
|bTileIfo|byte|
|Color|short|
|Height|byte|
|Region|short|
|IsLand|Byte|
|Block|byte[`(NW), (NE), (SW), (SE)`]|

The Decompresion is as folwed

|Name|Decom|
|---|---|
|TileTexture|`TileInfo_5TO8(TileInfo)`|
|Color|`RGB_565_TO_DWORD(Color) \| 0xff000000`|
|Region|Region|
|Block|Block|
|Height|`(float)(Height*10) / 100.0f`|
|IsLand|IsLand|
|TColor||
|XColor||
