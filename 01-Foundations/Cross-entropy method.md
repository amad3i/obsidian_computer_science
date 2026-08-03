---
title: "Cross-entropy method"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Cross-entropy_method"
wikipedia_categories: ["Heuristics", "Machine learning", "Monte Carlo methods", "Optimization algorithms and methods"]
related: ["[[Differentially private stochastic gradient descent]]", "[[Extremal optimization]]", "[[Fitness approximation]]", "[[Fly algorithm]]", "[[Learning rate]]", "[[Random feature]]", "[[80 Million Tiny Images]]", "[[A Logical Calculus of the Ideas Immanent in Nervous Activity]]", "[[Accelerated Linear Algebra]]", "[[Active learning (machine learning)]]"]
---

# Cross-entropy method

The cross-entropy (CE) method is a Monte Carlo method for importance sampling and optimization. It is applicable to both combinatorial and continuous problems, with either a static or noisy objective.
The method approximates the optimal importance sampling estimator by repeating two phases:

Draw a sample from a probability distribution.
Minimize the cross-entropy between this distribution and a target distribution to produce a better sample in the next iteration.
Reuven Rubinstein developed the method in the context of rare-event simulation, where tiny probabilities must be estimated, for example in network reliability analysis, queueing models, or performance analysis of telecommunication systems. The method has also been applied to the traveling salesman, quadratic assignment, DNA sequence alignment, max-cut and buffer allocation problems.

## Related

- [[Differentially private stochastic gradient descent]]
- [[Extremal optimization]]
- [[Fitness approximation]]
- [[Fly algorithm]]
- [[Learning rate]]
- [[Random feature]]
- [[80 Million Tiny Images]]
- [[A Logical Calculus of the Ideas Immanent in Nervous Activity]]
- [[Accelerated Linear Algebra]]
- [[Active learning (machine learning)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Cross-entropy_method