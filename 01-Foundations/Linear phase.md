---
title: "Linear phase"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Linear_phase"
wikipedia_categories: ["Digital signal processing"]
related: ["[[2D adaptive filters]]", "[[2D Z-transform]]", "[[Adaptive equalizer]]", "[[Adaptive filter]]", "[[Adaptive predictive coding]]", "[[Adaptive-additive algorithm]]", "[[Adjoint filter]]", "[[Advanced process control]]", "[[Aliasing]]", "[[All-pass filter]]"]
---

# Linear phase

In signal processing, linear phase is a property of a filter where the phase response of the filter is a linear function of frequency. The result is that all frequency components of the input signal are shifted in time (usually delayed) by the same constant amount (the slope of the linear function), which is referred to as the group delay. Consequently, there is no phase distortion due to the time delay of frequencies relative to one another.
Zero-phase filters are a special case of linear-phase filters where the group delay is zero.  In non-real-time digital signal processing, this can be obtained from any linear-phase filter simply by shifting the filtered output of a linear-phase filter backwards in time by the linear-phase filter's group delay, so sometimes all linear-phase filters are loosely referred to as zero-phase filters.
For discrete-time signals, perfect linear phase is easily achieved with a finite impulse response (FIR) filter by having coefficients which are symmetric or anti-symmetric. Approximations can be achieved with infinite impulse response (IIR) designs, which are more computationally efficient. Several techniques are:

a Bessel transfer function which has a maximally flat group delay approximation function
a phase equalizer

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

- Wikipedia: https://en.wikipedia.org/wiki/Linear_phase