# Projection Contract

输入：ordered committed events。
输出：versioned projection。

必须可回答：来自哪些事件、缺哪些事件、是否存在 gap、是否重放得到相同语义结果。

Gap / hash mismatch / invariant failure → READ_ONLY_DEGRADED 或 REBUILD_REQUIRED。
