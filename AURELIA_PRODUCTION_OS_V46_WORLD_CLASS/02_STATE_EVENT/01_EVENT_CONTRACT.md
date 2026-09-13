# EVENT CONTRACT

Every state-changing event contains:

event_id
event_type
aggregate_refs
expected_revision
causation_id
correlation_id
idempotency_key
actor
authority
semantic_delta
payload
timestamp
provenance

Events are facts about authorized transitions, not free-form logs.
