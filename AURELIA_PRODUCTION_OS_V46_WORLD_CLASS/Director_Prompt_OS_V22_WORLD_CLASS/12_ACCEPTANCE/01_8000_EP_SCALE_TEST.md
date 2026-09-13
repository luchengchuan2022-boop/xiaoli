# 8000 EP SCALE TEST

系统必须理论上支持：
- 8000+ EP
- 数万至数十万 Shot
- 大量资产版本
- 多季、多章、多线并行
- 长期 unresolved threads
- Retcon with authorization
- replay/recovery
- partial repair
- deterministic writeback

核心测试：
连续生产不能因为上下文变长而依赖“把所有历史塞进一个 Prompt”。
