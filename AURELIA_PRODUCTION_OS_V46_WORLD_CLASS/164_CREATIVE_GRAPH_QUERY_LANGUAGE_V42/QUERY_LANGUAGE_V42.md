# CREATIVE GRAPH QUERY LANGUAGE V42

A query is a typed request for a bounded semantic view. It MUST declare purpose, scope, temporal horizon, authority requirements and maximum context budget.

## Core operations
`GET_STATE`, `TRACE_UPSTREAM`, `TRACE_DOWNSTREAM`, `IMPACT`, `DEPENDENCY_CLOSURE`, `FIND_CONFLICTS`, `FIND_PROMISES`, `FIND_DEBTS`, `FIND_KNOWLEDGE_GAPS`, `FIND_CONTINUITY_LOCKS`, `COMPARE_VERSIONS`, `FORECAST`, `BUILD_CONTEXT`.

## Safety
- no implicit writes
- no hidden expansion beyond declared scope
- no context stuffing as a substitute for graph retrieval
- every returned claim retains source identity
- stale projections are marked stale, never silently refreshed as truth

## Example
`IMPACT(object=world_rule:star_energy, horizon=series, include=episodes|atoms|assets|promises)`
