# Checkpoint and Replay V21

Checkpoint at every irreversible stage and at configurable batch boundaries.

Recovery uses:
1. last verified checkpoint;
2. event log;
3. deterministic rebuild of projections;
4. revalidation;
5. resume from the earliest unverified stage.

A crash must never force the system to guess whether a write succeeded.
