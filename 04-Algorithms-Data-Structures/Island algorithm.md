---
title: "Island algorithm"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Island_algorithm"
wikipedia_categories: ["Bioinformatics algorithms", "Hidden Markov models"]
related: ["[[3D-Jury]]", "[[Adaptive sampling]]", "[[Baum–Welch algorithm]]", "[[Brown clustering]]", "[[Complete-linkage clustering]]", "[[Folding@home]]", "[[Hidden Markov model]]", "[[Hidden semi-Markov model]]", "[[Hierarchical hidden Markov model]]", "[[Layered hidden Markov model]]"]
---

# Island algorithm

The island algorithm is an algorithm for performing inference on hidden Markov models, or their generalization, dynamic Bayesian networks.
It calculates the marginal distribution for each unobserved node, conditional on any observed nodes. 
The island algorithm is a modification of belief propagation.  
It trades smaller memory usage for longer running time: while belief propagation takes O(n) time and O(n) memory, the island algorithm takes O(n log n) time and O(log n) memory.  On a computer with an unlimited number of processors, this can be reduced to O(n) total time, while still taking only O(log n) memory.

## Related

- [[3D-Jury]]
- [[Adaptive sampling]]
- [[Baum–Welch algorithm]]
- [[Brown clustering]]
- [[Complete-linkage clustering]]
- [[Folding@home]]
- [[Hidden Markov model]]
- [[Hidden semi-Markov model]]
- [[Hierarchical hidden Markov model]]
- [[Layered hidden Markov model]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Island_algorithm