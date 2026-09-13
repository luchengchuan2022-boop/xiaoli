# SCHEMA VERSIONING

Every persisted contract has schema_version.

Compatibility classes:
READ_COMPATIBLE
WRITE_COMPATIBLE
ROUNDTRIP_COMPATIBLE
BREAKING
SEMANTIC_BREAK

Roundtrip compatibility is required for data that may be loaded, modified, and written back without semantic loss.
