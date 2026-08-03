---
title: "Differential evolution"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Differential_evolution"
wikipedia_categories: ["Evolutionary algorithms"]
related: ["[[Artificial development]]", "[[Cellular evolutionary algorithm]]", "[[Constructive cooperative coevolution]]", "[[Cultural algorithm]]", "[[Defining length]]", "[[Dispersive flies optimisation]]", "[[Effective fitness]]", "[[Evolutionary algorithm]]", "[[Evolutionary multimodal optimization]]", "[[Evolutionary programming]]"]
---

# Differential evolution

Differential evolution (DE) is an evolutionary algorithm to optimize a problem by iteratively trying to improve a candidate solution with regard to a given measure of quality. Such methods are commonly known as metaheuristics as they make few or no assumptions about the optimized problem and can search very large spaces of candidate solutions. However, metaheuristics such as DE do not guarantee an optimal solution is ever found.
DE is used for multidimensional real-valued functions but does not use the gradient of the problem being optimized, which means DE does not require the optimization problem to be differentiable, as is required by classic optimization methods such as gradient descent and quasi-newton methods. DE can therefore also be used on optimization problems that are not even continuous, are noisy, change over time, etc.
DE optimizes a problem by maintaining a population of candidate solutions and creating new candidate solutions by combining existing ones according to its simple formulae, and then keeping whichever candidate solution has the best score or fitness on the optimization problem at hand. In this way, the optimization problem is treated as a black box that merely provides a measure of quality given a candidate solution and the gradient is therefore not needed.

## Related

- [[Artificial development]]
- [[Cellular evolutionary algorithm]]
- [[Constructive cooperative coevolution]]
- [[Cultural algorithm]]
- [[Defining length]]
- [[Dispersive flies optimisation]]
- [[Effective fitness]]
- [[Evolutionary algorithm]]
- [[Evolutionary multimodal optimization]]
- [[Evolutionary programming]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Differential_evolution