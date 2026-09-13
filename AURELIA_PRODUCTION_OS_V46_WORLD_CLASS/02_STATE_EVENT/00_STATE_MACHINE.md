# COMMITTED STATE MODEL

State is a versioned, authoritative snapshot of the production world.

State transition:
S(n) + authorized Event/Decision + preconditions
→ candidate S(n+1)
→ validation
→ commit.

A failed transition does not mutate committed state.
