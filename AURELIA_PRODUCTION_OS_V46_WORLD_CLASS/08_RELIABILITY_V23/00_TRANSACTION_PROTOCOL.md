# V23 Transaction Protocol

`PREPARE → LOCK/REVISION_CHECK → VALIDATE → AUTHORIZE → APPLY → VERIFY → COMMIT → ACK`.

Failure semantics:
- recoverable failure → retry/replay from checkpoint;
- indeterminate outcome → quarantine and evidence reconciliation;
- semantic conflict → no commit;
- authorization failure → no mutation.
