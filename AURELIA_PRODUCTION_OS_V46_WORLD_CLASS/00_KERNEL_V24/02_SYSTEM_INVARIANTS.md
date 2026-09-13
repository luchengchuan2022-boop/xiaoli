# V24 System Invariants

- One semantic fact has one canonical identity within a project namespace.
- Every mutable canonical object has a revision.
- Every committed mutation is attributable to an event/transaction.
- Every derived artifact retains lineage to its source objects and compiler inputs.
- A failed validation cannot become a committed release.
- A stale revision cannot overwrite a newer committed revision without explicit conflict handling.
- Prompt text cannot mutate Canon or committed State.
- A model capability gap is observable and cannot be silently converted into semantic loss.
- Context packets are derived views, never alternate sources of truth.
- A 15s atom may have zero semantic state delta when its purpose is attention, emotion, tension, atmosphere, or setup; this must be explicit.
