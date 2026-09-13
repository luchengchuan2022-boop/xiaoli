# RETRY POLICY

Retry is legal only when:
- operation is classified retryable
- idempotency key is stable
- expected revision is still valid or reconciliation is performed
- no semantic side effect has been duplicated

Unknown outcome is not permission to blindly retry.
