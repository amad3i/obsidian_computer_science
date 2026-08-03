---
title: "Fish School Search"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Fish_School_Search"
wikipedia_categories: ["Nature-inspired metaheuristics"]
related: ["[[Ant colony optimization algorithms]]", "[[Artificial bee colony algorithm]]", "[[Bat algorithm]]", "[[Bees algorithm]]", "[[Bio-inspired computing]]", "[[Biogeography-based optimization]]", "[[Cuckoo search]]", "[[Cultural algorithm]]", "[[Dispersive flies optimisation]]", "[[Dual-phase evolution]]"]
---

# Fish School Search

Fish School Search (FSS), proposed by Bastos Filho and Lima Neto in 2008 is, in its basic version, a unimodal optimization algorithm inspired by the collective behavior of fish schools. The mechanisms of feeding and coordinated movement were used as inspiration to create the search operators. The core idea is to make the fishes “swim” toward the positive gradient in order to “eat” and “gain weight”. Collectively, the heavier fishes have more influence on the search process as a whole, which makes the barycenter of the fish school move toward optima in the search space over successive iterations.
The FSS uses the following principles: 

Simple computations in all individuals (i.e. fish)
Various means of storing information (i.e. weights of fish and school barycenter)
Local computations (i.e. swimming is composed of distinct components)
Low communications between neighboring individuals (i.e. fish are to think local but also be socially aware)
Minimum centralized control (mainly for self-controlling of the school radius)
Some distinct diversity mechanisms (this to avoid undesirable flocking behavior)
Scalability (in terms of complexity of the optimization/search tasks)
Autonomy (i.e. ability to self-control functioning)

## Related

- [[Ant colony optimization algorithms]]
- [[Artificial bee colony algorithm]]
- [[Bat algorithm]]
- [[Bees algorithm]]
- [[Bio-inspired computing]]
- [[Biogeography-based optimization]]
- [[Cuckoo search]]
- [[Cultural algorithm]]
- [[Dispersive flies optimisation]]
- [[Dual-phase evolution]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Fish_School_Search