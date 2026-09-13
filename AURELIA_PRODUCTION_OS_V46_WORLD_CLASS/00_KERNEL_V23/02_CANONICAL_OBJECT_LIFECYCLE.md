# V23 Canonical Object Lifecycle

`DISCOVERED → NORMALIZED → TYPED → PROVENANCE_BOUND → AUTHORITY_RESOLVED → ACTIVE → REVISED/FORKED → VALIDATED → COMMITTED → RELEASED → SUPERSEDED/RETIRED`

Rules:
- Identity is stable; revision is mutable history.
- Forks cannot become production truth without an explicit merge/commit.
- Superseded objects remain auditable.
- Deletion is a policy-governed lifecycle transition, not silent disappearance.
