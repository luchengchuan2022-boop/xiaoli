# JAVA BOUNDARY RULES

1. SQLite/DB may be canonical persistence only after the future runtime chooses an implementation.
2. Files are artifacts/evidence/cache/materialization, never a second truth.
3. External model output enters as observation/evidence and cannot directly commit truth.
4. Transactions commit authorized events atomically.
5. Idempotency and replay are first-class.
6. Creative decisions remain inspectable and provenance-complete.
