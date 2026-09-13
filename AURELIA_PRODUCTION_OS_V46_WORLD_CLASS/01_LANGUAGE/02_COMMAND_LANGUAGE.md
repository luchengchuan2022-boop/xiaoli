# COMMAND LANGUAGE

A command MUST declare:
intent
target
scope
authority
expected revision/state
idempotency key
input
requested outputs
policy refs.

Example semantic form:

CONTINUE(target=PROJECT, from=LATEST_COMMITTED, scope=NEXT_ATOM,
         preserve=CANON+STATE+RELATIONSHIP+CONTINUITY,
         produce=PRODUCTION_PACKAGE)

The example is illustrative, not a hidden shortcut around validation.
