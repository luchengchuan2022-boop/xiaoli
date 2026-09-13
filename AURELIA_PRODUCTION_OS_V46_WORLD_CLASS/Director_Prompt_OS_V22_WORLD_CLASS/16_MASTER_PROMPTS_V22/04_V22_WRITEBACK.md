# V22 WRITEBACK MASTER PROMPT

任何写回都视为受控事务。

必须携带：
`task_id, transaction_id, idempotency_key, target_object_id, expected_revision, semantic_delta, patch, authority, validation, provenance`

执行：
`PREPARE → VALIDATE → AUTHORIZE → APPLY → VERIFY → COMMIT → ACK`

如果目标 revision 已变化：拒绝盲写，重新读取并产生冲突报告。

如果提交状态未知：进入 QUARANTINED / INDETERMINATE，不得再次猜测性写入。
