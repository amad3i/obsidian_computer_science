---
title: "Folding (DSP implementation)"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Folding_(DSP_implementation)"
wikipedia_categories: ["Digital signal processing"]
related: ["[[2D adaptive filters]]", "[[2D Z-transform]]", "[[Adaptive equalizer]]", "[[Adaptive filter]]", "[[Adaptive predictive coding]]", "[[Adaptive-additive algorithm]]", "[[Adjoint filter]]", "[[Advanced process control]]", "[[Aliasing]]", "[[All-pass filter]]"]
---

# Folding (DSP implementation)

Folding

is a transformation technique used in DSP architecture implementations for minimizing the number of functional blocks in synthesizing DSP architecture.
Folding was first developed by Keshab K. Parhi and his students in 1992.
Its concept is contrary to unfolding.
Folding transforms an operation from a unit-time processing to N unit-times processing where N is called folding factor.
Therefore, multiple same operations (less than N) used in original system could be replaced with a signal operation block in transformed system.
Thus, in N unit-times, a functional block in transformed system could be reused to perform N operations in original system.
While the folding transformation reduces the number of functional units in the architecture, it needs more memory element to store the temporary data.
The reason is that multiple data produced from an operation block needs to be distinguished from N data produced from original operations.
Therefore, the number of register may be increased.
Furthermore,  it needs additional multiplexer for switching different operation paths.
Hence, the number of switching elements would also be increased.
To counterattack such issues, the considerations of folding is

How to schedule multiple operations into an operation block.
How to schedule the memory element for reducing the number of registers and multiplexers.

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

- Wikipedia: https://en.wikipedia.org/wiki/Folding_(DSP_implementation)