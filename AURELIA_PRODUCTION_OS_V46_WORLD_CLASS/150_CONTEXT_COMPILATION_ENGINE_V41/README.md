# V41 Context Compilation Engine

## Goal
Compile the minimum sufficient context required to perform a task while preserving semantic dependencies. Context size is an optimization; dependency closure is a correctness requirement.

## Pipeline
`Task Contract → Required Claims → Dependency Closure → Authority Filter → Temporal Filter → Knowledge Firewall → Compression → Context Hash → Freeze`.

## Context classes
`CANON_TRUTH, COMMITTED_STATE, LOCAL_HISTORY, CHARACTER_KNOWLEDGE, AUDIENCE_MODEL, CREATIVE_PRECEDENT, OPEN_SPACE, UNCERTAINTY`.

## Prohibited
- context stuffing as a substitute for structure
- mixing candidate facts with committed facts
- leaking future events into present character knowledge
- silently dropping dependencies during compression

Every compiled context emits included refs, excluded refs, compression decisions, unresolved dependencies and a deterministic context hash.
