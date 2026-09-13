# V40 Golden Tests

## G01 — Continue
Given committed Episode N end state, “继续” cannot restart, contradict or duplicate prior state.

## G02 — Graph Query Safety
A read-only query cannot mutate truth or create an implicit fact.

## G03 — Bidirectional Trace
A 15s atom traces to its story/character/relationship/world sources, and a Canon change returns impacted production artifacts.

## G04 — Candidate Tournament
Candidate scoring uses frozen context; generator self-voting cannot become final authority.

## G05 — Irreversible Decision
High-blast-radius Canon change blocks without required review/impact analysis.

## G06 — Semantic Diff
A change in character knowledge is classified as semantic even when wording remains similar.

## G07 — Prompt Integrity
Prompt compiler cannot introduce a new motivation, relationship or world rule.

## G08 — Pretty-but-Empty
A beautiful shot with no dramatic function fails.

## G09 — Relationship Jump
Relationship delta without causal/evidentiary support fails.

## G10 — Reveal Fairness
Reveal that violates audience knowledge contract fails.

## G11 — Identity Drift
Character identity invariants cannot be silently changed by prompt generation.

## G12 — 15s Closure
Shot durations sum exactly 15.00 seconds.

## G13 — Proof Closure
Missing provenance or validation blocks commit.

## G14 — Future Option Destruction
A candidate that wins locally but destroys high-value future space is rejected or escalated.

## G15 — Model Failure Isolation
Model output failure does not mutate Canon.

## G16 — Repair Root Cause
Prompt repair cannot conceal an upstream semantic defect.

## G17 — Context Compression
Compressed context that omits a dependency required for a decision fails closed.

## G18 — Replay
Same semantic inputs and compiler contract reproduce the same package structure and semantic trace.
