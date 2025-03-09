|Start|Name|Type|DataType|Description|Example|
|---|---|---|:---:|:---:|---|
|0|Exist|Int32|`CRawDataInfo`|Should be used in the game|1|
|4|index|Int32|`CRawDataInfo`|Main search index|255|
|8|DataName|string(72)|`CRawDataInfo`|Data name|`Login Interface`|
|80|LastUseTick|Int32|`CRawDataInfo`||0|
|84|Enabled|Int32|`CRawDataInfo`|Is the data enabled|1|
|88|Data|Int32|`CRawDataInfo`||0|
|92|PackOffset|Int32|`CRawDataInfo`||0|
|96|DataSize|Int32|`CRawDataInfo`||0|
|100|ID|Int32|`CRawDataInfo`|Data ID|255|
|104|LoadCnt|Int32|`CRawDataInfo`||0|
|108|Color|UInt32|`AreaInfo`||680314|
|112|Music|Int32|`AreaInfo`|[Music](./musicinfo.md) ID|-1|
|116|EnvColor|UInt32|`AreaInfo`||4285699227|
|120|LightColor|UInt32|`AreaInfo`||4294967295|
|124|LightDir|Single[] (3)|`AreaInfo`||`-1`, `-1`, `-1`|
|124|Skip1|byte[] (4)|`AreaInfo`|`Data that is not yet known`|`00000000`|
