---
title: "Delta modulation"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Delta_modulation"
wikipedia_categories: ["Data compression", "Digital signal processing"]
related: ["[[Codec]]", "[[Discrete cosine transform]]", "[[Lapped transform]]", "[[Line spectral pairs]]", "[[Linear predictive coding]]", "[[Nyquist–Shannon sampling theorem]]", "[[Quantization (signal processing)]]", "[[Time-domain harmonic scaling]]", "[[Warped linear predictive coding]]", "[[2D adaptive filters]]"]
---

# Delta modulation

Delta modulation (DM, ΔM, or Δ-modulation) is an analog-to-digital and digital-to-analog signal conversion technique used for transmission of voice information where quality is not of primary importance. DM is the simplest form of differential pulse-code modulation (DPCM) where the difference between successive samples is encoded into n-bit data streams. In delta modulation, the transmitted data are reduced to a 1-bit data stream representing either up (↗) or down (↘). Its main features are:

The analog signal is approximated with a series of segments.
Each segment of the approximated signal is compared to the preceding bits and the successive bits are determined by this comparison.
Only the change of information is sent, that is, only an increase or decrease of the signal amplitude from the previous sample is sent whereas a no-change condition causes the modulated signal to remain at the same ↗ or ↘ state of the previous sample.
To achieve high signal-to-noise ratio, delta modulation must use oversampling techniques, that is, the analog signal is sampled at a rate several times higher than the Nyquist rate.
Derived forms of delta modulation are continuously variable slope delta modulation, delta-sigma modulation, and differential modulation. Differential pulse-code modulation is the superset of DM.

## Related

- [[Codec]]
- [[Discrete cosine transform]]
- [[Lapped transform]]
- [[Line spectral pairs]]
- [[Linear predictive coding]]
- [[Nyquist–Shannon sampling theorem]]
- [[Quantization (signal processing)]]
- [[Time-domain harmonic scaling]]
- [[Warped linear predictive coding]]
- [[2D adaptive filters]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Delta_modulation