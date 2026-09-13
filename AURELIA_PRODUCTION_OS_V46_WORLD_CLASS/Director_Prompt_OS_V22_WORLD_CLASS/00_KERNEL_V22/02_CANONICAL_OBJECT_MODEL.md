# V22 Canonical Object Model

Every durable production concept is a typed object.

Required identity fields:
- `object_id`
- `object_type`
- `schema_version`
- `revision`
- `authority`
- `status`
- `provenance`
- `semantic_hash`
- `created_from`
- `derived_from`
- `dependencies`

## Identity law

A display name is never an identity. Renaming must not create a new semantic entity unless the change is explicitly classified as identity mutation.

## Object families

`CANON_FACT, STORY_DECISION, WORLD_RULE, CHARACTER, RELATIONSHIP, TIMELINE_EVENT, KNOWLEDGE_STATE, EMOTIONAL_STATE, DRAMATIC_INTENT, BEAT, SCENE, SHOT, PERFORMANCE, CAMERA, AUDIO, VFX, ASSET, CONSTRAINT, PRODUCTION_IR, PROMPT_AST, TASK, EVENT, PATCH, EVIDENCE, VALIDATION, PACKAGE, RELEASE`

## Projection rule

Documents, prompts, database rows, UI fields, and generated files are projections of canonical objects unless explicitly designated authoritative.
