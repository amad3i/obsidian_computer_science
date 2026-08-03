---
title: "Digital signal (signal processing)"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Digital_signal_(signal_processing)"
wikipedia_categories: ["Digital signal processing"]
related: ["[[2D adaptive filters]]", "[[2D Z-transform]]", "[[Adaptive equalizer]]", "[[Adaptive filter]]", "[[Adaptive predictive coding]]", "[[Adaptive-additive algorithm]]", "[[Adjoint filter]]", "[[Advanced process control]]", "[[Aliasing]]", "[[All-pass filter]]"]
---

# Digital signal (signal processing)

In the context of digital signal processing (DSP), a digital signal is a discrete time, quantized amplitude signal. In other words, it is a sampled signal consisting of samples that take on values from a discrete set (a countable set that can be mapped one-to-one to a subset of integers). If that discrete set is finite, the discrete values can be represented with digital words of a finite width. Most commonly, these discrete values are represented as fixed-point words (either proportional to the waveform values or companded) or floating-point words.

The process of analog-to-digital conversion produces a digital signal. The conversion process can be thought of as occurring in two steps:

sampling, which produces a continuous-valued discrete-time signal, and
quantization, which replaces each sample value with an approximation selected from a given discrete set (for example, by truncating or rounding).
An analog signal can be reconstructed after conversion to digital (down to the precision afforded by the quantization used), provided that the signal has negligible power in frequencies above the Nyquist limit and does not saturate the quantizer.
Common practical digital signals are represented as 8-bit (256 levels), 16-bit (65,536 levels), 24-bit (16.8 million levels), and 32-bit (4.3 billion levels) using pulse-code modulation where the number of quantization levels is not necessarily limited to powers of two. A floating point representation is used in many DSP applications.

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

- Wikipedia: https://en.wikipedia.org/wiki/Digital_signal_(signal_processing)