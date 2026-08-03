---
title: "Dead-end elimination"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Dead-end_elimination"
wikipedia_categories: ["Mathematical optimization", "Protein methods"]
related: ["[[Algorithmic problems on convex sets]]", "[[Analysis of Boolean functions]]", "[[Backtracking line search]]", "[[Barzilai–Borwein method]]", "[[Basis pursuit]]", "[[Basis pursuit denoising]]", "[[Bauer maximum principle]]", "[[Bayesian efficiency]]", "[[Bilinear program]]", "[[Binary constraint]]"]
---

# Dead-end elimination

The dead-end elimination algorithm (DEE) is a method for minimizing a function over a discrete set of independent variables.  The basic idea is to identify "dead ends", i.e., combinations of variables that are not necessary to define a global minimum because there is always a way of replacing such a combination with a better or equivalent one. Then we can refrain from further searching such combinations. Hence, dead-end elimination is the mirror image of dynamic programming, in which "good" combinations are identified and explored further.
Although the method itself is general, it has been developed and applied mainly to the problems of predicting and designing the structures of proteins (and in this wise was cited in the Scientific Background to the 2024 Nobel Prize in Chemistry).  It is closely related to the notion of dominance in optimization also known as substitutability in a Constraint Satisfaction Problem. The original description and proof of the dead-end elimination theorem can be found in .

## Related

- [[Algorithmic problems on convex sets]]
- [[Analysis of Boolean functions]]
- [[Backtracking line search]]
- [[Barzilai–Borwein method]]
- [[Basis pursuit]]
- [[Basis pursuit denoising]]
- [[Bauer maximum principle]]
- [[Bayesian efficiency]]
- [[Bilinear program]]
- [[Binary constraint]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Dead-end_elimination