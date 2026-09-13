# V45 State/Event Algebra

## Canonical model
STATE(t+1) = APPLY(STATE(t), AUTHORIZED_EVENT, VALID_RULES)

An event is immutable historical fact with:
identity, aggregate, prior_version, result_version, semantic_delta, authority, evidence, causality, valid_time, record_time, idempotency_key, hash, parent_hash.

## Transition contract
PRECONDITIONS -> EVENT -> DELTA -> POSTCONDITIONS -> INVARIANTS -> PROOF

No event may be committed when an invariant is violated or critical uncertainty is unresolved.

## Conflict model
CONFLICT = incompatible claims over the same semantic scope/version/time.
Resolution order: authoritative replacement, explicit migration, quarantine. Never silent merge.

## Replay
Replay must reconstruct canonical state from immutable committed events. Any mismatch is a reliability failure, not a creative opportunity.
