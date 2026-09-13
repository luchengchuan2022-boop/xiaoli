# Projection Model

Canonical history is reconstructed from committed events. Every projection records source event position, version, hash and schema version.

Checks: event-position continuity, deterministic semantic projection, invariant preservation, dependency completeness, hash agreement.

If a projection diverges, repair the projection from history; never repair history to fit the projection.
