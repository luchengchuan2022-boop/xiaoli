# V43 → Java Integration Boundary

当前阶段：只定义 contract；不实现 Java。

## Java 应实现的职责
GraphStore / EventStore / StateProjector / QueryEngine / ContextCompiler / DecisionRegistry / ChangeControl / NarrativeHealth / CinematicCompiler / PromptCompiler / ModelAdapter / ObservationStore / EvidenceStore / RegressionEngine / ReplayEngine / TransactionCoordinator。

## Java 不得实现
- 通过 if/else 隐藏创作 Canon。
- 解析自然语言 prompt 决定业务真相。
- 直接把模型输出写进 Canon。
- 建立第二真相数据库。

## API 边界原则
输入输出全部 typed；必须携带 version / authority / provenance / hashes / status / errors。

## Error taxonomy
INVALID_CONTRACT / AUTHORITY_CONFLICT / PRECONDITION_FAILED / INVARIANT_FAILED / PROOF_GAP / CONTINUITY_BREACH / CAPABILITY_MISMATCH / IDEMPOTENCY_CONFLICT / PROJECTION_GAP / REPLAY_DIVERGENCE / MATERIALIZATION_PENDING / TRANSACTION_ABORTED。
