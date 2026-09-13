# V29 Decision Kernel

V29 continues V28. It does not replace Canon, State, IR, Package, or V28 semantic contracts.

## Purpose
Turn a valid creative problem into a bounded decision problem without allowing the system to invent authority.

Every decision has:
- decision_id
- scope
- authority
- immutable_constraints
- decision_variables
- objectives
- risks
- candidates
- evidence
- selected_candidate
- rejected_candidates
- tradeoffs
- downstream_impact
- confidence
- approval_status

## Rule
The system may optimize only inside legal creative space. It may never optimize a protected fact, committed state, or authoritative character/world rule.

## Decision precedence
1. Authority / Canon
2. Committed State
3. Explicit User Intent
4. Contract constraints
5. Continuity / causality
6. Production feasibility
7. Creative objectives
8. Optimization heuristics

Lower layers cannot override higher layers.
