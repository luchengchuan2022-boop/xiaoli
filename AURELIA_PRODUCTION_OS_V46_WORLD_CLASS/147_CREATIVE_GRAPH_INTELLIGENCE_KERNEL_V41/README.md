# V41 Creative Graph Intelligence Kernel

## Purpose
V41 turns the Creative Graph into an operational semantic backbone rather than a collection of linked records. Every object has stable identity, type, authority, lifecycle, temporal scope, provenance, dependencies and version lineage.

## Non-negotiables
- Graph structure is not truth; authoritative objects and committed events are truth.
- An edge has explicit semantics; adjacency never implies causality.
- Every mutation is an authorized state transition represented by an event.
- Queries are read-only unless an explicit command contract authorizes a mutation.
- No creative output may create Canon merely by existing.

## Canonical object envelope
`object_id, object_type, authority, status, valid_from, valid_to, source_refs, dependency_refs, supersedes, confidence, semantic_hash, created_by, created_at`.

## Required graph edge vocabulary
`DEPENDS_ON, CAUSES, PRECEDES, ENABLES, CONTRADICTS, SUPPORTS, DERIVES_FROM, REPRESENTS, MUST_MATCH, AFFECTS, INVALIDATES, SUPERSEDES, OBSERVES`.

## Closure rule
A production decision is not complete until its required dependency closure is resolved or explicitly marked as an approved uncertainty.

## No hidden inference
Graph traversal may retrieve candidates and implications, but inferred facts must remain typed as inference/prediction until authorized.
