# V45 Core Schemas

## CreativeObjectV45
object_id, object_type, schema_version, authority_class, provenance, valid_time, record_time, lifecycle_state, semantic_hash, dependencies, confidence, scope

## TransitionV45
transition_id, aggregate_id, from_version, to_version, preconditions, semantic_delta, postconditions, invariants, authority, evidence_ids, idempotency_key, causality_ids, proof_ids

## CreativeEventV45
event_id, aggregate_id, prior_version, result_version, event_type, semantic_delta, authority, evidence_ids, valid_time, record_time, parent_hash, hash

## ContextPacketV45
task_contract, required_claims, dependency_closure, authority_filter, temporal_filter, knowledge_perspective, continuity_locks, compression_log, context_hash

## ProductionAtomV45
atom_id, exact_duration_15s, start_state_ref, dramatic_purpose, beat, emotional_trajectory, audience_intent, storyboard, shots, performance, cinematic_ast, keyframes, image_prompts, video_prompts, audio, assets, continuity, end_state_ref, proof_bundle, manifest_hash
