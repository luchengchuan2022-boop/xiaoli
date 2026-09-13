# V43 — Proof-Carrying Production Manifest

每个 15s 生产包都必须携带“为什么可以生成”的证明闭包。

## Manifest 必含
source_refs / canon_version / state_version / context_hash / decision_id / semantic_delta / shot_count / exact_duration=15.00 / prompt_ast_hash / continuity_locks / asset_versions / model_capability / evidence_refs / validation_results / proof_hash。

生产包是可审计对象，不是提示词文本集合。
