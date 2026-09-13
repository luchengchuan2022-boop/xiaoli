# DETERMINISM CLASSES

D0 PURE_DETERMINISTIC
D1 ENVIRONMENT_DETERMINISTIC
D2 MODEL_CONFIG_DETERMINISTIC
D3 STOCHASTIC_EXTERNAL
D4 UNKNOWN_EXTERNAL.

Structural compilation should target D0/D1.
Neural generation may be D3.
The system must record the class instead of pretending all outputs are deterministic.
