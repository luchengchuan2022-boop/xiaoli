# Creative Graph Query Language V40

A typed, read-only query language for retrieving minimum sufficient context and impact closure.

## Query intent classes
- CONTEXT: what must be known before creating an atom?
- TRACE: where did this object come from and what depends on it?
- IMPACT: what becomes invalid or risky if this object changes?
- STATE: what was true at time T?
- PROMISE: which open promises/debts/mysteries are relevant?
- PRODUCTION: which assets/prompts/atoms depend on a semantic node?
- HEALTH: which long-horizon signals are degrading?

## Example abstract form
SELECT CharacterState
WHERE character_id = X
AT time = T
WITH dependency_closure = semantic
LIMIT context_budget = B

Queries are declarative. They never mutate truth.
