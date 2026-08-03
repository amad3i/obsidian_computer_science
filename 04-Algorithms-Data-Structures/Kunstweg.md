---
title: "Kunstweg"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Kunstweg"
wikipedia_categories: ["Algorithms", "Trigonometry"]
related: ["[[Adaptive algorithm]]", "[[Algorism]]", "[[Algorithm]]", "[[Algorithm characterizations]]", "[[Algorithm engineering]]", "[[Algorithm IMED]]", "[[Algorithmic amplification]]", "[[Algorithmic logic]]", "[[Algorithmic management]]", "[[Algorithmic mechanism design]]"]
---

# Kunstweg

Bürgi's Kunstweg is a set of algorithms developed by Jost Bürgi in the late 16th century. They are used to calculate sines to arbitrary precision.. Bürgi used these algorithms to calculate a Canon Sinuum, a sine table in increments of 2 arc seconds. It is believed that the table featured values accurate to eight sexagesimal places. Some authors have speculated that the table only covered the range from 0° to 45°, although there is no evidence supporting this claim. Such tables were crucial for maritime navigation. Johannes Kepler described the Canon Sinuum as the most precise sine table known at the time. Bürgi explained his algorithms in his work Fundamentum Astronomiae, which he presented to Emperor Rudolf II in 1592.
The Kunstweg algorithm calculates sine values iteratively. In each step, the value of a cell is the sum of the two preceding cells in the same column. The final cell's value is halved before beginning the next iteration. Ultimately, the values in the last column are normalized. Accurate sine approximations are achieved after only a few iterations.
In 2015, Menso Folkerts and coworkers demonstrated that this iterative process does indeed converge toward the true sine values. According to them this was the first step towards  differential calculus.

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

- Wikipedia: https://en.wikipedia.org/wiki/Kunstweg