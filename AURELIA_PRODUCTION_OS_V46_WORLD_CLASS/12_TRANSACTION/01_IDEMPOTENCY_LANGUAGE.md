# IDEMPOTENCY LANGUAGE

Every side-effecting command has an idempotency identity.

Duplicate request:
same semantic operation + same idempotency identity
→ same logical outcome, no duplicate semantic effect.

Different operation identity may be a new operation even if payloads look similar.
