---
title: "Computing the permanent"
tags: ["cs", "foundations-math", "advanced"]
domain: Foundations & Math
level: advanced
source: "https://en.wikipedia.org/wiki/Computing_the_permanent"
wikipedia_categories: ["Computational complexity theory", "Computational problems", "Linear algebra", "Matrix theory", "Permutations"]
related: ["[[Immanant]]", "[[Permanent (mathematics)]]", "[[Adjugate matrix]]", "[[Amitsur–Levitzki theorem]]", "[[Annihilating polynomial]]", "[[Bendixson's inequality]]", "[[Change of basis]]", "[[Computational complexity of matrix multiplication]]", "[[Determinant]]", "[[Eigenoperator]]"]
---

# Computing the permanent

In linear algebra, the computation of the permanent of a matrix is a problem that is thought to be more difficult than the computation of the determinant of a matrix despite the apparent similarity of the definitions.
The permanent is defined similarly to the determinant, as a sum of products of sets of matrix entries that lie in distinct rows and columns. However, where the determinant weights each of these products with a ±1 sign based on the parity of the set, the permanent weights them all with a +1 sign.
While the determinant can be computed in polynomial time by Gaussian elimination, it is generally believed that the permanent cannot be computed in polynomial time. In computational complexity theory, a theorem of Valiant states that computing permanents is #P-hard, and even #P-complete for matrices in which all entries are 0 or 1 Valiant (1979). This puts the computation of the permanent in a class of problems believed to be even more difficult to compute than NP. It is known that computing the permanent is impossible for logspace-uniform ACC0 circuits.(Allender & Gore 1994)
The development of both exact and approximate algorithms for computing the permanent of a matrix is an active area of research.

## Related

- [[Immanant]]
- [[Permanent (mathematics)]]
- [[Adjugate matrix]]
- [[Amitsur–Levitzki theorem]]
- [[Annihilating polynomial]]
- [[Bendixson's inequality]]
- [[Change of basis]]
- [[Computational complexity of matrix multiplication]]
- [[Determinant]]
- [[Eigenoperator]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Computing_the_permanent