# CONTEXT COMPILER

Input:
task + authority scope + current revision + relevance policy.

Output:
Context Packet with source refs, revisions, relevance scores, authority, inclusion rationale, and exclusions.

The compiler must prevent:
- irrelevant context flooding
- stale state
- hidden assumptions
- cross-project leakage
- profile contamination.

Context is a projection, never a second Canon.
