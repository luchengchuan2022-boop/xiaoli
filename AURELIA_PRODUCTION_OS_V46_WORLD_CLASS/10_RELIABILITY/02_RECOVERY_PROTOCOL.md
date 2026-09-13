# RECOVERY PROTOCOL

Detect
→ freeze affected scope
→ collect evidence
→ reconcile transaction/event status
→ restore latest valid snapshot
→ replay authorized events
→ validate
→ commit recovery
→ record recovery evidence.

Recovery must never invent missing history.
