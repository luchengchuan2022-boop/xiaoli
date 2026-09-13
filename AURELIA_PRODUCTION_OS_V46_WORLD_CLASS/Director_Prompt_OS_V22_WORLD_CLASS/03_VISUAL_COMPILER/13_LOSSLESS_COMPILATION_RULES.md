# Lossless Compilation Rules

A compiler stage may compress wording but cannot delete protected semantics.

Each stage emits:
- output object;
- semantic hash;
- inherited invariants;
- newly introduced intent;
- dropped fields (must be empty or explicitly justified);
- warnings;
- evidence.

If information is unsupported by a target adapter, mark `CAPABILITY_GAP`; never pretend it was rendered.
