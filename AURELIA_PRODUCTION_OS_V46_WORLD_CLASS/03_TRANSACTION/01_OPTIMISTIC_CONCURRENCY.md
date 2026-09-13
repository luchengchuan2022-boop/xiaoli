# OPTIMISTIC CONCURRENCY

Writes carry expected revisions.

If current_revision != expected_revision:
STALE_REVISION.

The system must not silently merge.
A reconciliation flow may propose a merge; authorization remains separate.
