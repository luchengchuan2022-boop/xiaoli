# Recommended Java Integration Order

Phase 1：schemas + enums + IDs + hash model
Phase 2：EventStore + TransactionCoordinator
Phase 3：StateProjector + GraphStore
Phase 4：QueryEngine + ContextCompiler
Phase 5：Decision/ChangeControl
Phase 6：CinematicCompiler + PromptCompiler
Phase 7：ModelAdapter + Observation/Evidence
Phase 8：Regression + Replay + Health
Phase 9：Production Package + materialization/recovery

任何阶段都必须先通过 V43 acceptance contracts，再进入下一层。
