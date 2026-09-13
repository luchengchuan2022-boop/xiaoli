# V23 Idempotency and Exactly-Once

Exactly-once means exactly one semantic effect, not necessarily one network delivery.

Every mutating command requires an idempotency key and expected revision. Duplicate delivery returns the original outcome or an equivalent deterministic acknowledgment without applying a second semantic effect.
