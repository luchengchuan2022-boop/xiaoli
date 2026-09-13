# V44 15秒电影Production Atom

固定15.00秒。它必须属于更大的连续电影。

输入：START_STATE + AUTHORIZED_INTENT + CONTEXT_PACKET。
输出：END_STATE + COMPLETE_PRODUCTION_PACKAGE + PROOF_BUNDLE。

链路：语义目的 -> 情绪轨迹 -> 注意力设计 -> Beat -> 表演 -> 调度 -> 分镜 -> 景别/构图/机位/运镜 -> 光线/美术/VFX/声音 -> 关键帧 -> 中文图片提示词 -> 中文视频提示词 -> 连续性锁 -> QA -> 证明。

必须满足：`END_STATE = START_STATE + AUTHORIZED_DELTA`；任何新增事实必须有授权；任何镜头都必须有戏剧功能。
