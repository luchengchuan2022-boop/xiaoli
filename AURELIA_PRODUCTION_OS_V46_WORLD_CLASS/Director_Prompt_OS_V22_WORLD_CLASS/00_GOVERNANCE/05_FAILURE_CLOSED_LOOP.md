# FAILURE CLOSED LOOP

任何失败必须回答：
1. 失败发生在哪一层？
2. 哪些成果仍然有效？
3. 哪些成果缺失？
4. 是否存在语义风险？
5. 是否可局部修复？
6. 是否影响 Canon？
7. 是否影响 State？
8. 是否需要人工授权？

输出：
ACCEPT / REPAIRABLE / REJECT / CONFLICT_REVIEW

REPAIR_PROMPT 必须只请求缺失部分，禁止无意义全量重生成。
