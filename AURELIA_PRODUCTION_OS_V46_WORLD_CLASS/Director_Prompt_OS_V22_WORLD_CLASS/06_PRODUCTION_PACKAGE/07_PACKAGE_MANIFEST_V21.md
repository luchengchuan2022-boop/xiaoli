# Production Package Manifest V21

A package is a dependency-closed, reproducible production unit.

Manifest must identify:
- package_id/revision;
- source story refs;
- state snapshot;
- canon/profile refs;
- scene/shot graph;
- assets and reference slots;
- PromptAST and rendered prompts;
- model adapter/capability profile;
- evidence;
- QA results;
- patches;
- release decision;
- checksums.

If a required dependency is absent, package status is `INCOMPLETE`, never silently completed.
