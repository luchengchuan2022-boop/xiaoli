# Transaction Boundary V21

A writeback transaction follows:
`PREPARE → VALIDATE → AUTHORIZE → APPLY → VERIFY → COMMIT → ACK`.

If verification fails, the transaction is not committed.

Retrying the same transaction with the same idempotency key must not duplicate semantic effects.
