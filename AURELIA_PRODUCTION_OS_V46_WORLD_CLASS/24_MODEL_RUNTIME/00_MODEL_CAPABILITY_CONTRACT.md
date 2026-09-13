# MODEL CAPABILITY CONTRACT

Before compilation to a model adapter, declare:

`MODEL_ID / VERSION / CAPABILITIES / LIMITATIONS / INPUT_LIMITS / OUTPUT_LIMITS / REFERENCE_SUPPORT / CAMERA_SUPPORT / MOTION_SUPPORT / STYLE_SUPPORT`

If requested semantics exceed declared capability, emit CAPABILITY_GAP. Never hide the gap by writing a longer prompt.
