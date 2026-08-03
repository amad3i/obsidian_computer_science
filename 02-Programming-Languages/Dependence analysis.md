---
title: "Dependence analysis"
tags: ["cs", "programming-languages", "advanced"]
domain: Programming & Languages
level: advanced
source: "https://en.wikipedia.org/wiki/Dependence_analysis"
wikipedia_categories: ["Static program analysis"]
related: ["[[Alias analysis]]", "[[Array-access analysis]]", "[[Call graph]]", "[[Code motion]]", "[[Escape analysis]]", "[[Extended static checking]]", "[[Hoare logic]]", "[[Infer Static Analyzer]]", "[[Live-variable analysis]]", "[[Perl--Critic]]"]
---

# Dependence analysis

In compiler theory, dependence analysis produces execution-order constraints between statements/instructions.  Broadly speaking, a statement S2 depends on S1 if S1 must be executed before S2.  Broadly, there are two classes of dependencies--control dependencies and data dependencies.
Dependence analysis determines whether it is safe to reorder or parallelize statements.

## Related

- [[Alias analysis]]
- [[Array-access analysis]]
- [[Call graph]]
- [[Code motion]]
- [[Escape analysis]]
- [[Extended static checking]]
- [[Hoare logic]]
- [[Infer Static Analyzer]]
- [[Live-variable analysis]]
- [[Perl--Critic]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Dependence_analysis