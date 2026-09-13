# V43 — State Projection & Consistency

Event Store 是历史事实源；State Projection、Creative Graph、Digital Twin、Health View 都是派生视图。

## 一致性规则
Event sequence → State Projection → Graph Projection → Derived Views。
任何 Projection 都必须记录 source_event_version / projection_version / projection_hash。

## Rebuild
允许从事件重建 Projection；重建结果必须通过 semantic checksum 与 invariant suite。

## 禁止双写真相
任何派生视图不得成为 Canon Authority。
