|Start|Name|Type|Description|Example|
|---|---|---|:---:|---|
|0|Exist|Int32|`Should be used in the game`|1|
|4|index|Int32|`Main search index`|45|
|8|DataName|string(72)|`Data name`|`Blackout`|
|80|LastUseTick|Int32||0|
|84|Enabled|Int32||1|
|88|Data|Int32||0|
|92|PackOffset|Int32||0|
|96|DataSize|Int32||0|
|100|ID|Int32||45|
|104|LoadCnt|Int32||0|
|108|CharacterID|Byte||45|
|109|Name|string(17)||`Blackout`|
|126|Frequency|Int16||-1|
|128|OnTransfer|string(32)||`0`|
|160|AddState|string(32)||`State_Xy_Add`|
|192|SubState|string(32)||`State_Xy_Rem`|
|224|AddType|Byte||2|
|225|CanCancle|Boolean||False|
|226|CanMove|Boolean||False|
|227|CanMSkill|Boolean||False|
|228|CanGSkill|Boolean||False|
|229|CanTrade|Boolean||False|
|230|CanItem|Boolean||False|
|231|CanUnbeatable|Boolean||True|
|232|CanItemmed|Boolean||True|
|233|CanSkilled|Boolean||True|
|234|NoHide|Boolean||True|
|235|NoShow|Boolean||True|
|236|OptItem|Boolean||True|
|237|TalkToNPC|Boolean||False|
|238|FreeState|Byte||0|
|239|Skip1|byte[] (25)||`0000000000FFFF00000001FD00010000000000000000000000`|
