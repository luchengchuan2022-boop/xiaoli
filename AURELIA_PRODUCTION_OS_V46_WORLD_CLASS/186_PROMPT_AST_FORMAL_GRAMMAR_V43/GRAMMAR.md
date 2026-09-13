# Compact Grammar

PRODUCTION_PROMPT ::= HEADER CONTEXT INTENT PERFORMANCE CAMERA VISUAL MOTION AUDIO NEGATIVE CONTINUITY FOOTER
INTENT ::= purpose + emotional_trajectory + audience_effect
PERFORMANCE ::= action + micro_expression + timing + eye_line + body_state
CAMERA ::= shot_size + composition + position + movement + focus + duration
VISUAL ::= environment + art_direction + lighting + color + vfx
MOTION ::= start_state + motion + end_state + temporal_constraints
CONTINUITY ::= identity_locks + geometry_locks + state_locks + carry_in + carry_out

编译器必须拒绝缺失关键语义的节点，而不是用模板补齐。
