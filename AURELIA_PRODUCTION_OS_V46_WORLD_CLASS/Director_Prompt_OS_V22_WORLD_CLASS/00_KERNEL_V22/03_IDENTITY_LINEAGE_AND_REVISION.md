# Identity, Lineage and Revision Contract

## Revision model

Every mutation creates a new revision or an append-only event that deterministically produces a new revision.

`object_id` remains stable across revisions. `revision` increases monotonically within that object lineage.

## Lineage requirements

Every derived artifact records:
- source object IDs and revisions;
- compiler/renderer version;
- profile version;
- model adapter version when applicable;
- semantic delta;
- task ID;
- evidence IDs.

## Forks

Experimental work may fork from a committed revision. A fork is never production truth until explicitly merged and committed.

## Merge

Merge requires conflict classification, semantic diff, authority check, and validation of downstream dependency closure.
