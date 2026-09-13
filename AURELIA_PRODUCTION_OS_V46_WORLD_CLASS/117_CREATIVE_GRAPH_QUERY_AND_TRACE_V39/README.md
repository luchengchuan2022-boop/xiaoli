# V39 — Creative Graph Query & Bidirectional Trace

## Purpose
Turn the V38 Creative Graph into a queryable semantic substrate. V39 does not add a second truth store. It defines how production reasoning asks for the minimum sufficient graph slice and how every production decision traces backward to authoritative causes and forward to affected descendants.

## Core contract
`QUERY -> AUTHORITY FILTER -> TEMPORAL FILTER -> DEPENDENCY CLOSURE -> MINIMUM SUFFICIENT SUBGRAPH -> PROVENANCE -> ANSWER`

Every answer must expose: authority, source object IDs, temporal scope, confidence class, dependency closure, and unresolved conflicts.

## Query classes
- `STATE_AT(time, scope)`
- `WHY(object_id)`
- `WHY_NOW(beat_id)`
- `WHO_KNOWS(fact_id, time)`
- `WHAT_CHANGES_IF(object_id, delta)`
- `WHAT_DEPENDS_ON(object_id)`
- `WHAT_BECOMES_INVALID_IF(object_id)`
- `TRACE_PROMPT_TO_SOURCE(prompt_fragment)`
- `TRACE_CANON_TO_PRODUCTION(canon_id)`
- `TRACE_PRODUCTION_TO_CANON(artifact_id)`
- `FIND_CONTRADICTIONS(scope)`

## Hard rules
1. Retrieval may not promote inference to truth.
2. Query results are read-only unless an explicit authorized transition is invoked.
3. Minimum sufficient context beats context stuffing.
4. A query must fail closed when authority or temporal scope is ambiguous for a critical decision.
5. Bidirectional trace is semantic trace, not merely file-path trace.
