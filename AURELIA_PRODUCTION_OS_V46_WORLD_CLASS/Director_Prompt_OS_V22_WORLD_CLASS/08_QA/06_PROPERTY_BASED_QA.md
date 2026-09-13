# PROPERTY-BASED QA

不要只测试固定案例。

随机生成合法状态并验证：
- transition legality
- idempotency
- dependency closure
- rollback safety
- patch locality
- authority monotonicity
- semantic preservation

QA 应测试“系统不会做什么”，而不只是“系统能做什么”。
