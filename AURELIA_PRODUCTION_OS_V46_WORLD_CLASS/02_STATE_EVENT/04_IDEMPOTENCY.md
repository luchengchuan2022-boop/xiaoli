# IDEMPOTENCY

The semantic operation identity is represented by an idempotency key.

Repeated execution of the same operation:
- returns the existing outcome when safely known, or
- enters reconciliation when outcome is indeterminate.

It must never create a second semantic effect.
