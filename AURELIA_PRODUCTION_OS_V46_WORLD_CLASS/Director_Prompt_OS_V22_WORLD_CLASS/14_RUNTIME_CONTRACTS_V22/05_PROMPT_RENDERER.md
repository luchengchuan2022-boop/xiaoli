# V22 Prompt Renderer Contract

Prompt rendering is deterministic with respect to the same:
- Production IR revision;
- profile revision;
- adapter revision;
- rendering policy;
- capability declaration.

The renderer may reorder wording for model effectiveness but cannot introduce protected story facts, delete protected constraints, or alter semantic intent without a declared delta.

Output must include both:
1. machine-readable PromptAST;
2. human/model-facing rendered prompt.
