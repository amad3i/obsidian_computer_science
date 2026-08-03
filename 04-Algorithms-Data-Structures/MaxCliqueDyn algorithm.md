---
title: "MaxCliqueDyn algorithm"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/MaxCliqueDyn_algorithm"
wikipedia_categories: ["Graph algorithms"]
related: ["[[A- search algorithm]]", "[[Alpha–beta pruning]]", "[[Aperiodic graph]]", "[[B-]]", "[[Barabási–Albert model]]", "[[Belief propagation]]", "[[Bellman–Ford algorithm]]", "[[Bianconi–Barabási model]]", "[[Bidirectional search]]", "[[Blossom algorithm]]"]
---

# MaxCliqueDyn algorithm

The MaxCliqueDyn algorithm is an algorithm for finding a maximum clique in an undirected graph.
MaxCliqueDyn  is based on the MaxClique algorithm, which finds a maximum clique of bounded size. The bound is found using a coloring algorithm. MaxCliqueDyn extends MaxClique to include dynamically varying bounds.
This algorithm was designed by Janez Konc and its description was published in 2007. In comparison to earlier algorithms, MaxCliqueDyn has an improved coloring algorithm (ColorSort) and applies tighter, more computationally expensive upper bounds on a fraction of the search space. Both improvements reduce time to find maximum clique. In addition to reducing time, the improved coloring algorithm also reduces the number of steps needed to find a maximum clique.

## Related

- [[A- search algorithm]]
- [[Alpha–beta pruning]]
- [[Aperiodic graph]]
- [[B-]]
- [[Barabási–Albert model]]
- [[Belief propagation]]
- [[Bellman–Ford algorithm]]
- [[Bianconi–Barabási model]]
- [[Bidirectional search]]
- [[Blossom algorithm]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/MaxCliqueDyn_algorithm