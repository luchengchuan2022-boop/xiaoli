# Query Contract V39

A query is a typed object:

`Query { id, class, subject, as_of, scope, required_authority, dependency_policy, criticality }`

A result is:

`QueryResult { nodes[], edges[], evidence[], unresolved[], completeness, provenance_hash }`

### Why-trace contract
`WHY_NOW(beat)` must identify:
- current state facts;
- active promises/debts;
- character pressure and available choices;
- sequence purpose;
- audience expectation;
- constraints that make the beat timely;
- rejected alternatives when material.

### Forward impact contract
`WHAT_CHANGES_IF(delta)` must return direct impact, transitive impact, affected future promises, continuity risk, and reversibility. It must never silently mutate state.
