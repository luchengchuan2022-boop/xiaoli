# V45 Object Lifecycle

All mutable creative meaning follows one lifecycle:
DRAFT -> CANDIDATE -> REVIEWED -> APPROVED -> COMMITTABLE -> COMMITTED.

Terminal/branch states:
QUARANTINED, SUPERSEDED, COMPENSATED, REJECTED, EXPIRED.

## Rules
1. Only authorized transitions may occur.
2. A transition declares preconditions, semantic delta, postconditions, invariants, evidence, actor, authority, and idempotency key.
3. COMMITTED objects are immutable in place. Change creates a new version/event.
4. Rollback is historical compensation, never deletion.
5. Rejected candidates remain evidence of search and are never silently promoted later.
6. Expired projections do not alter canonical truth.
