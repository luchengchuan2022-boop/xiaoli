# WRITEBACK MASTER TASK

Writeback must be transaction-based.

PREPARE
→ EXPECTED REVISION CHECK
→ VALIDATE
→ AUTHORIZE
→ APPLY
→ VERIFY
→ COMMIT
→ ACK

If outcome is indeterminate:
QUARANTINE → RECONCILE → RECOVER / ABORT.

No duplicate semantic effect.
