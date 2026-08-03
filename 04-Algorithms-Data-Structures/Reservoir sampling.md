---
title: "Reservoir sampling"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Reservoir_sampling"
wikipedia_categories: ["Algorithms", "Analysis of algorithms", "Randomized algorithms"]
related: ["[[External memory algorithm]]", "[[Multiplicative weight update method]]", "[[Randomized algorithm]]", "[[Adaptive algorithm]]", "[[Algorism]]", "[[Algorithm]]", "[[Algorithm characterizations]]", "[[Algorithm engineering]]", "[[Algorithm IMED]]", "[[Algorithmic amplification]]"]
---

# Reservoir sampling

Reservoir sampling is a family of randomized online algorithms for choosing a simple random sample, without replacement, of k items from a population of unknown size n in a single pass over the items.  The size of the population n is not known to the algorithm and is typically too large for all n items to fit into main memory.  The population is revealed to the algorithm over time, and the algorithm cannot look back at previous items. At any point, the current state of the algorithm must permit extraction of a simple random sample without replacement of size k over the part of the population seen so far.

## Related

- [[External memory algorithm]]
- [[Multiplicative weight update method]]
- [[Randomized algorithm]]
- [[Adaptive algorithm]]
- [[Algorism]]
- [[Algorithm]]
- [[Algorithm characterizations]]
- [[Algorithm engineering]]
- [[Algorithm IMED]]
- [[Algorithmic amplification]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Reservoir_sampling