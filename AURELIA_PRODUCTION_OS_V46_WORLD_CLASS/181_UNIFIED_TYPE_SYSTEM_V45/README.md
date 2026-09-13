# V45 Unified Type System

## Purpose
Collapse the growing Production OS vocabulary into one canonical semantic type system.

## Core object envelope
Every first-class object MUST expose:
- object_id
- object_type
- schema_version
- authority_class
- provenance
- valid_time
- record_time
- lifecycle_state
- semantic_hash
- dependencies
- confidence
- scope

## Type families
TRUTH, STATE, EVENT, ENTITY, RELATIONSHIP, RULE, PROMISE, DEBT, MOTIF, DRAMATIC_INTENT, DECISION, CANDIDATE, OBSERVATION, EVIDENCE, CINEMATIC_INTENT, SHOT, KEYFRAME, PROMPT_AST, ASSET, PRODUCTION_PACKAGE, PROOF, PROJECTION.

## Non-negotiable distinctions
Truth != State != Event != Decision != Candidate != Observation != Evidence != Projection.
A derived projection can never outrank its source authority.
Temporal adjacency does not imply causality.
Similarity does not imply identity.
Model output never becomes truth without an authorized transaction.

## Type compatibility
Every edge and transition declares source type, target type, cardinality, authority requirement, temporal semantics, and whether mutation is permitted. Invalid edges are rejected before creative selection.
