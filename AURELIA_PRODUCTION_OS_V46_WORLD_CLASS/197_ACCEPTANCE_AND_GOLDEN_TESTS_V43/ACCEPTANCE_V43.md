# V43 Acceptance Gates

## G01 Truth Authority
模型输出不能升级为 Canon。
## G02 Transition Proof
无 pre/post/invariant/proof 不得 commit。
## G03 Transaction Atomicity
半提交必须不可见。
## G04 Projection Replay
事件重放必须得到一致语义 projection。
## G05 Context Determinism
冻结输入下 context hash 可复现。
## G06 Prompt AST
Prompt 必须可追溯到 semantic source。
## G07 Semantic Preservation
模型能力不足不得篡改 protected semantics。
## G08 Cross-scale
Atom 不得静默破坏 Episode/Arc/Season/Series/IP invariant。
## G09 15s
exact_duration=15.00。
## G10 Proof-carrying package
无完整 proof bundle → BLOCKED。
## G11 Recovery
失败修复必须回到 earliest responsible layer。
## G12 Replay
可定位第一次 divergence。
## G13 Autonomous boundary
越权自动创作必须 STOP。
## G14 Longform health
重复、漂移、promise debt、future option collapse 必须可检测。
