# V43 — Deterministic Creative Control Plane

同一输入版本、同一规则版本、同一任务合同下，Context / Query / Decision Record / Prompt AST / Package Manifest 的**语义结构**必须可复现。

不要求外部模型像素级或文案级完全相同；要求控制平面结果可解释、可追踪、可比较。

## Deterministic Inputs
Authority snapshot + State version + Graph version + Rule version + Task contract + Capability profile + Seed/selection policy。

## Deterministic Outputs
context_hash / decision_hash / ast_hash / package_semantic_hash / proof_hash。

随机创意搜索必须显式隔离 random_seed，并记录搜索空间与选择规则。
