---
title: "Bellman equation"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Bellman_equation"
wikipedia_categories: ["Control theory", "Dynamic programming", "Equations"]
related: ["[[Recursive economics]]", "[[Dynamic programming]]", "[[4D-RCS Reference Model Architecture]]", "[[Ackermann's formula]]", "[[Active disturbance rejection control]]", "[[Adaptive control]]", "[[Advanced process control]]", "[[Affect control theory]]", "[[American Automatic Control Council]]", "[[Anticausal system]]"]
---

# Bellman equation

A Bellman equation, named after Richard E. Bellman,  is a technique in dynamic programming which breaks an optimization problem into a sequence of simpler subproblems, as Bellman's "principle of optimality" prescribes. It is a necessary condition for optimality. The "value" of a decision problem at a certain point in time is written in terms of the payoff from some initial choices and the "value" of the remaining decision problem that results from those initial choices. The equation applies to algebraic structures with a total ordering; for algebraic structures with a partial ordering, the generic Bellman's equation can be used.
The Bellman equation was first applied to engineering control theory and to other topics in applied mathematics, and subsequently became an important tool in economic theory; though the basic concepts of dynamic programming are prefigured in John von Neumann and Oskar Morgenstern's Theory of Games and Economic Behavior and Abraham Wald's sequential analysis. The term "Bellman equation" usually refers to the dynamic programming equation (DPE) associated with discrete-time optimization problems. In continuous-time optimization problems, the analogous equation is a partial differential equation called the Hamilton–Jacobi–Bellman equation.
In discrete time any multi-stage optimization problem can be solved by analyzing the appropriate Bellman equation. The appropriate Bellman equation can be found by introducing new state variables (state augmentation). However, the resulting augmented-state multi-stage optimization problem has a higher dimensional state space than the original multi-stage optimization problem - an issue that can potentially render the augmented problem intractable due to the "curse of dimensionality". Alternatively, it has been shown that if the cost function of the multi-stage optimization problem satisfies a "backward separable" structure, then the appropriate Bellman equation can be found without state augmentation.

## Related

- [[Recursive economics]]
- [[Dynamic programming]]
- [[4D-RCS Reference Model Architecture]]
- [[Ackermann's formula]]
- [[Active disturbance rejection control]]
- [[Adaptive control]]
- [[Advanced process control]]
- [[Affect control theory]]
- [[American Automatic Control Council]]
- [[Anticausal system]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Bellman_equation