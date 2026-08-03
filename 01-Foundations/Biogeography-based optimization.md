---
title: "Biogeography-based optimization"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Biogeography-based_optimization"
wikipedia_categories: ["Nature-inspired metaheuristics"]
related: ["[[Ant colony optimization algorithms]]", "[[Artificial bee colony algorithm]]", "[[Bat algorithm]]", "[[Bees algorithm]]", "[[Bio-inspired computing]]", "[[Cuckoo search]]", "[[Cultural algorithm]]", "[[Dispersive flies optimisation]]", "[[Dual-phase evolution]]", "[[Firefly algorithm]]"]
---

# Biogeography-based optimization

Biogeography-based optimization (BBO) is an evolutionary algorithm (EA) that optimizes a function by stochastically and iteratively improving candidate solutions with regard to a given measure of quality, or fitness function. BBO belongs to the class of metaheuristics since it includes many variations, and since it does not make any assumptions about the problem and can therefore be applied to a wide class of problems.
BBO is typically used to optimize multidimensional real-valued functions, but it does not use the gradient of the function, which means that it does not require the function to be differentiable as required by classic optimization methods such as gradient descent and quasi-newton methods. BBO can therefore be used on discontinuous functions.
BBO optimizes a problem by maintaining a population of candidate solutions, and creating new candidate solutions by combining existing ones according to a simple formula. In this way the objective function is treated as a black box that merely provides a measure of quality given a candidate solution, and the function's gradient is not needed.
Like many EAs, BBO was motivated by a natural process; in particular, BBO was motivated by biogeography, which is the study of the distribution of biological species through time and space. BBO was originally introduced by Dan Simon in 2008.

## Related

- [[Ant colony optimization algorithms]]
- [[Artificial bee colony algorithm]]
- [[Bat algorithm]]
- [[Bees algorithm]]
- [[Bio-inspired computing]]
- [[Cuckoo search]]
- [[Cultural algorithm]]
- [[Dispersive flies optimisation]]
- [[Dual-phase evolution]]
- [[Firefly algorithm]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Biogeography-based_optimization