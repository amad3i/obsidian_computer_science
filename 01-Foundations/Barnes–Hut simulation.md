---
title: "Barnes–Hut simulation"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Barnes–Hut_simulation"
wikipedia_categories: ["Gravity", "Numerical integration", "Physical cosmology", "Simulation"]
related: ["[[N-body simulation]]", "[[Millennium Run]]", "[[Activation strain model]]", "[[Artificial life]]", "[[Ashfield House]]", "[[AXIS Flight Training Systems]]", "[[Behavior authoring]]", "[[Benefit financing model]]", "[[Boole's rule]]", "[[Business simulation]]"]
---

# Barnes–Hut simulation

The Barnes–Hut simulation (named after Joshua Barnes and Piet Hut) is an approximation algorithm for performing an N-body simulation. It is notable for having order O(n log n) compared to a direct-sum algorithm which would be O(n2).
The simulation volume is usually divided up into cubic cells via an octree (in a three-dimensional space), so that only particles from nearby cells need to be treated individually, and particles in distant cells can be treated as a single large particle centered at the cell's center of mass (or as a low-order multipole expansion). This can dramatically reduce the number of particle pair interactions that must be computed.

Some of the most demanding high-performance computing projects perform computational astrophysics using the Barnes–Hut treecode algorithm, such as DEGIMA.

## Related

- [[N-body simulation]]
- [[Millennium Run]]
- [[Activation strain model]]
- [[Artificial life]]
- [[Ashfield House]]
- [[AXIS Flight Training Systems]]
- [[Behavior authoring]]
- [[Benefit financing model]]
- [[Boole's rule]]
- [[Business simulation]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Barnes–Hut_simulation