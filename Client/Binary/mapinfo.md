|Start|Name|Type|DataType|Description|Example|
|---|---|---|:---:|:---:|---|
|0|Exist|Int32|`Record`|Should be used in the game|1|
|4|index|Int32|`Record`|Main search index|4|
|8|DataName|string(72)|`CRawDataInfo`|Data name|`lonetower`|
|80|LastUseTick|Int32|`CRawDataInfo`||0|
|84|Enabled|Int32|`CRawDataInfo`|Is the data enabled|1|
|88|Data|Int32|`CRawDataInfo`||0|
|92|PackOffset|Int32|`CRawDataInfo`||0|
|96|DataSize|Int32|`CRawDataInfo`||0|
|100|ID|Int32|`CRawDataInfo`|Data ID|4|
|104|LoadCnt|Int32|`CRawDataInfo`||0|
|108|Name|string(16)|`MapInfo`||`Lone Towerp3`|
|124|initX|Int32|`MapInfo`||50|
|128|initY|Int32|`MapInfo`||50|
|132|LightDir|Single[] (3)|`MapInfo`||`1`, `1`, `-1`|
|132|LightColor|byte[] (3)|`MapInfo`||`FFFFFF`|
|135|ShowSwitch|Boolean|`MapInfo`||False|
