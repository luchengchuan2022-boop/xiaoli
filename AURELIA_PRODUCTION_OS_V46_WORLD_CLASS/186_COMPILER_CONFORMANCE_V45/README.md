# V45 Compiler Conformance

## Canonical compilation chain
SOURCE -> SEMANTIC_OBJECT -> NARRATIVE_IR -> DRAMA_IR -> CHARACTER_IR -> RELATIONSHIP_IR -> AUDIENCE_IR -> SEQUENCE_IR -> CINEMATIC_IR -> PERFORMANCE_IR -> SHOT_AST -> KEYFRAME_AST -> IMAGE_PROMPT_AST -> VIDEO_PROMPT_AST -> AUDIO_AST -> CONTINUITY -> QA -> PROOF -> MANIFEST.

## Transformation ledger
Each source claim is marked PRESERVED, TRANSFORMED, OMITTED_WITH_REASON, or INTRODUCED_AS_CINEMATIC_EXPRESSION.

INTRODUCED_AS_CINEMATIC_EXPRESSION may add only presentation, never unsupported story truth.

## Prompt conformance
Every prompt node has semantic_source_ids, constraints, temporal scope, continuity locks, model capability requirements, and negative constraints.

Prompt compiler may optimize wording, ordering, and model syntax but cannot mutate protected semantics.
