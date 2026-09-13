V33 Model Failure & Recovery

Model output is observation/evidence, never Truth.

Failure classes: semantic_loss, canon_drift, identity_drift, spatial_error, temporal_error, acting_error, style_drift, omission, hallucination, capability_gap, continuity_break, unsafe_or_invalid_output.

Recovery: OBSERVE -> CLASSIFY -> TRACE -> EARLIEST_RESPONSIBLE_LAYER -> MINIMUM_REPAIR -> RECOMPILE -> REGRESSION -> VALIDATE.

Retrying the same prompt without changing the responsible layer is not a repair. Capability gaps must be explicit.
