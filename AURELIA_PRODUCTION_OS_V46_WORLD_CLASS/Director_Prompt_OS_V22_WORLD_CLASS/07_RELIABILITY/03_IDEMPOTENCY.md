# IDEMPOTENCY

重复执行同一 task：
- 不得重复增加 EP。
- 不得重复追加相同 event。
- 不得重复写入相同 Canon Delta。
- 不得制造第二份“已完成”事实。

使用：
task_id + input_fingerprint + compiler_version + semantic_hash

重复请求应返回已有结果或安全的 no-op。
