# V41 Semantic Event Sourcing

## Principle
Long-form creative state is reconstructed from authoritative events, not from mutable prose snapshots.

`Committed State = Reduce(Genesis + Ordered Authorized Events)`

## Event contract
Each event records: event_id, aggregate_id, event_type, prior_version, resulting_version, semantic_delta, actor, authority, evidence_refs, causality_refs, idempotency_key, timestamp, hash, commit_status.

## Rules
1. Event order is not automatically causal.
2. An event without authority is evidence/candidate, never Canon mutation.
3. Replay must reconstruct the same semantic state for the same committed event stream.
4. Snapshots are caches; event lineage remains authoritative.
5. Failed transactions never enter the committed stream.

## Creative event classes
`CHARACTER_CHOICE, RELATIONSHIP_SHIFT, KNOWLEDGE_GAIN, WORLD_RULE_CHANGE, PROMISE_CREATED, PROMISE_FULFILLED, DEBT_CREATED, REVEAL_COMMITTED, STORY_BEAT_COMMITTED, PRODUCTION_RESULT_ACCEPTED`.
