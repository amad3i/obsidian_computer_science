---
title: "Cellular evolutionary algorithm"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Cellular_evolutionary_algorithm"
wikipedia_categories: ["Evolutionary algorithms"]
related: ["[[Artificial development]]", "[[Constructive cooperative coevolution]]", "[[Cultural algorithm]]", "[[Defining length]]", "[[Differential evolution]]", "[[Dispersive flies optimisation]]", "[[Effective fitness]]", "[[Evolutionary algorithm]]", "[[Evolutionary multimodal optimization]]", "[[Evolutionary programming]]"]
---

# Cellular evolutionary algorithm

A cellular evolutionary algorithm (cEA) is a kind of evolutionary algorithm (EA) in which individuals cannot mate arbitrarily, but every one interacts with its closer neighbors on which a basic EA is applied (selection, variation, replacement).

The cellular model simulates natural evolution from the point of view of
the individual, which encodes a tentative optimization, learning, or search problem solution. The essential idea of this model is to provide the EA population
with a special structure defined as a connected graph, in which each vertex is an individual that communicates with its nearest neighbors. Particularly, individuals are conceptually set in a toroidal
mesh, and are only allowed to recombine with close individuals. This leads
to a kind of locality known as "isolation by distance". The set of potential mates
of an individual is called its neighborhood. It is known that, in this kind
of algorithm, similar individuals tend to cluster creating niches, and these groups
operate as if they were separate sub-populations (islands). There is no
clear demarcation between adjacent groups and close niches could be easily
"colonized" by competitive niches, potentially merging solution contents during the process.

## Related

- [[Artificial development]]
- [[Constructive cooperative coevolution]]
- [[Cultural algorithm]]
- [[Defining length]]
- [[Differential evolution]]
- [[Dispersive flies optimisation]]
- [[Effective fitness]]
- [[Evolutionary algorithm]]
- [[Evolutionary multimodal optimization]]
- [[Evolutionary programming]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Cellular_evolutionary_algorithm