# V42 Creative Graph Runtime Specification

V42 defines the semantic runtime contract that unifies creative objects, edges, events, state, time, causality, authority, versions, decisions, evidence and production artifacts.

## Prime rule
There is exactly one semantic identity for an object within a project lineage. A prompt, file, model output, cache entry or materialized view is never a second truth.

## Runtime layers
AUTHORITY → OBJECT → EDGE → EVENT → STATE → QUERY → DECISION → COMPILATION → ARTIFACT → OBSERVATION → EVIDENCE → VALIDATION → COMMIT.

## Non-negotiable distinctions
- temporal precedence is not causality
- correlation is not explanation
- candidate is not truth
- observation is not interpretation
- interpretation is not canon
- recommendation is not authorization
- rendered artifact is not semantic state
- context is a projection, never a new source of truth

All runtime operations MUST expose identity, provenance, authority, temporal scope and lifecycle.
