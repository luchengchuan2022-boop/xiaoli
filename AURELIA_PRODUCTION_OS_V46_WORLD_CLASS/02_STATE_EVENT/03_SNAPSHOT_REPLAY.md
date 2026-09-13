# SNAPSHOT / REPLAY

A recoverable runtime requires:
Snapshot + ordered event history + schema version + compiler/profile versions.

Replay must be deterministic with respect to declared deterministic inputs.
Non-deterministic external observations must remain evidence-bound observations, not hidden state.
