|Start|Name|Type|DataType|Description|Example|
|---|---|---|:---:|:---:|---|
|0|Exist|Int32|`Record`|Should be used in the game|1|
|4|index|Int32|`Record`|Main search index|40|
|8|DataName|string(72)|`CRawDataInfo`|Data name|`Training Gem of Soul`|
|80|LastUseTick|Int32|`CRawDataInfo`||0|
|84|Enabled|Int32|`CRawDataInfo`|Is the data enabled|1|
|88|Data|Int32|`CRawDataInfo`||0|
|92|PackOffset|Int32|`CRawDataInfo`||0|
|96|DataSize|Int32|`CRawDataInfo`||0|
|100|ID|Int32|`CRawDataInfo`|Data ID|40|
|104|LoadCnt|Int32|`CRawDataInfo`||0|
|108|ItemID|Int32|`StoneInfo`||10524|
|112|EquipPos|Int32[] (3)|`StoneInfo`||`1`, `2`, `3`|
|112|Type|Int32|`StoneInfo`||4|
|116|Skip1|byte[] (3)|`StoneInfo`|`Data that is not yet known`|`FF5072`|
|119|HinFunc|string(64)|`StoneInfo`||`ItemHint_TrainingSoul`|
