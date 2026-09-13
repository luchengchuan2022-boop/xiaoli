# CREATIVE GRAPH RUNTIME V42

## 1. Canonical object identity
Every object has `object_id`, `object_type`, `version`, `authority_ref`, `provenance`, `valid_time`, `record_time`, `lifecycle`, and `semantic_hash`.

## 2. Typed edges
Allowed semantic relations include `CAUSES`, `DEPENDS_ON`, `PRECEDES`, `CONTRADICTS`, `SUPPORTS`, `DERIVES_FROM`, `TRANSFORMS`, `CONSUMES`, `MUST_MATCH`, `EXPRESSES`, `PROMISES`, `PAYS_DEBT`, `AFFECTS`, `KNOWS`, `BELIEVES`, and `REVEALS`.
Edges require evidence or explicit declaration according to edge policy.

## 3. Event semantics
State mutation occurs only through authorized events. Events are immutable records. A projection may be rebuilt from committed events.

## 4. Conflict model
Conflicting claims enter `CONFLICT_QUARANTINE`; the runtime never resolves conflict by recency, majority vote, model confidence, or prompt wording alone.

## 5. Query safety
Queries are read-only unless an explicit command contract authorizes a mutation. Query results carry authority and freshness metadata.
