# TYPE SYSTEM

V26 requires typed domains rather than free-form strings wherever semantics matter.

Core types:
ProjectId, ObjectId, RevisionId, Version, AuthorityRef, StateRef, EventId,
TaskId, CommandId, TransactionId, PackageId, ArtifactId, EvidenceId,
ValidationId, AgentId, ProfileId, SemanticHash, ContentHash, Timestamp.

Enums are closed unless explicitly marked EXTENSIBLE.
Unknown enum values must not be silently mapped to a known value.
