# JAVA FUTURE CONTRACT BOUNDARY

当前不实现 Java。

未来 Java Runtime 只需要消费稳定契约：
TaskContract
CanonRecord
StateRecord
KnowledgeRecord
ProductionPlan
ProductionIR
PromptAST
AssetRef
Evidence
ValidationResult
Event
Snapshot
WritebackTransaction
ReleaseManifest

Java 不应依赖自然语言 Prompt 的内部段落位置。
Prompt 是 Renderer，不是数据库 Schema。
