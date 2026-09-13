# Planning Contract V39

Planner states:
`OBSERVE -> FRAME -> GENERATE -> SIMULATE -> COMPARE -> SELECT -> COMMIT_HORIZON`

Commit levels:
- `LOCAL`: safe atom/scene decision;
- `EPISODIC`: episode-level commitment;
- `ARC`: affects multiple episodes;
- `SERIES`: changes long-term architecture;
- `IP`: protected identity mutation.

Higher-level commitments require stronger evidence and explicit review. The planner must preserve unresolved uncertainty rather than inventing certainty.
