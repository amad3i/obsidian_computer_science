---
title: "Minimum phase"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Minimum_phase"
wikipedia_categories: ["Control theory", "Digital signal processing"]
related: ["[[Advanced process control]]", "[[Anticausal system]]", "[[Bilinear transform]]", "[[First-order hold]]", "[[Matched Z-transform method]]", "[[PLL multibit]]", "[[System analysis]]", "[[Zero-order hold]]", "[[2D adaptive filters]]", "[[2D Z-transform]]"]
---

# Minimum phase

In control theory and signal processing, a linear, time-invariant system is said to be minimum-phase if the system and its inverse are causal and stable.
The most general causal LTI transfer function can be uniquely factored into a series of an all-pass and a minimum phase system. The system function is then the product of the two parts, and in the time domain the response of the system is the convolution of the two part responses. The difference between a minimum-phase and a general transfer function is that a minimum-phase system has all of the poles and zeros of its transfer function in the left half of the s-plane representation (in discrete time, respectively, inside the unit circle of the z plane). Since inverting a system function leads to poles turning to zeros and conversely, and poles on the right side (s-plane imaginary line) or outside (z-plane unit circle) of the complex plane lead to unstable systems, only the class of minimum-phase systems is closed under inversion. Intuitively, the minimum-phase part of a general causal system implements its amplitude response with minimal group delay, while its all-pass part corrects its phase response alone to correspond with the original system function.
The analysis in terms of poles and zeros is exact only in the case of transfer functions which can be expressed as ratios of polynomials. In the continuous-time case, such systems translate into networks of conventional, idealized LCR networks. In discrete time, they conveniently translate into approximations thereof, using addition, multiplication, and unit delay. It can be shown that in both cases, system functions of rational form with increasing order can be used to efficiently approximate any other system function; thus even system functions lacking a rational form, and so possessing an infinitude of poles and/or zeros, can in practice be implemented as efficiently as any other.
In the context of causal, stable systems, we would in theory be free to choose whether the zeros of the system function are outside of the stable range (to the right or outside) if the closure condition wasn't an issue. However, inversion is of great practical importance, just as theoretically perfect factorizations are in their own right. (Cf. the spectral symmetric/antisymmetric decomposition as another important example, leading e.g. to Hilbert transform techniques.) Many physical systems also naturally tend towards minimum-phase response, and sometimes have to be inverted using other physical systems obeying the same constraint.
Insight is given below as to why this system is called minimum-phase, and why the basic idea applies even when the system function cannot be cast into a rational form that could be implemented.

## Related

- [[Advanced process control]]
- [[Anticausal system]]
- [[Bilinear transform]]
- [[First-order hold]]
- [[Matched Z-transform method]]
- [[PLL multibit]]
- [[System analysis]]
- [[Zero-order hold]]
- [[2D adaptive filters]]
- [[2D Z-transform]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Minimum_phase