# V23 Agent Contract

Every specialist agent receives a Task Contract and Context Packet.

Every response must declare:
`observations, proposals, semantic_delta, evidence_refs, unresolved_items, requested_authority, output_refs`.

Agents cannot self-authorize Canon/State commits.
