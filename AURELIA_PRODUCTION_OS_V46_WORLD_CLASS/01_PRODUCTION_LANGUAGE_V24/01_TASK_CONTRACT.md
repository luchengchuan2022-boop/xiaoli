# V24 Task Contract

Required fields: `task_id, mode, goal, input_refs, authority_scope, context_policy, allowed_mutations, forbidden_mutations, required_outputs, gates, failure_policy, commit_policy, compiler_version, profile_version, idempotency_key`.

Modes: `CREATE / CONTINUE / COMPILE / REPAIR / REVIEW / PLAN / WRITEBACK / MIGRATE / RECOVER / REBUILD / RELEASE`.
No task may infer authority from natural-language tone, urgency, or user intent alone; authority is typed in the contract.
