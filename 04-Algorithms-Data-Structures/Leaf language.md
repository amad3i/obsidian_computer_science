---
title: "Leaf language"
tags: ["cs", "algorithms-data-structures", "advanced"]
domain: Algorithms & Data Structures
level: advanced
source: "https://en.wikipedia.org/wiki/Leaf_language"
wikipedia_categories: ["Computational complexity theory"]
related: ["[[Aanderaa–Karp–Rosenberg conjecture]]", "[[Advice (complexity)]]", "[[Analysis of algorithms]]", "[[Approximation algorithm]]", "[[Asymptotic computational complexity]]", "[[Averaging argument]]", "[[Bernstein–Vazirani algorithm]]", "[[Best, worst and average case]]", "[[Boolean circuit]]", "[[Certificate (complexity)]]"]
---

# Leaf language

Leaf language is a method in computational complexity theory for characterizing a complexity class by formalizing what it means for a machine to "accept" an input.
Complexity classes are typically defined in terms of a polynomial-time nondeterministic Turing machine (NTM). These machines possess multiple computational paths, and the outcomes of these paths determine whether an input is accepted or rejected.  Traditionally, an NTM accepts an input if at least one path accepts it, and rejects it only if all paths reject it. In contrast, a co-Nondeterministic Turing Machine (co-NTM) accepts an input only if all paths accept it, and rejects it if any path rejects it. Moreover, more complex notions of acceptance can also be defined.
To formalize the characterization of a complexity class, one can examine the formal language associated with each acceptance condition. This involves assuming an ordered tree, and reading the accepted/rejected strings from the leaves of the computation tree. NTMs will accept if the leaf string is in the language 0*1{0, 1}*, and will reject if the leaf string is in the language 0*.

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

- Wikipedia: https://en.wikipedia.org/wiki/Leaf_language