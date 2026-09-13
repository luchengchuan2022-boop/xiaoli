# V23 Semantic Loss Budget

Every compiler boundary declares whether transformation is:
`LOSSLESS`, `CONTROLLED_PRESENTATION_VARIATION`, or `SEMANTIC_CHANGE`.

Semantic change requires an authorized decision and a new semantic delta.

The compiler must report dropped, approximated, unsupported, or ambiguous requirements rather than silently deleting them.
