# V43 — Creative Transaction Algebra

将创作变化建模为受控事务，而非“写一段文本”。

## 状态机
DRAFT → CANDIDATE → REVIEWED → APPROVED → COMMITTABLE → COMMITTED
旁路：REJECTED / QUARANTINED / SUPERSEDED。

## ACID 语义
- Atomic：一次语义变更要么全部提交，要么全部不提交。
- Consistent：提交后所有不变量成立。
- Isolated：候选之间不得互相污染。
- Durable：提交事件具有不可变身份和证据。

## Rollback
Rollback 不删除历史；它产生新的补偿事件。

## Idempotency
相同 idempotency_key + 相同 base_version + 相同 semantic payload 必须得到相同提交结果；冲突 payload 必须进入 CONFLICT。
