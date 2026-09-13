# V24 Transaction Protocol

Canonical flow: `PREPARE → VALIDATE → AUTHORIZE → APPLY → VERIFY → COMMIT → ACK`.

If outcome is uncertain, enter `INDETERMINATE`; never assume success.
