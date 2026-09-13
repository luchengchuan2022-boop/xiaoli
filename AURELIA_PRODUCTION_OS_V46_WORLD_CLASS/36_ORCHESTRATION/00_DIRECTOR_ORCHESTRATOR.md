# Director Orchestrator

The Orchestrator coordinates bounded specialists. It does not become a new source of truth.

Required flow:
INTENT → PLAN → SPECIALIST PROPOSALS → CONSTRAINT CHECK → ARBITRATION → COMPILE → VALIDATE → PACKAGE

Every specialist has a declared scope and cannot mutate another domain directly.
