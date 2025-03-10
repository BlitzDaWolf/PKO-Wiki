|Start|Name|Type|DataType|Description|Example|
|---|---|---|:---:|:---:|---|
|0|Exist|Int32|`Record`|Should be used in the game|1|
|4|index|Int32|`Record`|Main search index|136|
|8|DataName|string(72)|`CRawDataInfo`|Data name|`Deathsoul Acceleration`|
|80|LastUseTick|Int32|`CRawDataInfo`||0|
|84|Enabled|Int32|`CRawDataInfo`|Is the data enabled|1|
|88|Data|Int32|`CRawDataInfo`||0|
|92|PackOffset|Int32|`CRawDataInfo`||0|
|96|DataSize|Int32|`CRawDataInfo`||0|
|100|ID|Int32|`CRawDataInfo`|Data ID|136|
|104|LoadCnt|Int32|`CRawDataInfo`||0|
|108|CharacterID|Byte|`SkillEff`||136|
|109|Name|string(17)|`SkillEff`||`Deathsoul Accele`|
|126|Frequency|Int16|`SkillEff`||-1|
|128|OnTransfer|string(32)|`SkillEff`||`0`|
|160|AddState|string(32)|`SkillEff`||`State_wljs_Add`|
|192|SubState|string(32)|`SkillEff`||`State_wljs_Rem`|
|224|AddType|Byte|`SkillEff`||1|
|225|CanCancle|Boolean|`SkillEff`||False|
|226|CanMove|Boolean|`SkillEff`||True|
|227|CanMSkill|Boolean|`SkillEff`||True|
|228|CanGSkill|Boolean|`SkillEff`||True|
|229|CanTrade|Boolean|`SkillEff`||False|
|230|CanItem|Boolean|`SkillEff`||True|
|231|CanUnbeatable|Boolean|`SkillEff`||True|
|232|CanItemmed|Boolean|`SkillEff`||True|
|233|CanSkilled|Boolean|`SkillEff`||True|
|234|NoHide|Boolean|`SkillEff`||True|
|235|NoShow|Boolean|`SkillEff`||True|
|236|OptItem|Boolean|`SkillEff`||True|
|237|TalkToNPC|Boolean|`SkillEff`||True|
|238|FreeState|Byte|`SkillEff`||0|
|239|Skip1|byte[] (25)|`SkillEff`|`Data that is not yet known`|`0000000000FFFF000000009A03FFFF00000000000000000000`|
