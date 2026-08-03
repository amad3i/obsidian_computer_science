---
title: "Beta encoder"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Beta_encoder"
wikipedia_categories: ["Digital signal processing", "Signal processing"]
related: ["[[Aliasing]]", "[[BIBO stability]]", "[[Delay equalization]]", "[[Digital down converter]]", "[[Downsampling (signal processing)]]", "[[First-order hold]]", "[[Half-band filter]]", "[[Instantaneous phase and frequency]]", "[[Least-squares spectral analysis]]", "[[Linear time-invariant system]]"]
---

# Beta encoder

A beta encoder is an analog-to-digital conversion (A/D) system in which a real number in the unit interval is represented by a finite representation of a sequence in base beta, with beta being a real number between 1 and 2. Beta encoders are an alternative to traditional approaches to pulse-code modulation.
As a form of non-integer representation, beta encoding contrasts with traditional approaches to binary quantization, in which each value is mapped to the first N bits of its base-2 expansion. Rather than using base 2, beta encoders use base beta as a beta-expansion.
In practice, beta encoders have attempted to exploit the redundancy provided by the non-uniqueness of the expansion in base beta to produce more robust results. An early beta encoder, the Golden ratio encoder used the golden ratio base for its value of beta, but was susceptible to hardware errors. Although integrator leaks in hardware elements make some beta encoders imprecise, specific algorithms can be used to provide exponentially accurate approximations for the value of beta, despite the imprecise results provided by some circuit components.
An alternative design called the negative beta encoder (called so due to the negative eigenvalue of the transition probability matrix) has been proposed to further reduce the quantization error.

## Related

- [[Aliasing]]
- [[BIBO stability]]
- [[Delay equalization]]
- [[Digital down converter]]
- [[Downsampling (signal processing)]]
- [[First-order hold]]
- [[Half-band filter]]
- [[Instantaneous phase and frequency]]
- [[Least-squares spectral analysis]]
- [[Linear time-invariant system]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Beta_encoder