# MODEL GATEWAY

The Model Gateway is an external execution boundary.

Input:
Prompt AST + capability requirements + references + generation policy.

Output:
ModelRun + observations + artifact refs + metadata.

The gateway cannot mutate Canon or committed State directly.
