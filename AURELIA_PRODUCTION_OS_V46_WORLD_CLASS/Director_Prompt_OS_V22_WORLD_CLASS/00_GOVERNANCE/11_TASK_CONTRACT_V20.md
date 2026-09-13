# TASK CONTRACT V20

每个任务必须声明：

task_id
mode
goal
input_refs
authority_scope
allowed_mutations
forbidden_mutations
required_outputs
quality_gates
failure_policy
commit_policy
context_budget
compiler_version
profile_version

没有明确 allowed_mutations 的任务，默认 **READ/PROPOSE ONLY**。
