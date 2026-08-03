---
title: "Live-variable analysis"
tags: ["cs", "foundations-math", "advanced"]
domain: Foundations & Math
level: advanced
source: "https://en.wikipedia.org/wiki/Live-variable_analysis"
wikipedia_categories: ["Compiler optimizations", "Data-flow analysis", "Static program analysis"]
related: ["[[Code motion]]", "[[Value range analysis]]", "[[Alias analysis]]", "[[Array-access analysis]]", "[[Automatic parallelization]]", "[[Automatic vectorization]]", "[[Call graph]]", "[[Compile-time function execution]]", "[[Dependence analysis]]", "[[Escape analysis]]"]
---

# Live-variable analysis

In compilers, live variable analysis (or simply liveness analysis) is a classic data-flow analysis to calculate the variables that are live at each point in the program. A variable is live at some point if it holds a value that may be needed in the future, or equivalently if its value may be read before the next time the variable is written to.

## Related

- [[Code motion]]
- [[Value range analysis]]
- [[Alias analysis]]
- [[Array-access analysis]]
- [[Automatic parallelization]]
- [[Automatic vectorization]]
- [[Call graph]]
- [[Compile-time function execution]]
- [[Dependence analysis]]
- [[Escape analysis]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Live-variable_analysis