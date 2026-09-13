# V22 Event & State Protocol

State is derived from authorized events or transactions, not arbitrary document overwrites.

Every event has:
`event_id, aggregate_id, expected_revision, resulting_revision, event_type, actor, authority, semantic_delta, payload_hash, timestamp, causation_id, correlation_id, idempotency_key`

Duplicate delivery of the same idempotency key must have one semantic effect.
