---
title: "Descriptive complexity theory"
tags: ["cs", "foundations-math", "advanced"]
domain: Foundations & Math
level: advanced
source: "https://en.wikipedia.org/wiki/Descriptive_complexity_theory"
wikipedia_categories: ["Computational complexity theory", "Descriptive complexity", "Finite model theory"]
related: ["[[Kolmogorov complexity]]", "[[Aanderaa–Karp–Rosenberg conjecture]]", "[[Advice (complexity)]]", "[[Analysis of algorithms]]", "[[Approximation algorithm]]", "[[Asymptotic computational complexity]]", "[[Averaging argument]]", "[[Bernstein–Vazirani algorithm]]", "[[Best, worst and average case]]", "[[BIT predicate]]"]
---

# Descriptive complexity theory

Descriptive complexity is a branch of computational complexity theory and of finite model theory that characterizes complexity classes by the type of logic needed to express the languages in them. For example, PH, the union of all complexity classes in the polynomial hierarchy, is precisely the class of languages expressible by statements of second-order logic. This connection between complexity and the logic of finite structures allows results to be transferred easily from one area to the other, facilitating new proof methods and providing additional evidence that the main complexity classes are somehow "natural" and not tied to the specific abstract machines used to define them. That is, it provides a machine-independent approach to complexity theory.
Specifically, each logical system produces a set of queries expressible in it. The queries – when restricted to finite structures – correspond to the computational problems of traditional complexity theory.
The first main result of descriptive complexity was Fagin's theorem, shown by Ronald Fagin in 1974. It established that NP is precisely the set of languages expressible by sentences of existential second-order logic; that is, second-order logic excluding universal quantification over relations, functions, and subsets. Many other classes were later characterized in such a manner.

## Related

- [[Kolmogorov complexity]]
- [[Aanderaa–Karp–Rosenberg conjecture]]
- [[Advice (complexity)]]
- [[Analysis of algorithms]]
- [[Approximation algorithm]]
- [[Asymptotic computational complexity]]
- [[Averaging argument]]
- [[Bernstein–Vazirani algorithm]]
- [[Best, worst and average case]]
- [[BIT predicate]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Descriptive_complexity_theory