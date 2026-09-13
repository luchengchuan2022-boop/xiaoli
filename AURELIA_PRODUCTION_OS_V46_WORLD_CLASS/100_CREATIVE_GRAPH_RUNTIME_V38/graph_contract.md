# Graph Contract

A graph mutation is valid only when `subject`, `predicate`, `object`, `authority`, `provenance`, `effective_time`, `scope`, `reason`, and `lifecycle` are present.

Allowed relation families: `CAUSES`, `ENABLES`, `CONSTRAINS`, `KNOWS`, `BELIEVES`, `PROMISES`, `OWES`, `REMEMBERS`, `TRANSFORMS`, `APPEARS_IN`, `MUST_MATCH`, `DEPENDS_ON`, `PRECEDES`, `CONTRADICTS`, `SUPPORTS`.

Never infer `CAUSES` from temporal order alone. Never infer `KNOWS` from audience knowledge or author knowledge.
