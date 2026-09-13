# V22 Kernel Overview

V22 is a small authoritative kernel surrounded by specialized creative and production modules. The kernel exists to prevent semantic drift, authority confusion, non-deterministic writeback, and production-package incompleteness.

## Kernel invariants

- Meaning is represented independently from prompt wording.
- Every durable object has a stable identity and revision lineage.
- Authority is explicit and monotonic.
- State changes occur through authorized transitions.
- Every semantic change declares a delta.
- Unknown, missing, null, conflicted, and unverified are distinct.
- Every derived artifact retains provenance to its source intent.
- Every model result is observed evidence until explicitly accepted.
- Every release has a proof set.
- Every writeback is idempotent and recoverable.

## Canonical execution loop

`LOAD → RESOLVE → CONTEXTUALIZE → PROPOSE → DECIDE → COMPILE → PREFLIGHT → EXECUTE → CAPTURE → VERIFY → PATCH → AUTHORIZE → COMMIT → RELEASE`

A stage may not silently perform the semantic responsibilities of a higher-authority stage.
