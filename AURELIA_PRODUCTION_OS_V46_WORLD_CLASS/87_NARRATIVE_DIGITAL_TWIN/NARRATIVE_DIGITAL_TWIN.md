# NARRATIVE DIGITAL TWIN V37

## State layers
WORLD / TIME / LOCATION / CHARACTER / RELATIONSHIP / KNOWLEDGE / OBJECT / EVENT / PROMISE / DEBT / MYSTERY / MOTIF / AUDIENCE / VISUAL ASSET / PRODUCTION STATUS.

## State semantics
- SNAPSHOT = what is true now.
- EVENT = what changed it.
- CAUSAL_EDGE = why it changed.
- EVIDENCE = why the system is allowed to believe it.
- PROJECTION = possible future, never truth.

## Twin queries
The system must support conceptual queries such as:
- What must remain true if Episode N continues?
- Which unresolved promises are eligible to pay off now?
- Which characters possess the knowledge required for this reveal?
- What downstream artifacts depend on this costume/prop/location fact?
- What changes if this beat is removed?
- Which future options would be destroyed by this decision?

## No prose memory as authority
Summaries are retrieval aids. Canonical state is represented by typed facts, events and evidence.

## State checksum
A production context is frozen by a deterministic hash over selected authoritative facts plus dependency versions. Any material change invalidates the compiled decision context.
