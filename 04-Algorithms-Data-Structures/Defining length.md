---
title: "Defining length"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Defining_length"
wikipedia_categories: ["Computer science stubs", "Evolutionary algorithms", "Genetic algorithms"]
related: ["[[Cultural algorithm]]", "[[Evolutionary programming]]", "[[Fly algorithm]]", "[[Gene expression programming]]", "[[Genetic memory (computer science)]]", "[[Alewife (multiprocessor)]]", "[[ALF (proof assistant)]]", "[[Analog image processing]]", "[[AQUA@home]]", "[[Artificial development]]"]
---

# Defining length

In the field of genetic algorithms, a schema (plural: schemata) is a template that represents a subset of potential solutions. These templates use fixed symbols (e.g., `0` or `1`) for specific positions and a wildcard or "don't care" symbol (often `#` or `*`) for others.
The defining length of a schema, denoted as L(H), measures the distance between the outermost fixed positions in the template. According to the Schema theorem, a schema with a shorter defining length is less likely to be disrupted by the genetic operator of crossover. As a result, short schemata are considered more robust and are more likely to be propagated to the next generation.
In genetic programming, where solutions are often represented as trees, the defining length is the number of links in the minimum tree fragment that includes all the non-wildcard symbols within a schema H.

## Related

- [[Cultural algorithm]]
- [[Evolutionary programming]]
- [[Fly algorithm]]
- [[Gene expression programming]]
- [[Genetic memory (computer science)]]
- [[Alewife (multiprocessor)]]
- [[ALF (proof assistant)]]
- [[Analog image processing]]
- [[AQUA@home]]
- [[Artificial development]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Defining_length