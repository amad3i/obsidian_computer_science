---
title: "Alias analysis"
tags: ["cs", "programming-languages", "advanced"]
domain: Programming & Languages
level: advanced
source: "https://en.wikipedia.org/wiki/Alias_analysis"
wikipedia_categories: ["Static program analysis"]
related: ["[[Array-access analysis]]", "[[Call graph]]", "[[Code motion]]", "[[Dependence analysis]]", "[[Escape analysis]]", "[[Extended static checking]]", "[[Hoare logic]]", "[[Infer Static Analyzer]]", "[[Live-variable analysis]]", "[[Perl--Critic]]"]
---

# Alias analysis

Alias analysis is a technique in compiler theory, used to determine if a storage location may be accessed in more than one way. Two pointers are said to be aliased if they point to the same location.
Alias analysis techniques are usually classified by flow-sensitivity and context-sensitivity. They may determine may-alias or must-alias information. The term alias analysis is often used interchangeably with points-to analysis, a specific case.
Alias analysers intend to make and compute useful information for understanding aliasing in programs.

## Related

- [[Array-access analysis]]
- [[Call graph]]
- [[Code motion]]
- [[Dependence analysis]]
- [[Escape analysis]]
- [[Extended static checking]]
- [[Hoare logic]]
- [[Infer Static Analyzer]]
- [[Live-variable analysis]]
- [[Perl--Critic]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Alias_analysis