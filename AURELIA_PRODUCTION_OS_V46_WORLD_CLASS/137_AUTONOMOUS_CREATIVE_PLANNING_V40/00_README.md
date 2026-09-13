# Autonomous Creative Planning V40

Autonomy is bounded. Agents may search, compare, simulate, critique and compile candidates. They may not silently mutate Canon or committed state.

## Planner contract
INPUT frozen state + objective + constraints + horizon + budget.
OUTPUT plan candidates + assumptions + expected value + risks + stop reason.

A planner must stop when the objective is satisfied, uncertainty is irreducible, budget is exhausted, or further search is dominated.
