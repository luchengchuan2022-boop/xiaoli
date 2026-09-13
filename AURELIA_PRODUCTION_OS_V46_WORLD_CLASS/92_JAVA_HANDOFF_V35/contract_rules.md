# Java Contract Rules V35

1. Stable IDs and semantic hashes are mandatory.
2. Every mutation carries expected revision and explicit delta.
3. Unknown contract versions fail closed.
4. Model adapters are replaceable and cannot own Canon.
5. Validation is deterministic wherever possible.
6. Prompt text is a compiled artifact, not a database truth object.
7. Evidence and provenance survive serialization.
8. Replay must reproduce semantic decisions from the same frozen context.
9. One canonical truth store; no shadow Canon in prompt files.
