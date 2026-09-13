# Core V40 Schema

```text
SemanticObject {
  object_id: ID,
  object_type: ENUM,
  authority: ENUM,
  provenance: REF[],
  temporal_scope: TIME_SCOPE,
  lifecycle: ENUM,
  version: VERSION,
  dependencies: REF[],
  semantic_hash: HASH,
  confidence: ENUM,
  status: ENUM
}

CreativeDecision {
  decision_id: ID,
  question: TEXT,
  state_version: VERSION,
  protected_semantics: REF[],
  candidates: REF[],
  selected_candidate: REF,
  impact: IMPACT_SET,
  reversibility: ENUM,
  authority: REF,
  rationale: TEXT,
  evidence: REF[]
}

ProductionAtom15s {
  atom_id: ID,
  start_state: REF,
  purpose: TEXT,
  beats: REF[],
  duration_seconds: 15.00,
  end_state: REF,
  shot_plan: REF[],
  keyframes: REF[],
  image_prompts: REF[],
  video_prompt: REF,
  continuity: REF[],
  evidence: REF[],
  manifest: REF
}
```
