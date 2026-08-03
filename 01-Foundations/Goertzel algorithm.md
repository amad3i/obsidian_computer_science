---
title: "Goertzel algorithm"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Goertzel_algorithm"
wikipedia_categories: ["Digital signal processing", "Fast Fourier transforms"]
related: ["[[Fast Fourier transform]]", "[[Vector-radix FFT algorithm]]", "[[2D adaptive filters]]", "[[2D Z-transform]]", "[[Adaptive equalizer]]", "[[Adaptive filter]]", "[[Adaptive predictive coding]]", "[[Adaptive-additive algorithm]]", "[[Adjoint filter]]", "[[Advanced process control]]"]
---

# Goertzel algorithm

The Goertzel algorithm is a technique in digital signal processing (DSP) for efficient evaluation of the individual terms of the discrete Fourier transform (DFT). It is useful in certain practical applications, such as recognition of dual-tone multi-frequency signaling (DTMF) tones produced by the push buttons of the keypad of a traditional analog telephone. The algorithm was first described by Gerald Goertzel in 1958.
Like the DFT, the Goertzel algorithm analyses one selectable frequency component from a discrete signal.  Unlike direct DFT calculations, the Goertzel algorithm applies a single real-valued coefficient at each iteration, using real-valued arithmetic for real-valued input sequences. For covering a full spectrum (except when using for continuous stream of data where coefficients are reused for subsequent calculations, which has computational complexity equivalent of sliding DFT), the Goertzel algorithm has a higher order of complexity than fast Fourier transform (FFT) algorithms, but for computing a small number of selected frequency components, it is more numerically efficient. The simple structure of the Goertzel algorithm makes it well suited to small processors and embedded applications.
The Goertzel algorithm can also be used "in reverse" as a sinusoid synthesis function, which requires only 1 multiplication and 1 subtraction per generated sample.

## Related

- [[Fast Fourier transform]]
- [[Vector-radix FFT algorithm]]
- [[2D adaptive filters]]
- [[2D Z-transform]]
- [[Adaptive equalizer]]
- [[Adaptive filter]]
- [[Adaptive predictive coding]]
- [[Adaptive-additive algorithm]]
- [[Adjoint filter]]
- [[Advanced process control]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Goertzel_algorithm