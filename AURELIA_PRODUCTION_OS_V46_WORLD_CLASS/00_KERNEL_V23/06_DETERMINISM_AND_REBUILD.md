# V23 Determinism and Rebuild Contract

For the same committed inputs, policy, compiler version, profile version, and declared nondeterministic sources, the system must be able to reconstruct the same semantic artifacts.

Non-deterministic model outputs are observations, not hidden truth. Rebuild must preserve their provenance and distinguish regenerated observations from the original observation.

Every derived artifact records the compilation inputs and versions needed for audit or reproducibility.
