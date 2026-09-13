# V43 — Runtime Observability / Replay / Explainability

每次创作决策都必须可以回答：系统看到了什么、忽略了什么、为什么这么选、哪个规则阻止了什么、最终语义来自哪里。

## Trace
REQUEST → CONTEXT → QUERY → CANDIDATES → REVIEW → DECISION → COMPILATION → OBSERVATION → EVIDENCE → VALIDATION → TRANSACTION。

## Replay
给定冻结输入与规则版本，必须能够重放语义流程并定位第一次分歧。
