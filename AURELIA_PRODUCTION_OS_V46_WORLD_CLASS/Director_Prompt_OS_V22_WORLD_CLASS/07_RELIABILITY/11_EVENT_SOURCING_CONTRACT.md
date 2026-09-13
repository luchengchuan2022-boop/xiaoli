# Event Sourcing Contract

Every committed mutation is represented by an immutable event with:
`event_id`, `task_id`, `aggregate_id`, `expected_revision`, `payload`, `authority`, `timestamp`, `causation_id`, `correlation_id`, `semantic_delta`, `evidence_refs`.

Events are append-only. Current state is a projection, not the only record of truth.
