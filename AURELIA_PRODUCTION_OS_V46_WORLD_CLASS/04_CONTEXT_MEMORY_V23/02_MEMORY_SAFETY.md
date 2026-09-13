# V23 Memory Safety

Rules:
- Unknown is not false.
- Missing is not empty.
- Inference is not fact.
- Model output is not memory truth.
- Uncommitted proposal is not committed state.
- Stale context must be detected by revision checks.

A stale Context Packet cannot silently write into a newer revision.
