# JAVA IMPLEMENTATION GUARDRAILS

When implementation begins:
- contracts first
- adapters second
- persistence projections last
- no business truth in UI
- no creative truth in infrastructure
- no silent exception swallowing
- no hidden global mutable state
- no direct writes bypassing transaction manager
- no model adapter direct writes to Canon
