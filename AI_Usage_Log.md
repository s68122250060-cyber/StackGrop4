# Generative AI Usage Log — Group 04

| Task | AI assistance | Verification | Student revision |
|---|---|---|---|
| Tokenization / multi-digit numbers | Suggested regex `split("\s+")` | Tested `(3+4)*2`; regex alone did not separate adjacent numbers/operators reliably | Reimplemented character-by-character tokenizer with `StringBuilder` |
| Big-O analysis | Initially suggested O(n²) because of nested-looking loops | Checked amortized push/pop behavior and traced the stacks | Corrected analysis to O(n) |
| Test cases | Suggested general cases | Compared against the assignment's mandatory 8 cases | Added all required boundary/error cases |
| Performance experiment / graph | Helped draft `ExperimentRunner` and `ExpressionGenerator` | Compiled and ran; compared operation counts with the original algorithm logic | Kept Algorithm A/B logic unchanged; used helper tools only for measurement |

## Reflection
AI was useful for brainstorming and checking structure, but its output was treated as a draft. The group verified the code, test cases, complexity analysis, and experimental results before using them. Every member must be able to explain the source code.
