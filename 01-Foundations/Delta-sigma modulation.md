---
title: "Delta-sigma modulation"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Delta-sigma_modulation"
wikipedia_categories: ["Digital signal processing"]
related: ["[[2D adaptive filters]]", "[[2D Z-transform]]", "[[Adaptive equalizer]]", "[[Adaptive filter]]", "[[Adaptive predictive coding]]", "[[Adaptive-additive algorithm]]", "[[Adjoint filter]]", "[[Advanced process control]]", "[[Aliasing]]", "[[All-pass filter]]"]
---

# Delta-sigma modulation

Delta-sigma (ΔΣ; or sigma-delta, ΣΔ) modulation is an oversampling method for encoding signals into low bit depth digital signals at a very high sample-frequency as part of the process of delta-sigma analog-to-digital converters (ADCs) and digital-to-analog converters (DACs). Delta-sigma modulation achieves high quality by utilizing a negative feedback loop during quantization to the lower bit depth that continuously corrects quantization errors and moves quantization noise to higher frequencies well above the original signal's bandwidth. Subsequent low-pass filtering for demodulation easily removes this high frequency noise and time averages to achieve high accuracy in amplitude, which can be ultimately encoded as pulse-code modulation (PCM).
Both ADCs and DACs can employ delta-sigma modulation. A delta-sigma ADC (e.g., Figure 1 top) encodes an analog signal using high-frequency delta-sigma modulation and then applies a digital filter to demodulate it to a high-bit digital output at a lower sampling frequency. A delta-sigma DAC (e.g., Figure 1 bottom) encodes a high-resolution digital input signal into a lower-resolution, but higher sample-frequency signal that may then be mapped to voltages and smoothed with an analog filter for demodulation. In both cases, the temporary use of a low bit depth signal at a higher sampling frequency simplifies circuit design and takes advantage of the efficiency and high accuracy in time of digital electronics.
Primarily because of its cost efficiency and reduced circuit complexity, this technique has found increasing use in modern electronic components such as DACs, ADCs, frequency synthesizers, switched-mode power supplies and motor controllers. The coarsely-quantized output of a delta-sigma ADC is occasionally used directly in signal processing or as a representation for signal storage (e.g., Super Audio CD stores the raw output of a 1-bit delta-sigma modulator).
While this article focuses on synchronous modulation, which requires a precise clock for quantization, asynchronous delta-sigma modulation instead runs without a clock.

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

- Wikipedia: https://en.wikipedia.org/wiki/Delta-sigma_modulation