# Policy as Code

Creative policy must be expressible as testable predicates, not only prose.

Examples:
- protected canon path cannot be mutated by a prompt renderer;
- a committed state transition must reference an authorized event;
- every released artifact must have evidence and dependency closure;
- unsupported model capability cannot be silently omitted;
- duplicate event IDs cannot produce duplicate commits.

Natural language explains policy; machine-checkable predicates enforce it.
