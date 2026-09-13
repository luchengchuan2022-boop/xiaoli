# Semantic Delta Contract

Every transformation declares what changed semantically.

Fields: `delta_id`, `source_revision`, `target_revision`, `changed_paths`, `added_meaning`, `removed_meaning`, `unchanged_invariants`, `risk_class`, `authorization_required`, `evidence_refs`.

Allowed classes:
- D0 expression only
- D1 director expression
- D2 production implementation
- D3 story decision
- D4 canon change
- D5 committed state change
- D6 retcon

If a transform claims D0/D1/D2 but actually changes D3+, validation MUST fail.
