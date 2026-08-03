---
title: "Constructive cooperative coevolution"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Constructive_cooperative_coevolution"
wikipedia_categories: ["Evolutionary algorithms", "Evolutionary computation"]
related: ["[[Fly algorithm]]", "[[Gene expression programming]]", "[[Artificial development]]", "[[Cellular evolutionary algorithm]]", "[[Computer-automated design]]", "[[Cultural algorithm]]", "[[Defining length]]", "[[Differential evolution]]", "[[Dispersive flies optimisation]]", "[[Effective fitness]]"]
---

# Constructive cooperative coevolution

The constructive cooperative coevolutionary algorithm (also called C3) is a global optimisation algorithm in artificial intelligence based on the multi-start architecture of the greedy randomized adaptive search procedure (GRASP). It incorporates the existing cooperative coevolutionary algorithm (CC). The considered problem is decomposed into subproblems. These subproblems are optimised separately while exchanging information in order to solve the complete problem. An optimisation algorithm, usually but not necessarily an evolutionary algorithm, is embedded in C3 for optimising those subproblems. The nature of the embedded optimisation algorithm determines whether C3's behaviour is deterministic or stochastic.
The C3 optimisation algorithm was originally designed for simulation-based optimisation but it can be used for global optimisation problems in general. Its strength over other optimisation algorithms, specifically cooperative coevolution, is that it is better able to handle non-separable optimisation problems.
An improved version was proposed later, called the Improved Constructive Cooperative Coevolutionary Differential Evolution (C3iDE), which removes several limitations with the previous version. A novel element of C3iDE is the advanced initialisation of the subpopulations. C3iDE initially optimises the subpopulations in a partially co-adaptive fashion. During the initial optimisation of a subpopulation, only a subset of the other subcomponents is considered for the co-adaptation. This subset increases stepwise until all subcomponents are considered. This makes C3iDE very effective on large-scale global optimisation problems (up to 1000 dimensions) compared to cooperative coevolutionary algorithm (CC) and Differential evolution.
The improved algorithm has then been adapted for multi-objective optimization.

## Related

- [[Fly algorithm]]
- [[Gene expression programming]]
- [[Artificial development]]
- [[Cellular evolutionary algorithm]]
- [[Computer-automated design]]
- [[Cultural algorithm]]
- [[Defining length]]
- [[Differential evolution]]
- [[Dispersive flies optimisation]]
- [[Effective fitness]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Constructive_cooperative_coevolution