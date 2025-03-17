# NotificationAction

## MoveAction

|Name|Type|Description|
|---|---|---|
|State|Int16|Movement State|
|A|Int16||
|Points|Byte[]|Movement point (Currentspot -> Movespot)|


## StopState

|Name|Type|Description|
|---|---|---|
|State|Int32||


## SkillPoseAction

|Name|Type|Description|
|---|---|---|
|Angle|Int16||
|Pose|Int16||


## LookAction

|Name|Type|Description|
|---|---|---|
|SyncType|Byte||
|TypeID|Int16||
|HairID|Int16||
|A|Int16||
|B|Int16||
|C|Int16||
|D|Int16||
|E|Int16||


## SkillSrc

|Name|Type|Description|
|---|---|---|
|FightId|Byte||
|Angle|Int16||
|State|Int16||
|StopState|Int16||
|SkillId|UInt32|Used skill|
|Speed|Int64||
|Skill|[SkillState](./SkillState.md)||
|ExecTime|Int16||
|Effects|[Effect[]](./Effect[].md)||
|StateNumber|Int16||


## SkillTar

|Name|Type|Description|
|---|---|---|
|FightId|Byte||
|State|Int16||
|DoubleAttack|Boolean||
|Miss|Boolean||
|BeatBack|Boolean||
|SrcID|UInt32||
|X|UInt32||
|Y|UInt32||
|SkillID|Int32||
|TarX|Int32||
|TarY|Int32||
|ExecTime|UInt16||
|Skip|Byte||
|Effects|[Effect[]](./Effect[].md)||


## ItemFailed

|Name|Type|Description|
|---|---|---|
|ItemID|Int16||


## PKControll

|Name|Type|Description|
|---|---|---|
|A|Byte||


## ClientMove

|Name|Type|Description|
|---|---|---|
|Points|Byte[]||


## SkillAction

|Name|Type|Description|
|---|---|---|
|Move|Byte||
|FightID|Byte||
|Points|Byte[]||
|SkillID|UInt32||
|TargetID|UInt32||
|TargetHandle|UInt32||


## ItemPickUp

|Name|Type|Description|
|---|---|---|
|WorldID|UInt32||
|Handle|UInt32||


## SkillPose

|Name|Type|Description|
|---|---|---|
|Angle|Int16||
|Pose|Int16||


## ItemUse

|Name|Type|Description|
|---|---|---|
|GridID|Int16||
|Left|Int16||


## ItemPosition

|Name|Type|Description|
|---|---|---|
|SourceGridId|Int16||
|SourceNumber|Int16||
|TargetGridId|Int16||


