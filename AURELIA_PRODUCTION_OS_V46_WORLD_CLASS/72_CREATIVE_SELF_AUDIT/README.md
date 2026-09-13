# V36 创作自审计与错误发现
目标：让 Production OS 不只生成内容，还能主动发现“哪里错了、为什么错、最早在哪一层错”。

原则：
- 发现问题 ≠ 修复问题
- 修复必须定位 earliest responsible layer
- 不得用 Prompt 美化掩盖语义错误
- 不得用新 Lore 修补旧因果
- 每个缺陷必须有 severity、evidence、lineage、impact、repair_scope、regression_scope
- 自审计结果不能直接成为 Canon；必须经过既有 Truth/Commit 边界

缺陷分类：
SEMANTIC / CANON / STATE / CAUSAL / AGENCY / PSYCHOLOGY / RELATIONSHIP / AUDIENCE / PACING / CINEMATIC / VISUAL_IDENTITY / CONTINUITY / ASSET / MODEL / PRODUCTION / RECOVERY

审计闭环：
OBSERVE → DETECT → CLASSIFY → TRACE → LOCATE EARLIEST RESPONSIBLE LAYER → IMPACT ANALYSIS → REPAIR PLAN → RECOMPILE → REGRESSION → VALIDATE → EVIDENCE
