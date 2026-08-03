---
title: "Weak NP-completeness"
tags: ["cs", "algorithms-data-structures", "advanced"]
domain: Algorithms & Data Structures
level: advanced
source: "https://en.wikipedia.org/wiki/Weak_NP-completeness"
wikipedia_categories: ["Complexity classes", "Computational complexity theory", "Weakly NP-complete problems"]
related: ["[[Complexity class]]", "[[Pseudo-polynomial time]]", "[[Pseudo-polynomial transformation]]", "[[Quasi-polynomial time]]", "[[Strong NP-completeness]]", "[[Aanderaa–Karp–Rosenberg conjecture]]", "[[Advice (complexity)]]", "[[Analysis of algorithms]]", "[[Approximation algorithm]]", "[[Asymptotic computational complexity]]"]
---

# Weak NP-completeness

In computational complexity, an NP-complete (or NP-hard) problem is weakly NP-complete (or weakly NP-hard) if there is an algorithm for the problem whose running time is polynomial in the dimension of the problem and the magnitudes of the data involved (provided these are given as integers), rather than the base-two logarithms of their magnitudes. Such algorithms have running times that are exponential functions of their input size and are therefore not considered polynomial
For example, the NP-hard knapsack problem can be solved by a dynamic programming algorithm requiring a number of steps polynomial in the size of the knapsack and the number of items (assuming that all data are scaled to be integers); however, the runtime of this algorithm is exponential time since the input sizes of the objects and knapsack are logarithmic in their magnitudes. However, as Garey and Johnson (1979) observed, “A pseudo-polynomial-time algorithm … will display 'exponential behavior' only when confronted with instances containing 'exponentially large' numbers, [which] might be rare for the application we are interested in. If so, this type of algorithm might serve our purposes almost as well as a polynomial time algorithm.” Another example for a weakly NP-complete problem is the subset sum problem.
The related term strongly NP-complete (or unary NP-complete) refers to those problems that remain NP-complete even if the data are encoded in unary, that is, if the data are "small" relative to the overall input size.

## Related

- [[Complexity class]]
- [[Pseudo-polynomial time]]
- [[Pseudo-polynomial transformation]]
- [[Quasi-polynomial time]]
- [[Strong NP-completeness]]
- [[Aanderaa–Karp–Rosenberg conjecture]]
- [[Advice (complexity)]]
- [[Analysis of algorithms]]
- [[Approximation algorithm]]
- [[Asymptotic computational complexity]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Weak_NP-completeness