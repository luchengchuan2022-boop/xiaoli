# Recovery Matrix

Semantic failure：回到 semantic owner。
Prompt compilation failure：修 compiler/AST。
Model capability failure：协商能力或换模型，不改 Canon。
Materialization failure：保持 DB truth，进入 pending recovery。
Projection failure：重建 projection，不修改事件历史。
