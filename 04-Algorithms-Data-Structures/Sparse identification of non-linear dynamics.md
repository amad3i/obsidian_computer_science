---
title: "Sparse identification of non-linear dynamics"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Sparse_identification_of_non-linear_dynamics"
wikipedia_categories: ["Algorithms"]
related: ["[[Adaptive algorithm]]", "[[Algorism]]", "[[Algorithm]]", "[[Algorithm characterizations]]", "[[Algorithm engineering]]", "[[Algorithm IMED]]", "[[Algorithmic amplification]]", "[[Algorithmic logic]]", "[[Algorithmic management]]", "[[Algorithmic mechanism design]]"]
---

# Sparse identification of non-linear dynamics

Sparse identification of nonlinear dynamics (SINDy) is a data-driven algorithm for obtaining dynamical systems from data. Given a series of snapshots of a dynamical system and its corresponding time derivatives, SINDy performs a sparsity-promoting regression (such as LASSO and sparse Bayesian inference) on a library of nonlinear candidate functions of the snapshots against the derivatives to find the governing equations. This procedure relies on the assumption that most physical systems only have a few dominant terms which dictate the dynamics, given an appropriately selected coordinate system and quality training data. It has been applied to identify the dynamics of fluids, based on proper orthogonal decomposition, as well as other complex dynamical systems, such as biological networks.

## Related

- [[Adaptive algorithm]]
- [[Algorism]]
- [[Algorithm]]
- [[Algorithm characterizations]]
- [[Algorithm engineering]]
- [[Algorithm IMED]]
- [[Algorithmic amplification]]
- [[Algorithmic logic]]
- [[Algorithmic management]]
- [[Algorithmic mechanism design]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Sparse_identification_of_non-linear_dynamics