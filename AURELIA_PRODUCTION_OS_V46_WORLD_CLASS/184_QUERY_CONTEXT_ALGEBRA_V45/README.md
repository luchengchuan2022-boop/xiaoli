# V45 Query + Context Algebra

## Query primitives
GET, TRACE_UPSTREAM, TRACE_DOWNSTREAM, DEPENDENCY_CLOSURE, IMPACT, CONFLICTS, VERSION_DIFF, PROMISES, DEBTS, KNOWLEDGE_GAPS, CONTINUITY_LOCKS, FORECAST, REPLAY, BUILD_CONTEXT.

## Context contract
Context = required claims + dependency closure + authority filter + temporal filter + character knowledge filter + continuity locks + task contract + compression log + context hash.

Minimum Sufficient Context MUST preserve every dependency required to make the requested decision without inventing missing truth.

## Context firewall
Character knowledge, audience knowledge, narrator knowledge, and canonical truth are separate projections. A context packet must declare whose knowledge it represents.

## Determinism
Same frozen semantic inputs + same policy + same compiler version => same semantic context hash and equivalent AST structure.
