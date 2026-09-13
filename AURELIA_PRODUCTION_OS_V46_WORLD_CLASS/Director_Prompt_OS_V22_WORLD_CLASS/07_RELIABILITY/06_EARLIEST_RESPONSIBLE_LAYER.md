# EARLIEST RESPONSIBLE LAYER

出现问题时，不允许直接修改最终 Prompt。

沿责任链向上检查：
SOURCE
→ CANON
→ STATE
→ KNOWLEDGE
→ STORY
→ INTENT
→ DRAMATIC
→ PERFORMANCE
→ STAGING
→ CINEMATIC
→ WORLD
→ ASSET
→ CONSTRAINT
→ IR
→ PROMPT AST
→ MODEL ADAPTER
→ MODEL OUTPUT

原则：
在“第一个产生错误的层”修复，而不是在最下游遮盖症状。

例：
角色年龄错误若来自 Canon，不得靠 Seedance Prompt 修正。
镜头执行错误若来自 ShotIR，不得只加一句“电影感”。
模型不支持某动作，不得修改剧情；应进入 Adapter/Alternative。
