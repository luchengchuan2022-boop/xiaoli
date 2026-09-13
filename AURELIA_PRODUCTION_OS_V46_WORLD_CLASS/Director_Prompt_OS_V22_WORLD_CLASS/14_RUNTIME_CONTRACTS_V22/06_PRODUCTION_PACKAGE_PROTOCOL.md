# V22 Production Package Protocol

A Production Package is a dependency-closed, provenance-complete, reproducible delivery unit.

Minimum graph:
`source → intent → IR → assets → prompts → execution → observation → evidence → validation → release`

The manifest records object IDs, revisions, hashes, dependencies, compiler/profile/adapter versions, and release status.

A package is not complete merely because all expected filenames exist.
