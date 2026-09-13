# Transaction Model

Lifecycle: `DRAFT -> CANDIDATE -> REVIEWED -> APPROVED -> COMMITTABLE -> COMMITTED`.
Terminal historical states: `SUPERSEDED`, `COMPENSATED`, `REJECTED`, `QUARANTINED`.

A transaction contains read-set, write-set, dependency-set, authority, semantic delta, proofs, idempotency key, conflict set, commit decision and event hash.

Rollback never erases committed history; it creates a compensating event with explicit lineage.
