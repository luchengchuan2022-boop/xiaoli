# Semantic Versioning and Diff V40

V40 compares creative states semantically, not by text diff alone.

## Diff classes
UNCHANGED, REPRESENTATION_ONLY, ADDITIVE, REMOVAL, TRANSFORM, MOVE_IN_TIME, AUTHORITY_CHANGE, RELATIONSHIP_CHANGE, KNOWLEDGE_CHANGE, RULE_CHANGE, PROMISE_CHANGE, CINEMATIC_REINTERPRETATION.

## Required output
old_state → semantic_delta → impacted_nodes → invalidations → required recompilation → regression suites → approval status.
