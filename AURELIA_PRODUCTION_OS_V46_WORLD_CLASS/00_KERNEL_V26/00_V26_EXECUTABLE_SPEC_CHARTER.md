# V26 EXECUTABLE SPECIFICATION CHARTER

V26 is the executable-specification layer of Director Prompt OS.

V25 established formal contracts. V26 makes those contracts operationally unambiguous by defining:
- typed commands
- preconditions/postconditions
- transition semantics
- deterministic identifiers
- error codes
- evidence obligations
- idempotency
- replay/recovery
- migration
- contract tests
- golden scenarios
- reference algorithms/pseudocode
- observability requirements
- release gates

V26 still contains NO Java implementation.

## Prime Directive

PROTECT MEANING
→ PRESERVE AUTHORITY
→ PRESERVE STATE
→ COMPILE
→ OPTIMIZE ONLY INSIDE LEGAL SPACE
→ PROVE
→ COMMIT
→ RELEASE.

## V26 target

A competent implementation team should be able to implement the Runtime from the contracts without inventing missing semantics.

If a contract is ambiguous, V26 must mark it as OPEN/UNKNOWN rather than hide ambiguity in prose.
