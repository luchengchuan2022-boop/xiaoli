# V45 Java Handoff Boundary

Java integration is intentionally deferred. This document defines contracts only.

Suggested service boundaries:
AuthorityService, ObjectRegistry, EventStore, StateProjector, GraphStore, QueryEngine, ContextCompiler, DecisionRegistry, TransitionEngine, ChangeControl, NarrativeHealth, CinematicCompiler, PromptCompiler, ModelAdapter, ObservationStore, EvidenceStore, ProofEngine, ManifestBuilder, RegressionEngine, ReplayEngine, TransactionCoordinator.

Java MUST NOT:
- become Canon authority
- infer creative truth from prose heuristically
- mutate committed state without an event
- accept model output as truth
- duplicate Canon in multiple stores
- encode hidden creative policy in UI code
- bypass proof gates

Every service boundary is typed, versioned, auditable and idempotent.
