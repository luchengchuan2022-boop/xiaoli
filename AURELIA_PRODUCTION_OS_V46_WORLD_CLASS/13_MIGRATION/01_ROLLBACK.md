# MIGRATION ROLLBACK

Rollback must restore the previous active schema/policy boundary without deleting migration evidence.

A migration that has already produced committed semantic changes is not undone by deleting the migration file; use explicit compensating transactions where required.
