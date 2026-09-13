# LINEAGE RECONCILIATION V37

The V27→V36 lineage contains overlapping module families and historical packaging variations. V37 treats the current root package as the release lineage and does not create a second truth merely to preserve old labels.

## Rules
- Existing accepted contracts remain inherited unless explicitly superseded.
- Duplicate concepts are mapped to one canonical concept.
- Legacy documents are evidence of lineage, not active authority.
- A migration note must identify semantic replacement, not merely rename files.
- V37 modules may extend V36 but must not redefine a concept already authoritative elsewhere.

## V32 lineage note
An earlier V33 build did not physically inherit every separately generated V32 module directory even though V33 incorporated the semantic concepts. V37 records this as historical packaging drift and uses semantic reconciliation rather than duplicating a second V32 truth tree.
