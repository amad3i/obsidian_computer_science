---
title: "Isolation lemma"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Isolation_lemma"
wikipedia_categories: ["Combinatorics", "Lemmas", "Theorems in probability theory"]
related: ["[[Algorithmic Lovász local lemma]]", "[[Lovász local lemma]]", "[[Counting lemma]]", "[[Dickson's lemma]]", "[[Lindström–Gessel–Viennot lemma]]", "[[Littlewood–Offord problem]]", "[[Tucker's lemma]]", "[[Uniform convergence in probability]]", "[[3-dimensional matching]]", "[[Aanderaa–Karp–Rosenberg conjecture]]"]
---

# Isolation lemma

In theoretical computer science, the term isolation lemma (or isolating lemma) refers to randomized algorithms that reduce the number of solutions to a problem to one, should a solution exist.
This is achieved by constructing random constraints such that, with non-negligible probability, exactly one solution satisfies these additional constraints if the solution space is not empty.
Isolation lemmas have important applications in computer science, such as the Valiant–Vazirani theorem and Toda's theorem in computational complexity theory.
The first isolation lemma was introduced by Valiant & Vazirani (1986), albeit not under that name.
Their isolation lemma chooses a random number of random hyperplanes, and has the property that, with non-negligible probability, the intersection of any fixed non-empty solution space with the chosen hyperplanes contains exactly one element. This suffices to show the Valiant–Vazirani theorem:
there exists a randomized polynomial-time reduction from the satisfiability problem for Boolean formulas to the problem of detecting whether a Boolean formula has a unique solution.
Mulmuley, Vazirani & Vazirani (1987) introduced an isolation lemma of a slightly different kind:
Here every coordinate of the solution space gets assigned a random weight in a certain range of integers, and the property is that, with non-negligible probability, there is exactly one element in the solution space that has minimum weight. This can be used to obtain a randomized parallel algorithm for the maximum matching problem.
Stronger isolation lemmas have been introduced in the literature to fit different needs in various settings.
For example, the isolation lemma of Chari, Rohatgi & Srinivasan (1993) has similar guarantees as that of Mulmuley et al., but it uses fewer random bits.
In the context of the exponential time hypothesis, Calabro et al. (2008) prove an isolation lemma for k-CNF formulas.
Noam Ta-Shma gives an isolation lemma with slightly stronger parameters, and gives non-trivial results even when the size of the weight domain is smaller than the number of variables.

## Related

- [[Algorithmic Lovász local lemma]]
- [[Lovász local lemma]]
- [[Counting lemma]]
- [[Dickson's lemma]]
- [[Lindström–Gessel–Viennot lemma]]
- [[Littlewood–Offord problem]]
- [[Tucker's lemma]]
- [[Uniform convergence in probability]]
- [[3-dimensional matching]]
- [[Aanderaa–Karp–Rosenberg conjecture]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Isolation_lemma