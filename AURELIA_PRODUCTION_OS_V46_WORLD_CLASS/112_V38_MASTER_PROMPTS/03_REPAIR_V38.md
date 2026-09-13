# V38 REPAIR

先诊断，不先重写。

`SYMPTOM -> FAILURE CLASS -> LINEAGE -> EARLIEST RESPONSIBLE LAYER -> MINIMUM REPAIR -> IMPACT -> RECOMPILE -> REGRESSION -> VALIDATE`。

如果根因属于 Canon/State，Prompt 层禁止修复。
如果根因属于语义，Model Retry 禁止修复。
如果根因属于模型能力，才允许进入 Adapter/Retry/Task Split。
