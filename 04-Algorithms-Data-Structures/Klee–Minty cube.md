---
title: "Klee–Minty cube"
tags: ["cs", "algorithms-data-structures", "advanced"]
domain: Algorithms & Data Structures
level: advanced
source: "https://en.wikipedia.org/wiki/Klee–Minty_cube"
wikipedia_categories: ["Analysis of algorithms", "Computational complexity theory", "Convex geometry", "Cubes", "Linear programming"]
related: ["[[Analysis of algorithms]]", "[[Best, worst and average case]]", "[[Combinatorial search]]", "[[Computational complexity]]", "[[Half-exponential function]]", "[[Pseudo-polynomial time]]", "[[Quasi-polynomial time]]", "[[Smoothed analysis]]", "[[Time complexity]]", "[[Aanderaa–Karp–Rosenberg conjecture]]"]
---

# Klee–Minty cube

The Klee–Minty cube or Klee–Minty polytope (named after Victor Klee and George J. Minty) is a unit hypercube of variable dimension whose corners have been perturbed. Klee and Minty demonstrated that George Dantzig's simplex algorithm has poor worst-case performance when initialized at one corner of their "squashed cube". On the three-dimensional version, the simplex algorithm and the criss-cross algorithm visit all 8 corners in the worst case. 
In particular, many optimization algorithms for linear optimization exhibit poor performance when applied to the Klee–Minty cube. In 1973 Klee and Minty showed that Dantzig's simplex algorithm was not a polynomial-time algorithm when applied to their cube. Later, modifications of the Klee–Minty cube have shown poor behavior both for other basis-exchange pivoting algorithms and also for interior-point algorithms.

## Related

- [[Analysis of algorithms]]
- [[Best, worst and average case]]
- [[Combinatorial search]]
- [[Computational complexity]]
- [[Half-exponential function]]
- [[Pseudo-polynomial time]]
- [[Quasi-polynomial time]]
- [[Smoothed analysis]]
- [[Time complexity]]
- [[Aanderaa–Karp–Rosenberg conjecture]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Klee–Minty_cube