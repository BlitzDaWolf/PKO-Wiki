|Start|Name|Type|DataType|Description|Example|
|---|---|---|:---:|:---:|---|
|0|Exist|Int32|`Record`|Should be used in the game|1|
|4|index|Int32|`Record`|Main search index|50|
|8|DataName|string(72)|`CRawDataInfo`|Data name|`Hairdo 7`|
|80|LastUseTick|Int32|`CRawDataInfo`||0|
|84|Enabled|Int32|`CRawDataInfo`|Is the data enabled|1|
|88|Data|Int32|`CRawDataInfo`||0|
|92|PackOffset|Int32|`CRawDataInfo`||0|
|96|DataSize|Int32|`CRawDataInfo`||0|
|100|ID|Int32|`CRawDataInfo`|Data ID|50|
|104|LoadCnt|Int32|`CRawDataInfo`||0|
|108|Color|string(40)|`Hair`||`Cyan`|
|148|NeedItem|HairNeedItem[] (4)|`Hair`||`(Itm=1807, Amt=1)`, `(Itm=1808, Amt=1)`, `(Itm=1801, Amt=5)`, `(Itm=1806, Amt=1)`|
|148|Money|Int32|`Hair`||100000|
|152|ItemID|Int32|`Hair`||2051|
|156|FailItemID|Int32[] (3)|`Hair`||`1999`, `0`, `0`|
|156|ChaUse|Int16[] (4)|`Hair`||`1`, `0`, `1`, `0`|
