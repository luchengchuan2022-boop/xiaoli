# Migration Protocol

For high-blast-radius changes:
1. Freeze source version.
2. Produce semantic diff.
3. Calculate dependency closure.
4. Mark affected future work.
5. Generate migration candidates.
6. Run regression and contradiction checks.
7. Obtain required authority.
8. Commit new version.
9. Preserve old lineage.

No destructive migration is allowed without a recoverable prior state.
