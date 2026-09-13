# EXACTLY-ONCE SEMANTICS

目标：
外部副作用在逻辑上表现为 exactly-once。

实现原则：
idempotency key
transaction boundary
event uniqueness
commit marker
post-commit verification

如果无法证明 exactly-once：
降级为 at-least-once + deduplication，
不得假装成功。
