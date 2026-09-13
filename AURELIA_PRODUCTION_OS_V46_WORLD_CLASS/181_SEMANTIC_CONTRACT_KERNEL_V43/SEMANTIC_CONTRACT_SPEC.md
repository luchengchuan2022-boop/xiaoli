# Semantic Contract Specification V43

每个 Contract 必须回答：WHO / WHAT / WHY / FROM / TO / UNDER_WHICH_RULE / PROOF / AUTHORITY / REVERSIBILITY。

### Transition Contract
- transition_id
- aggregate_id
- base_version
- authority
- preconditions[]
- protected_semantics[]
- legal_creative_space[]
- delta[]
- postconditions[]
- invariants[]
- evidence_requirements[]
- reversibility
- blast_radius
- idempotency_key
- provenance

### Proof Obligation
每个 protected semantic 与 postcondition 必须映射到 evidence 或可验证规则。
若 proof_status ≠ PROVEN，则关键变更不得 COMMIT。
