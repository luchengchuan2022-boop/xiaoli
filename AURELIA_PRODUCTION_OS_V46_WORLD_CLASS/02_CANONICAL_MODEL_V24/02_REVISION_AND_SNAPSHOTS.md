# V24 Revision & Snapshot Model

Committed revisions are immutable. New changes create a new revision.

Snapshots capture the minimum complete state required for deterministic continuation or recovery.
Stale writes fail closed unless an explicit merge/conflict policy is authorized.
