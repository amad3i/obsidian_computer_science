---
title: "♯P-completeness of 01-permanent"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/♯P-completeness_of_01-permanent"
wikipedia_categories: ["Article proofs", "Combinatorics", "Computational problems"]
related: ["[[Josephus problem]]", "[[♯SAT]]", "[[3-dimensional matching]]", "[[Aanderaa–Karp–Rosenberg conjecture]]", "[[Addition principle]]", "[[AI-complete]]", "[[Algorithmic Lovász local lemma]]", "[[Algorithms and Combinatorics]]", "[[Alignments of random points]]", "[[All-pairs testing]]"]
---

# ♯P-completeness of 01-permanent

The #P-completeness of 01-permanent, sometimes known as Valiant's theorem, is a mathematical proof about the permanent of matrices, considered a seminal result in computational complexity theory. In 1979, Leslie Valiant proved that the computational problem of computing the permanent of a matrix is #P-hard, even if the matrix is restricted to have entries that are all 0 or 1. In this restricted case, computing the permanent is even #P-complete, because it corresponds to the #P problem of counting the number of permutation matrices one can get by changing ones into zeroes.
Valiant's 1979 paper also introduced   #P as a complexity class.
Valiant's definition of completeness, and his proof of completeness of 01-permanent, both used polynomial-time Turing reductions. In this kind of reduction, a single hard instance of some other problem in #P is reduced to computing the permanent of a sequence of multiple graphs, each of which could potentially depend on the results of previous permanent computations. A later simplification by Ben-Dor & Halevi (1993) showed that it is possible to use a weaker notion of reduction, a polynomial-time counting reduction, that translates the other problem into a single instance of the permanent problem.

## Related

- [[Josephus problem]]
- [[♯SAT]]
- [[3-dimensional matching]]
- [[Aanderaa–Karp–Rosenberg conjecture]]
- [[Addition principle]]
- [[AI-complete]]
- [[Algorithmic Lovász local lemma]]
- [[Algorithms and Combinatorics]]
- [[Alignments of random points]]
- [[All-pairs testing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/♯P-completeness_of_01-permanent