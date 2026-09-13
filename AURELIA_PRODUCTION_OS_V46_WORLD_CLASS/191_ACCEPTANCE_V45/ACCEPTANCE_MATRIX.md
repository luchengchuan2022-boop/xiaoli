# V45 Acceptance Matrix

PASS requires all critical tests below:

1. TYPE_SAFETY_PASS — invalid semantic edges rejected.
2. AUTHORITY_PASS — lower authority cannot overwrite higher authority.
3. LIFECYCLE_PASS — illegal transitions rejected.
4. EVENT_REPLAY_PASS — committed state reconstructs from immutable events.
5. PROJECTION_CONSISTENCY_PASS — projections reconcile with canonical history.
6. CONTEXT_CLOSURE_PASS — required dependencies never silently omitted.
7. KNOWLEDGE_FIREWALL_PASS — character/audience knowledge does not leak.
8. DECISION_SEPARATION_PASS — generator cannot self-approve.
9. PROOF_CLOSURE_PASS — critical obligations have evidence.
10. COMPILER_CONFORMANCE_PASS — protected semantics survive all compilation layers.
11. PROMPT_NONAUTHORITATIVE_PASS — prompt cannot create canon.
12. FIFTEEN_SECOND_PASS — exact 15.00s and valid end-state delta.
13. CONTINUITY_PASS — identity, geography, time, costume, props, axis, lighting and state remain legal.
14. LONGFORM_PASS — no violation of higher-scale invariants or future option space.
15. REPAIR_EARLIEST_LAYER_PASS — downstream repair cannot hide upstream semantic defects.
16. IDEMPOTENCY_PASS — repeated same transaction cannot duplicate truth.
17. CONFLICT_QUARANTINE_PASS — contradictions never silently merge.
18. MANIFEST_PROOF_PASS — package is independently auditable.
19. DETERMINISTIC_SEMANTICS_PASS — same frozen input yields equivalent semantic output.
20. ADVERSARIAL_STUDIO_PASS — pretty-but-empty, unfair-reveal, relationship-jump, lore-injection and model-as-canon scenarios fail closed.
