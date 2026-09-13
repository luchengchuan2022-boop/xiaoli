# Transaction Rules

Commit 前必须通过：Authority / Preconditions / Delta / Postconditions / Invariants / Evidence / Continuity / Cross-scale / Production Completeness。

任何一个关键 Gate FAIL：不得 Commit。

COMMITTED ≠ MATERIALIZED。生产文件落盘失败属于 POST_COMMIT_MATERIALIZATION_PENDING，不回滚已提交语义事实。
