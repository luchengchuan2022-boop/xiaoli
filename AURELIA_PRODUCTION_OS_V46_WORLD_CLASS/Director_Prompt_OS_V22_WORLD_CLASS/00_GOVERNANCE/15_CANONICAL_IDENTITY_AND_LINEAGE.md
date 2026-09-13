# Canonical Identity and Lineage

Every canonical object has a stable logical identity independent of wording, prompt, file path, or model.

Required concepts:
- `object_id`: stable identity.
- `revision_id`: immutable revision.
- `parent_revision_id`: lineage.
- `semantic_hash`: meaning fingerprint.
- `provenance`: source and transformation chain.
- `authority`: who/what may authorize mutation.
- `status`: lifecycle state.

Copies are not new facts. Rewrites are not new facts unless their semantic delta says so.

A prompt string, image filename, or model response must never become the identity of a story/world/character/state object.
