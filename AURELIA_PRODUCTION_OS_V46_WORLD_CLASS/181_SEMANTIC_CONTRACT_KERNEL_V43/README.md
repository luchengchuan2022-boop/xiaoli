# V43 — Semantic Contract Kernel

目标：把 V42 的语义原则进一步变成**可执行、可验证、可回放的契约体系**。

## 核心公理
1. 每个可变创作对象必须有唯一语义身份、生命周期、权威来源、版本、有效时间与依赖闭包。
2. 任何状态变化必须由授权 Transition 产生；“模型写了”不是 Transition。
3. Transition 必须同时提供：Preconditions、Protected Semantics、Delta、Postconditions、Invariants、Evidence、Authorization。
4. 无法证明的关键语义不得静默落地。
5. Prompt 不是业务逻辑；Prompt 只能消费已经确定的语义合同。

## Contract 生命周期
DRAFT → VALIDATED → AUTHORIZED → EXECUTABLE → OBSERVED → PROVEN → COMMITTABLE → COMMITTED
失败：REJECTED / QUARANTINED / SUPERSEDED。

## 不允许
- 用自然语言隐藏硬约束。
- 用模型结果反向提升 Authority。
- 用视觉漂亮度覆盖语义缺陷。
- 省略 Provenance、Evidence 或版本信息。
