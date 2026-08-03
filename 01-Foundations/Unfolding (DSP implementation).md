---
title: "Unfolding (DSP implementation)"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Unfolding_(DSP_implementation)"
wikipedia_categories: ["Digital signal processing"]
related: ["[[2D adaptive filters]]", "[[2D Z-transform]]", "[[Adaptive equalizer]]", "[[Adaptive filter]]", "[[Adaptive predictive coding]]", "[[Adaptive-additive algorithm]]", "[[Adjoint filter]]", "[[Advanced process control]]", "[[Aliasing]]", "[[All-pass filter]]"]
---

# Unfolding (DSP implementation)

Unfolding is a transformation technique of duplicating the functional blocks to increase the throughput of the DSP program in such a way that preserves its functional behavior at its outputs.
Unfolding was first proposed by Keshab K. Parhi and David G. Messerschmitt in 1989. Unfolding in general program is as known as Loop unrolling.
Unfolding has applications in designing high-speed and low-power ASIC architectures.
One application is to unfold the program to reveal hidden concurrency so that the program can be scheduled to a smaller iteration period, thus increasing the throughput of the implementation.
Another application is parallel processing in word level or bit level.
Therefore these transformed circuit could increase the throughput and decrease the power consumption.

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

- Wikipedia: https://en.wikipedia.org/wiki/Unfolding_(DSP_implementation)