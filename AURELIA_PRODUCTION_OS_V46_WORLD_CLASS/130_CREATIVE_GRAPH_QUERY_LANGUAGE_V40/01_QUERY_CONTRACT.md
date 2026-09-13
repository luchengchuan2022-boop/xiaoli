# Query Contract

A query must declare:
query_id, purpose, root_nodes, temporal_scope, authority_filter, edge_types, closure_policy, freshness_policy, confidence_policy, context_budget, output_schema.

The engine must return provenance for every returned fact and must identify omitted dependencies caused by budget limits.

### Forbidden
- unbounded context stuffing
- treating inferred text as committed truth
- implicit write through query side effects
- silently mixing historical and current state
