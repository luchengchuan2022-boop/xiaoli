# Unified Cinematic IR

The Unified Cinematic IR is the semantic bridge between story intent and model prompts.

Pipeline:
`Story/State → DramaticIntent → BeatIR → ShotIR → PerformanceIR → StagingIR → CameraIR → LightingIR → EnvironmentIR → AudioIR/VFXIR → AssetIR → ConstraintIR → PromptAST`.

No vendor wording belongs in the semantic IR.

The same IR must be renderable to multiple model adapters without changing protected meaning.
