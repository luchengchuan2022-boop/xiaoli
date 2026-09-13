# DIFF / PATCH

支持：
CanonDiff
StateDiff
StoryDiff
ShotDiff
PromptDiff
AssetDiff
PackageDiff

Repair 优先生成 Patch，而不是整包重写。

Patch 必须声明：
base_version
target_version
changed_objects
semantic_delta
validation_scope
rollback_point
