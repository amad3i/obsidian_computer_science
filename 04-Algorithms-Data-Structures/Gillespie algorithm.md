---
title: "Gillespie algorithm"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Gillespie_algorithm"
wikipedia_categories: ["Chemical kinetics", "Computational chemistry", "Monte Carlo methods", "Stochastic simulation"]
related: ["[[Tau-leaping]]", "[[Dynamic Monte Carlo method]]", "[[Monte Carlo method]]", "[[Multilevel Monte Carlo method]]", "[[Particle filter]]", "[[Reaction coordinate]]", "[[Stochastic process rare event sampling]]", "[[Transition path sampling]]", "[[Umbrella sampling]]", "[[1s Slater-type function]]"]
---

# Gillespie algorithm

In probability theory, the Gillespie algorithm (or the Doob–Gillespie algorithm or stochastic simulation algorithm, the SSA) generates a statistically correct trajectory (possible solution) of a stochastic equation system for which the reaction rates are known. It was created by Joseph L. Doob and others (circa 1945), presented by Daniel Gillespie in 1976, and popularized in 1977 in a paper where he uses it to simulate chemical or biochemical systems of reactions efficiently and accurately using limited computational power (see stochastic simulation). As computers have become faster, the algorithm has been used to simulate increasingly complex systems. The algorithm is particularly useful for simulating reactions within cells, where the number of reagents is low and keeping track of every single reaction is computationally feasible. Mathematically, it is a variant of a dynamic Monte Carlo method and similar to the kinetic Monte Carlo methods. It is used heavily in computational systems biology.

## Related

- [[Tau-leaping]]
- [[Dynamic Monte Carlo method]]
- [[Monte Carlo method]]
- [[Multilevel Monte Carlo method]]
- [[Particle filter]]
- [[Reaction coordinate]]
- [[Stochastic process rare event sampling]]
- [[Transition path sampling]]
- [[Umbrella sampling]]
- [[1s Slater-type function]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Gillespie_algorithm