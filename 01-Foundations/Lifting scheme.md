---
title: "Lifting scheme"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Lifting_scheme"
wikipedia_categories: ["Digital signal processing", "Matrix decompositions", "Wavelets"]
related: ["[[Discrete wavelet transform]]", "[[Filter bank]]", "[[Polyphase matrix]]", "[[Quadrature mirror filter]]", "[[2D adaptive filters]]", "[[2D Z-transform]]", "[[Adaptive equalizer]]", "[[Adaptive filter]]", "[[Adaptive predictive coding]]", "[[Adaptive-additive algorithm]]"]
---

# Lifting scheme

The lifting scheme is a technique for both designing wavelets and performing the discrete wavelet transform (DWT). In an implementation, it is often worthwhile to merge these steps and design the wavelet filters while performing the wavelet transform. This is then called the second-generation wavelet transform. The technique was introduced by Wim Sweldens.
The lifting scheme factorizes any discrete wavelet transform with finite filters into a series of elementary convolution operators, so-called lifting steps, which reduces the number of arithmetic operations by nearly a factor two. Treatment of signal boundaries is also simplified.
The discrete wavelet transform applies several filters separately to the same signal. In contrast to that, for the lifting scheme, the signal is divided like a zipper. Then a series of convolution–accumulate operations across the divided signals is applied.

## Related

- [[Discrete wavelet transform]]
- [[Filter bank]]
- [[Polyphase matrix]]
- [[Quadrature mirror filter]]
- [[2D adaptive filters]]
- [[2D Z-transform]]
- [[Adaptive equalizer]]
- [[Adaptive filter]]
- [[Adaptive predictive coding]]
- [[Adaptive-additive algorithm]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Lifting_scheme