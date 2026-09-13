# Evidence Contract

Every production artifact has: source identity, semantic inputs, compiler version, model adapter, execution parameters, output hash, validation results and lineage.

Re-running the same semantic input under the same declared compiler and adapter contract must produce the same semantic package structure, even if external model pixels differ.

Semantic determinism is mandatory; pixel determinism is model-dependent and must not be falsely claimed.
