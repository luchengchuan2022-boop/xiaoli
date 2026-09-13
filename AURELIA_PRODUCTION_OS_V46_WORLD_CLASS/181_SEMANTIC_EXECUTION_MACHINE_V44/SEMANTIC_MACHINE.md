# Semantic Execution Machine

## 1. Purpose
The OS is treated as a typed state-transition machine, not a prompt collection.

## 2. Kernel objects
`CreativeObject`, `CreativeState`, `CreativeEvent`, `CreativeDecision`, `TransitionContract`, `ContextPacket`, `ProductionIR`, `PromptAST`, `Observation`, `EvidenceBundle`, `ProductionPackage`, `Transaction`, `Projection`.

## 3. Transition contract
`T = (subject, preconditions, authority, protected_semantics, delta, postconditions, invariants, evidence_requirements, provenance, reversibility, blast_radius)`

A transition is admissible only if every precondition and invariant is proven.

## 4. State law
`S_(n+1) = Project(S_n, committed_event)`; candidate/model observations cannot mutate committed state.

## 5. Closed-loop execution
The machine must preserve semantic identity from source meaning through cinematic compilation and back through evidence.

## 6. Fail-closed
Unknown authority, unresolved causal conflict, protected-semantic drift, missing dependency, invalid duration, or insufficient proof blocks commit.
