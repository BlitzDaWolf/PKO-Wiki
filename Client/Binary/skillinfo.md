|Start|Name|Type|DataType|Description|Example|
|---|---|---|:---:|:---:|---|
|0|Exist|Int32|`Record`|Should be used in the game|1|
|4|index|Int32|`Record`|Main search index|295|
|8|DataName|string(72)|`CRawDataInfo`|Data name|`Encumbered Skeleton`|
|80|LastUseTick|Int32|`CRawDataInfo`||0|
|84|Enabled|Int32|`CRawDataInfo`|Is the data enabled|1|
|88|Data|Int32|`CRawDataInfo`||0|
|92|PackOffset|Int32|`CRawDataInfo`||0|
|96|DataSize|Int32|`CRawDataInfo`||0|
|100|ID|Int32|`CRawDataInfo`|Data ID|295|
|104|LoadCnt|Int32|`CRawDataInfo`||0|
|108|ShortID|Int16|`SkillInfo`||295|
|110|Name|string(17)|`SkillInfo`||`Encumbered Skele`|
|127|FightID|Byte|`SkillInfo`||1|
|128|Skip1|byte[] (166)|`SkillInfo`|`Data that is not yet known`|`FF0AFEFEFEFEFEFEFEFEFEFEFEFEFEFEFEFE0100FFFFFEFFFEFFFEFFFEFFFEFFFEFFFEFFFEFFFEFFFEFFFEFFFEFFFEFFFEFF0100FFFFFEFFFEFFFEFFFEFFFEFFFEFFFEFFFEFFFEFFFEFFFEFFFEFFFEFFFEFF0100FFFFFEFFFEFFFEFFFEFFFEFFFEFFFEFFFEFFFEFFFEFFFEFFFEFFFEFFFEFFFFFFFFFF0000FEFF000000000000000000000000000000000000000000000000000000000000000000000000000000000001FFFF`|
|294|previous|Int16|`SkillInfo`||-1|
|296|previousLevel|Int16|`SkillInfo`||-1|
|298|Skip2|byte[] (23)|`SkillInfo`|`Data that is not yet known`|`FEFFFEFFFEFFFEFF010202002003040100000000000000`|
|321|Prepare|string(33)|`SkillInfo`||`0`|
|354|UseSP|string(33)|`SkillInfo`||`0`|
|387|UseEndure|string(33)|`SkillInfo`||`0`|
|420|UseEnergy|string(33)|`SkillInfo`||`0`|
|453|SetRange|string(33)|`SkillInfo`||`0`|
|486|RangeState|string(33)|`SkillInfo`||`0`|
|519|Use|string(33)|`SkillInfo`||`0`|
|552|Effect|string(33)|`SkillInfo`||`Skill_klcs_End`|
|585|Active|string(33)|`SkillInfo`||`0`|
|618|Inactive|string(33)|`SkillInfo`||`0`|
|651|StateID|Int32|`SkillInfo`||0|
|655|SelfAttribute|Int16[] (2)|`SkillInfo`||`0`, `0`|
|655|SelfEffect|Int16[] (2)|`SkillInfo`||`0`, `0`|
|655|ItemExend|Int16[] (4)|`SkillInfo`||`0`, `0`, `0`, `0`|
|655|BeingTime|Int16|`SkillInfo`||0|
|657|TargetAttr|Int16[] (2)|`SkillInfo`||`0`, `0`|
|657|SplashParam|Int16|`SkillInfo`||0|
|659|TargetEffect|Int16|`SkillInfo`||0|
|661|SplashEffect|Int16|`SkillInfo`||0|
|663|Variation|Int16|`SkillInfo`||0|
|665|Summon|Int16|`SkillInfo`||0|
|667|PreTime|Int16|`SkillInfo`||0|
|669|FireSpeed|string(33)|`SkillInfo`||`SkillCooldown_klcs`|
|702|Operate|string(3)|`SkillInfo`||``|
|705|ActionHarm|Int16|`SkillInfo`||256|
|707|ActionPlayType|Byte|`SkillInfo`||0|
|708|ActionPose|Int16[] (10)|`SkillInfo`||`1`, `11`, `0`, `0`, `0`, `0`, `0`, `0`, `0`, `0`|
|708|ActionFrame|Int16|`SkillInfo`||0|
|710|Whop|Int16|`SkillInfo`||0|
|712|ActionDummyLink|Int16[] (2)|`SkillInfo`||`104`, `-1`|
|712|ActionEffect|Int16[] (2)|`SkillInfo`||`0`, `0`|
|712|ActionEffectType|Int16[] (2)|`SkillInfo`||`0`, `0`|
|712|ItemDummyLink|Int16|`SkillInfo`||0|
|714|ItemEffect1|Int16[] (2)|`SkillInfo`||`0`, `0`|
|714|ItemEffect2|Int16[] (2)|`SkillInfo`||`0`, `0`|
|714|SkyEffectActionKeyFrame|Int16|`SkillInfo`||0|
|716|SkyEffectActionDummyLink|Int16|`SkillInfo`||0|
|718|SkyEffectItemDummyLink|Int16|`SkillInfo`||0|
|720|SkyEffect|Int16|`SkillInfo`||0|
|722|SkySpd|Int16|`SkillInfo`||0|
|724|Whoped|Int16|`SkillInfo`||5|
|726|TargetDummyLink|Int16|`SkillInfo`||-1|
|728|TargetEffectID|Int16|`SkillInfo`||0|
|730|TargetEffectTime|Byte|`SkillInfo`||0|
|731|AgroundEffectID|Int16|`SkillInfo`||26880|
|733|WaterEffectID|Int16|`SkillInfo`||-256|
|735|Skip3|byte[] (9)|`SkillInfo`|`Data that is not yet known`|`FF8E03000000000000`|
|744|Icon|string(17)|`SkillInfo`||`s0225.tga`|
|761|playTime|Byte|`SkillInfo`||0|
|762|DescribeHint|string(128)|`SkillInfo`||`Monster Skill`|
|890|EffectHint|string(128)|`SkillInfo`||`Monster Skill`|
|1018|ExpandHint|string(128)|`SkillInfo`||`0`|
|1146|Skip4|byte[] (10)|`SkillInfo`|`Data that is not yet known`|`00000101000000000000`|
