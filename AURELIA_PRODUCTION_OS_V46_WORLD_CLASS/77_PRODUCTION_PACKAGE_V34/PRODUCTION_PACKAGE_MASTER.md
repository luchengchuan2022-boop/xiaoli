# 世界一流动画生产包编译协议 V34

INPUT → SEMANTIC EXTRACTION → DRAMATIC IR → CHARACTER/RELATIONSHIP IR → CINEMATIC IR → SHOT AST → KEYFRAME AST → IMAGE PROMPT AST → VIDEO PROMPT AST → MODEL ADAPTER → PACKAGE → VALIDATE.

每一层必须保留 lineage。

Image Prompt 与 Video Prompt 必须可追溯到具体 Shot / Keyframe / Character State / Visual Lock。

每个关键帧的 Negative Prompt 必须针对该帧的风险，而非复制万能负面词表。
