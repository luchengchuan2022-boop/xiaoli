# Production Compiler V31

编译链：
SOURCE → SEMANTIC OBJECT → NARRATIVE IR → DRAMA IR → CHARACTER/RELATIONSHIP IR → CINEMATIC IR → SHOT AST → KEYFRAME AST → VIDEO AST → MODEL ADAPTER → PROMPT → PACKAGE

每次转换必须保留 provenance，并声明：preserved / transformed / omitted / newly introduced。

## 15s Delivery Atom
START_STATE → PURPOSE → BEATS → EMOTION → ATTENTION → PERFORMANCE → STAGING → SHOTS → KEYFRAMES → IMAGE PROMPTS → VIDEO PROMPTS → AUDIO → NEGATIVE CONSTRAINTS → CONTINUITY LOCKS → END_STATE

硬规则：END_STATE = START_STATE + AUTHORIZED_DELTA。

Vendor-specific wording is an adapter concern, never the semantic source of truth。
