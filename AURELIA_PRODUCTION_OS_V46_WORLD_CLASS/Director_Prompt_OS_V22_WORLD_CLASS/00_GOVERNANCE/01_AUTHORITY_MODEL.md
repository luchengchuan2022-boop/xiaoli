# AUTHORITY MODEL

权威层级：
L0 Governance / System Invariants
L1 Authoritative Canon
L2 Committed Production State
L3 Approved Authorial Intent
L4 Approved Story / Editorial Decisions
L5 Production Constraints
L6 Director Intent
L7 Asset / Reference Constraints
L8 Model Capability
L9 Prompt Rendering Preference

低层不能覆盖高层。

状态类型：
LOCKED / AUTHORITATIVE / APPROVED / PROPOSED / OBSERVED / EXTERNAL / UNKNOWN / CONFLICTED

关键规则：
- PROPOSED 只能进入 Review。
- OBSERVED/EXTERNAL 只能作为证据，不能自动升级为 Canon。
- UNKNOWN 不是空值。
- CONFLICTED 必须进入冲突工作流。
