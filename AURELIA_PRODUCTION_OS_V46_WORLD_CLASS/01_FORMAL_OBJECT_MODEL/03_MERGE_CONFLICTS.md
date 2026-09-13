# OBJECT MERGE AND CONFLICTS

Merging is permitted only when semantic ownership and authority are compatible.

Conflict classes:
- identity conflict
- revision conflict
- field ownership conflict
- semantic conflict
- dependency conflict
- temporal conflict
- authority conflict

Default behavior: preserve both candidates, mark CONFLICTED, request arbitration.
Never silently choose the last writer.
