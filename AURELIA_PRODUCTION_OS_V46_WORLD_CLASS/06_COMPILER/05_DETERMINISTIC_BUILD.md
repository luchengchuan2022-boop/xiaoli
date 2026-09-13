# DETERMINISTIC BUILD

Given:
same authoritative revisions
same compiler versions
same declared policies
same deterministic inputs

the structural build must reproduce the same IR hashes and dependency graph.

Model generation may be probabilistic; the production record must preserve exact inputs, adapter version, model metadata, and observations.
