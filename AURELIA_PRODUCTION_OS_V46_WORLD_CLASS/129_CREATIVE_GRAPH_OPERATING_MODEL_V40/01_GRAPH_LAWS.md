# Graph Laws and Invariants

### Identity
Two nodes with the same semantic identity must not silently diverge. Different representations may exist, but they must resolve to one authoritative identity or be explicitly marked as candidates/observations.

### Causality
CAUSES means a justified causal dependency. PRECEDES means order only. CORRELATES_WITH never implies cause. DERIVED_FROM preserves source lineage.

### Time
Every state-bearing object has effective_from/effective_to or an explicit timeless scope. Future projections must never be written into past truth.

### Mutation
Allowed mutation verbs: CREATE_CANDIDATE, PROPOSE, APPROVE, COMMIT, SUPERSEDE, DEPRECATE, RETCON, MIGRATE. Direct overwrite of committed truth is forbidden.

### Proof closure
A committed object must have dependency closure sufficient to reconstruct why it exists. Missing authority or evidence is a validation failure, not a reason to guess.
