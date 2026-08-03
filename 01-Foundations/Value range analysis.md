---
title: "Value range analysis"
tags: ["cs", "foundations-math", "advanced"]
domain: Foundations & Math
level: advanced
source: "https://en.wikipedia.org/wiki/Value_range_analysis"
wikipedia_categories: ["Compiler optimizations", "Static program analysis"]
related: ["[[Code motion]]", "[[Live-variable analysis]]", "[[Alias analysis]]", "[[Array-access analysis]]", "[[Automatic parallelization]]", "[[Automatic vectorization]]", "[[Call graph]]", "[[Compile-time function execution]]", "[[Dependence analysis]]", "[[Escape analysis]]"]
---

# Value range analysis

In computing, in particular compiler construction, value range analysis is a type of data flow analysis that tracks the range (interval) of values that a numeric variable can take on at each point of a program's execution.
The resulting information can be used in optimizations such as redundancy elimination, dead code elimination, instruction selection, etc., but can also be used to improve the safety of programs, e.g. in the detection of buffer overruns. Techniques for value range analysis typically use symbolic analysis extensively.
Value range analysis is often implemented in the Intel C++ Compiler and is implemented in GCC.

## Related

- [[Code motion]]
- [[Live-variable analysis]]
- [[Alias analysis]]
- [[Array-access analysis]]
- [[Automatic parallelization]]
- [[Automatic vectorization]]
- [[Call graph]]
- [[Compile-time function execution]]
- [[Dependence analysis]]
- [[Escape analysis]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Value_range_analysis