# V41 JAVA HANDOFF — CONTRACT ONLY

Java integration is intentionally deferred. This directory defines stable semantic boundaries, not implementation.

Recommended services/interfaces:
`AuthorityService, GraphService, EventStore, StateReducer, QueryService, ContextCompiler, DecisionService, SimulationService, CharacterService, RelationshipService, AudienceService, NarrativePlanner, CinematicCompiler, PromptCompiler, ModelAdapter, EvidenceService, ValidationService, RegressionService, ProductionPackageService`.

## Boundary rule
Java may execute contracts, persistence, transactions, scheduling, hashing, graph queries and adapters. Java must not become the source of creative truth or a hidden parser of master-prompt prose.

## Future integration principle
Implement from schemas and acceptance tests first; do not infer behavior from filenames.
