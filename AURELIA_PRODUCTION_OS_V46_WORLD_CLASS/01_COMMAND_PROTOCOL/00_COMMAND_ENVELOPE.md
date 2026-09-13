# COMMAND ENVELOPE

Every runtime operation is represented by a typed command envelope:

command_id
command_type
command_version
project_id
aggregate_refs
expected_revisions
authority_context
actor
correlation_id
causation_id
idempotency_key
input_payload
policy_refs
requested_outputs
created_at

Commands are immutable requests.
Results are separate immutable records.
