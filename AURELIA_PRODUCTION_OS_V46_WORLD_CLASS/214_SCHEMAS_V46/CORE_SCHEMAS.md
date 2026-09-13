# V46 Core Schemas
CreativeObjectV46: object_id, object_type, schema_version, authority_class, scope, valid_time, record_time, lifecycle_state, semantic_hash, provenance, dependencies, confidence.
CreativeExecutionV46: execution_id, task_contract, frozen_context_hash, authority_snapshot, objective, constraints, candidate_policy, compiler_version, seed_policy, evidence_policy, status.
TransitionV46: transition_id, aggregate_id, from_version, to_version, preconditions, protected_semantics, semantic_delta, postconditions, invariants, evidence_ids, proof_ids, authorization, idempotency_key.
EventV46: event_id, aggregate_id, prior_version, result_version, event_type, semantic_delta, valid_time, record_time, causality_ids, authority, evidence_ids, parent_hash, hash, idempotency_key.
ContextPacketV46: task_contract, required_claims, dependency_closure, authority_filter, temporal_filter, knowledge_perspective, continuity_locks, dramatic_requirements, compression_log, context_hash.
ProductionAtomV46: atom_id, exact_duration_15s, start_state_ref, dramatic_purpose, beat, emotional_trajectory, audience_state, character_state_refs, relationship_delta_refs, storyboard, shots, performance_ir, cinematic_ast, keyframe_ast, image_prompt_ast, video_prompt_ast, audio_ast, asset_refs, continuity_locks, end_state_ref, validation, proof_bundle, manifest_hash.
ProofBundleV46: obligation_id, obligation_type, status, source_refs, evidence_refs, reasoning_trace, validator_version, proof_hash.
