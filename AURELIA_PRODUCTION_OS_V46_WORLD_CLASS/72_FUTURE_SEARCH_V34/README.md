# Future Story Search V34

The system does not greedily choose the next episode. It searches a bounded legal future space.

## Horizons
ATOM 15S → EPISODE → SEQUENCE → ARC → SEASON → SERIES → 1600/8000+

## Search stages
STATE SNAPSHOT → LEGAL ACTION SPACE → CANDIDATE GENERATION → CAUSAL FORECAST → CHARACTER FORECAST → RELATIONSHIP FORECAST → AUDIENCE FORECAST → PRODUCTION COST/RISK → LONG-HORIZON VALUE → PARETO FILTER → DIRECTOR ARBITRATION.

Use bounded beam/Pareto search conceptually; do not explode the search space.

A candidate is rejected when it violates Canon, requires unexplained character knowledge, causes unbounded lore, consumes a protected future reveal without authorization, or creates unrecoverable continuity debt.
