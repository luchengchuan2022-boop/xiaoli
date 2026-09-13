# V23 Runtime API Shapes

Every runtime API should accept explicit IDs/revisions and return typed outcomes. Avoid APIs such as `saveText()` for authoritative mutation. Prefer semantic operations such as `proposePatch()`, `authorizePatch()`, `commitRevision()`, `replayTransaction()`, `buildContextPacket()`, `compileIR()`, `validatePackage()`.
