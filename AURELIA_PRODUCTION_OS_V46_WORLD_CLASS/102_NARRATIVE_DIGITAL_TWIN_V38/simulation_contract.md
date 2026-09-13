# Simulation Contract

`COMMITTED_STATE + RULES + AGENTS + PRESSURES + TIME -> CANDIDATE EVENTS -> PREDICTED CONSEQUENCES`.

Every prediction is labeled `PREDICTION`, carries assumptions, confidence and affected nodes, and expires when its assumptions change.

Simulation must support: forward projection, counterfactual branch, sensitivity analysis, blast-radius estimation and contradiction detection.

No simulation output may be promoted to truth without an explicit authorized transition.
