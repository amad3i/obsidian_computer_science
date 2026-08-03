---
title: "Token-based replay"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Token-based_replay"
wikipedia_categories: ["Algorithms"]
related: ["[[Adaptive algorithm]]", "[[Algorism]]", "[[Algorithm]]", "[[Algorithm characterizations]]", "[[Algorithm engineering]]", "[[Algorithm IMED]]", "[[Algorithmic amplification]]", "[[Algorithmic logic]]", "[[Algorithmic management]]", "[[Algorithmic mechanism design]]"]
---

# Token-based replay

Token-based replay technique is a conformance checking algorithm  that checks how well a process conforms with its model by replaying each trace on the model (in Petri net notation ). Using the four counters produced tokens, consumed tokens, missing tokens, and remaining tokens, it records the situations where a transition is forced to fire and the remaining tokens after the replay ends. Based on the count at each counter, we can compute the fitness value between the trace and the model.

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

- Wikipedia: https://en.wikipedia.org/wiki/Token-based_replay