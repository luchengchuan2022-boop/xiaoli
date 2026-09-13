# V30 JAVA HANDOFF BOUNDARY

当前阶段只定义语义/生产合同，不实现 Java。

Java 后续必须消费稳定契约，而不是解析自然语言 Master Prompt。

建议边界：
AuthorityService
StateStore
PromiseLedgerService
CreativeGraphService
DirectorDecisionService
PromptCompiler
ModelAdapter
ObservationIngestor
ValidationEngine
ProductionPackageStore
EvidenceStore
TransactionCoordinator

Java 不拥有创作真相；Java 负责执行、持久化、事务、调度、证据与可靠性。
