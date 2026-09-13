# V35 Schemas

Required envelope for every core object:
id, project_id, canon_version, state_revision, authority_ref, provenance, semantic_hash, temporal_scope, dependencies, confidence, lifecycle, validation_status.

Core: SemanticObjectV35 / WorldStateV35 / CausalChainV35 / CharacterStateV35 / RelationshipStateV35 / AudienceModelV35 / FutureCandidateV35 / DramaticDynamicsV35 / CinematicDecisionV35 / ProductionAtomV35 / ProductionPackageV35 / EvidenceBundleV35 / RecoveryPlanV35.

Closed enums. Unknown critical enum = BLOCKED until explicit schema migration.
