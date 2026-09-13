# V22 Decision Logic

Every consequential decision is represented as a decision record:

`decision_id, task_id, options, protected_constraints, semantic_deltas, evidence, rationale, authority, selected_option, downstream_impact, validation, commit_status`

## Selection order

1. Reject illegal options.
2. Preserve protected semantics.
3. Preserve continuity and causal integrity.
4. Satisfy dramatic objective.
5. Satisfy visual/production requirements.
6. Optimize quality, reuse, cost, latency, and model fit.

Cost or convenience can never compensate for a violated hard constraint.
