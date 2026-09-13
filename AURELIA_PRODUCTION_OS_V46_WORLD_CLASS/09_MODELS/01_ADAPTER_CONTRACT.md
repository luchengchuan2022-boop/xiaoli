# ADAPTER CONTRACT

Adapter responsibilities:
translate Prompt AST to model-specific representation
negotiate capabilities
record unsupported features
preserve protected semantics
record parameters
normalize model result metadata.

Adapter may not invent story content to fill unsupported semantics without explicit fallback policy.
