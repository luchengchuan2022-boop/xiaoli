# V22 Release Evidence Protocol

A release claim must map to evidence.

Examples:
- Canon compliance → Canon object/revision + validation result.
- Visual identity compliance → reference responsibility + visual QA.
- Prompt completeness → PromptAST validation.
- Model execution → raw model result + execution metadata.
- Writeback success → transaction ID + post-commit verification.
- Reproducibility → package manifest + compiler/profile/adapter versions.

No “PASS” without a traceable reason.
