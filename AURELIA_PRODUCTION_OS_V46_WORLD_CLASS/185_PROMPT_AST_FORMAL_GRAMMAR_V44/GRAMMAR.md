# Prompt AST Grammar

`ProductionPrompt ::= Intent Stage Performance Staging Camera Light Environment Audio Keyframe Motion Constraints Continuity`

Every node carries semantic source references and transformation status: `PRESERVED | TRANSFORMED | OMITTED_WITH_REASON | INTRODUCED_AS_CINEMATIC_EXPRESSION`.

A prompt node cannot introduce a new plot fact, character fact, relationship state or world rule.
