# TASK PROMPT — REPAIR

MODE=REPAIR

输入：
已有正确成果 + Validation Failure + Evidence

规则：
1. 保留所有已通过部分。
2. 找到最早责任层。
3. 只修该层及受影响下游。
4. 重新验证。
5. 不重写无关内容。
6. 不推进 State，直到重新 Commit。

输出：
REPAIR PLAN
→ REPAIR DELTA
→ RECOMPILED ARTIFACT
→ VALIDATION
→ WRITEBACK PROPOSAL
