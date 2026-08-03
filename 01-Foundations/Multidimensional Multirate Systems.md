---
title: "Multidimensional Multirate Systems"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Multidimensional_Multirate_Systems"
wikipedia_categories: ["Digital signal processing", "Video signal"]
related: ["[[2D adaptive filters]]", "[[2D Z-transform]]", "[[Adaptive equalizer]]", "[[Adaptive filter]]", "[[Adaptive predictive coding]]", "[[Adaptive-additive algorithm]]", "[[Adjoint filter]]", "[[Advanced process control]]", "[[Aliasing]]", "[[All-pass filter]]"]
---

# Multidimensional Multirate Systems

Multidimensional Multirate systems find applications in image compression and coding. Several applications such as conversion between progressive video signals require usage of multidimensional multirate systems. In multidimensional multirate systems, the basic building blocks are decimation matrix (M), expansion matrix(L) and Multidimensional digital filters. The decimation and expansion matrices have dimension of D x D, where D represents the dimension. To extend the one dimensional (1-D)  multirate results, there are two different ways which are based on the structure of decimation and expansion matrices. If these matrices are diagonal, separable approaches can be used, which are separable operations in each dimension. Although separable approaches might serve less complexity, non-separable methods, with non-diagonal expansion and decimation matrices, provide much better performance. The difficult part in non-separable methods is to create results in MD case by extend the 1-D case. Polyphase decomposition and maximally decimated reconstruction systems are already carried out.
MD decimation / interpolation filters derived from 1-D filters and maximally decimated filter banks are widely used and constitute important steps in the design of multidimensional multirate systems.

## Related

- [[2D adaptive filters]]
- [[2D Z-transform]]
- [[Adaptive equalizer]]
- [[Adaptive filter]]
- [[Adaptive predictive coding]]
- [[Adaptive-additive algorithm]]
- [[Adjoint filter]]
- [[Advanced process control]]
- [[Aliasing]]
- [[All-pass filter]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Multidimensional_Multirate_Systems