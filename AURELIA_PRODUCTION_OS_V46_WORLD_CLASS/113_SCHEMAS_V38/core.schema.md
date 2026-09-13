# Core Schema V38

Required common fields:
`id, type, authority, provenance, source_refs, temporal_scope, dependencies, confidence, lifecycle, semantic_hash`.

Core objects:
`CreativeGraphNode, StoryState, FutureCandidate, Decision, CharacterTransition, RelationshipTransition, RevealContract, ProductionAtom15s, ProductionPackage, EvidenceBundle, RepairPlan, HealthReport`.

Semantic hash must be derived from normalized semantic fields, not free-form prompt whitespace.
