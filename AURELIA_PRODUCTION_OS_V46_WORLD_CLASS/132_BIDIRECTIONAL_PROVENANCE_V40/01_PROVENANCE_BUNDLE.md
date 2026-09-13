# Provenance Bundle

Minimum fields:
source_ids, dependency_ids, decision_ids, compiler_version, semantic_hash, input_state_hash, output_manifest_hash, model_observation_refs, validation_refs, reviewer_refs.

Provenance must distinguish PRESERVED, TRANSFORMED, OMITTED_BY_POLICY, NEWLY_INTRODUCED, and UNKNOWN.
UNKNOWN provenance is a gate failure for any claim presented as established truth.
