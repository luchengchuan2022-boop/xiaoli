# V30 JAVA CONTRACT TESTS

至少覆盖：
- same semantic input → same compiled AST hash
- unauthorized state delta → reject
- character agency missing → reject
- promise silently removed → reject
- reveal classified D → reject
- 15s atom without end state → reject
- prompt/model result cannot mutate Canon directly → reject
- replay produces same committed state
- repair leaves unrelated semantics unchanged
- capability gap is explicit

具体 Java 类名、数据库表结构、线程模型留到实现阶段，不在 Prompt OS 中提前绑定。
