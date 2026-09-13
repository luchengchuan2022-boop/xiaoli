# V24 Identity, Lineage & Deduplication

Identity uses stable project-scoped IDs. Display names are non-authoritative labels.

Deduplication must compare identity, semantic hash, provenance and explicit alias relationships; fuzzy textual similarity alone cannot merge canonical objects.
Every derived artifact records the exact source revision(s) and compiler/profile versions used to create it.
