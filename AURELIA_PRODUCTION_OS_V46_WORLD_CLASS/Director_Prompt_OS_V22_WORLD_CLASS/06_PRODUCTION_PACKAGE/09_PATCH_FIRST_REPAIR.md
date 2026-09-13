# Patch-First Repair

Repair the earliest responsible layer.

Examples:
- wrong plot → story layer;
- wrong character knowledge → knowledge layer;
- correct intent but weak framing → cinematic layer;
- correct prompt but model ignored constraint → adapter/capability layer;
- correct model output but writeback duplicated → reliability layer.

Do not regenerate the entire pipeline for a local defect unless dependency analysis proves it necessary.
