# V23 Identity and Deduplication

Deduplication is semantic, not filename-based.

The engine compares stable identity candidates, canonical type, provenance, semantic hash, parent lineage, and declared equivalence.

Never merge two objects solely because their names match. Never split one lineage solely because its display label changed.

Ambiguous matches become `DUPLICATION_CANDIDATE`, not automatic merges.
