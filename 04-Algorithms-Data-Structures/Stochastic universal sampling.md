---
title: "Stochastic universal sampling"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Stochastic_universal_sampling"
wikipedia_categories: ["Selection (evolutionary algorithm)"]
related: ["[[Fitness proportionate selection]]", "[[Reward-based selection]]", "[[Tournament selection]]", "[[Truncation selection]]"]
---

# Stochastic universal sampling

Stochastic universal sampling (SUS) is a selection technique used in evolutionary algorithms for selecting potentially useful solutions for recombination. It was introduced by James Baker.
SUS is a development of fitness proportionate selection (FPS) which exhibits no bias and minimal spread. Where FPS chooses several solutions from the population by repeated random sampling, SUS uses a single random value to sample all of the solutions by choosing them at evenly spaced intervals. This gives weaker members of the population (according to their fitness) a chance to be chosen. 
FPS can have bad performance when a member of the population has a really large fitness in comparison with other members. Using a comb-like ruler, SUS starts from a small random number, and chooses the next candidates from the rest of population remaining, not allowing the fittest members to saturate the candidate space.

## Related

- [[Fitness proportionate selection]]
- [[Reward-based selection]]
- [[Tournament selection]]
- [[Truncation selection]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Stochastic_universal_sampling