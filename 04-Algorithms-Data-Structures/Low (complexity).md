---
title: "Low (complexity)"
tags: ["cs", "algorithms-data-structures", "advanced"]
domain: Algorithms & Data Structures
level: advanced
source: "https://en.wikipedia.org/wiki/Low_(complexity)"
wikipedia_categories: ["Computational complexity theory"]
related: ["[[Aanderaa–Karp–Rosenberg conjecture]]", "[[Advice (complexity)]]", "[[Analysis of algorithms]]", "[[Approximation algorithm]]", "[[Asymptotic computational complexity]]", "[[Averaging argument]]", "[[Bernstein–Vazirani algorithm]]", "[[Best, worst and average case]]", "[[Boolean circuit]]", "[[Certificate (complexity)]]"]
---

# Low (complexity)

In computational complexity theory, a language B (or a complexity class B) is said to be low for a complexity class A  (with some reasonable relativized version of A) if AB = A; that is, A with an oracle for B is equal to A. 
Such a statement implies that an abstract machine that solves problems in A achieves no additional power if it is given the ability to solve problems in B at unit cost. In particular, this means that if B is low for A then B is contained in A. Informally, lowness means that problems in B are not only solvable by machines that can solve problems in A, but are “easy to solve”. An A machine can simulate many oracle queries to B without exceeding its resource bounds.
Results and relationships that establish one class as low for another are often called lowness results. The set of languages low for a complexity class A is denoted Low(A).

## Related

- [[Aanderaa–Karp–Rosenberg conjecture]]
- [[Advice (complexity)]]
- [[Analysis of algorithms]]
- [[Approximation algorithm]]
- [[Asymptotic computational complexity]]
- [[Averaging argument]]
- [[Bernstein–Vazirani algorithm]]
- [[Best, worst and average case]]
- [[Boolean circuit]]
- [[Certificate (complexity)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Low_(complexity)