# V22 Error & Recovery Protocol

Errors are classified by earliest responsible layer:
`SOURCE, CANON, STATE, CONTEXT, STORY, DRAMA, VISUAL, ASSET, COMPILER, ADAPTER, EXECUTION, CAPTURE, EVIDENCE, QA, TRANSACTION, RELEASE`

Recovery principle:
**repair the earliest responsible layer and recompile downstream dependents.**

Never patch a downstream prompt to conceal an upstream canon/state/story defect.

Indeterminate transactions are quarantined until evidence establishes their actual state.
