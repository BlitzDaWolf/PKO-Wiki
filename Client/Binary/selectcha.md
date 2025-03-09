|Start|Name|Type|DataType|Description|Example|
|---|---|---|:---:|:---:|---|
|0|Exist|Int32|`CRawDataInfo`|Should be used in the game|1|
|4|index|Int32|`CRawDataInfo`|Main search index|4|
|8|DataName|string(72)|`CRawDataInfo`|Data name|`Ami`|
|80|LastUseTick|Int32|`CRawDataInfo`||0|
|84|Enabled|Int32|`CRawDataInfo`|Is the data enabled|1|
|88|Data|Int32|`CRawDataInfo`||0|
|92|PackOffset|Int32|`CRawDataInfo`||0|
|96|DataSize|Int32|`CRawDataInfo`||0|
|100|ID|Int32|`CRawDataInfo`|Data ID|4|
|104|LoadCnt|Int32|`CRawDataInfo`||0|
|108|Type|Int32|`ChaCreate`||-842150451|
|112|Bone|Int32|`ChaCreate`||3|
|116|Hair|Int32[] (64)|`ChaCreate`||`193`, `194`, `201`, `219`, `221`|
|116|Face|Int32[] (64)|`ChaCreate`||`255`|
|116|Body|Int32[] (64)|`ChaCreate`||`289`|
|116|Hand|Int32[] (64)|`ChaCreate`||`465`|
|116|Foot|Int32[] (64)|`ChaCreate`||`641`|
|116|HairNumber|Int32|`ChaCreate`||5|
|120|FaceNumber|Int32|`ChaCreate`||1|
|124|BodyNumber|Int32|`ChaCreate`||1|
|128|HandNumber|Int32|`ChaCreate`||1|
|132|FootNumber|Int32|`ChaCreate`||1|
|136|Description|string(1024)|`ChaCreate`||``|
