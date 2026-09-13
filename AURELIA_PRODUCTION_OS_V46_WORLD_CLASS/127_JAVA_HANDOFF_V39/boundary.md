# Boundary Rules

1. SQLite or the eventual canonical state store remains the single truth authority in the implementation phase.
2. Filesystem artifacts are evidence/cache/export/recovery material, never a competing truth store.
3. Prompt text is an instruction artifact, not a database schema.
4. Model output is observation/evidence until validated and committed.
5. Every write has an idempotency identity and provenance.
6. Every contract has version and compatibility rules.
