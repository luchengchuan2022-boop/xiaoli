# V39 Core Schema

`QueryV39 { id, class, subject_ids, as_of, scope, criticality, required_authority }`

`CandidateV39 { id, source_context_hash, semantic_delta, rationale, forecast, risks, option_value, reversibility }`

`CanonChangeV39 { id, target, change_type, before_hash, after_hash, authority, impact_graph, regression_plan, status }`

`CrossScaleProofV39 { claim_id, scale, supporting_nodes, supporting_edges, authority, temporal_scope, confidence, status }`

`StudioReviewV39 { review_id, role, verdict, critical_flags, evidence, conflicts, required_repairs }`

`ProductionAtomV39 { atom_id, duration_ms, start_state, end_state, semantic_delta, shots, keyframes, image_prompts, video_prompt, continuity, qa, evidence, manifest }`
