# CONTEXT INTEGRITY

A frozen Context Packet is immutable.

If source state changes after freeze:
CONTEXT_STALE.

The task must either:
reuse the frozen packet intentionally,
or compile a new packet.

Never silently mix revisions.
