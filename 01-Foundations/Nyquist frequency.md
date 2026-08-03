---
title: "Nyquist frequency"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Nyquist_frequency"
wikipedia_categories: ["Digital signal processing"]
related: ["[[2D adaptive filters]]", "[[2D Z-transform]]", "[[Adaptive equalizer]]", "[[Adaptive filter]]", "[[Adaptive predictive coding]]", "[[Adaptive-additive algorithm]]", "[[Adjoint filter]]", "[[Advanced process control]]", "[[Aliasing]]", "[[All-pass filter]]"]
---

# Nyquist frequency

In signal processing, the Nyquist frequency (or folding frequency) is a characteristic of a sampler, which converts a continuous function or signal into a discrete sequence. It is named after Harry Nyquist. For a given sampling rate (samples per second), the Nyquist frequency (cycles per second) is the frequency whose cycle-length (or period) is twice the interval between samples, thus 0.5 cycle/sample.  For example, audio CDs have a sampling rate of 44100 samples/second.  At 0.5 cycle/sample, the corresponding Nyquist frequency is 22050 cycles/second (Hz).  Conversely, the Nyquist rate for sampling a 22050 Hz signal is 44100 samples/second. 
When the highest frequency (bandwidth) of a signal is less than the Nyquist frequency of the sampler, the resulting discrete-time sequence is said to be free of the distortion known as aliasing, and the corresponding sample rate is said to be above the Nyquist rate for that particular signal.
In a typical application of sampling, one first chooses the highest frequency to be preserved and recreated, based on the expected content (voice, music, etc.) and desired fidelity. Then one inserts an anti-aliasing filter ahead of the sampler. Its job is to attenuate the frequencies above that limit. Finally, based on the characteristics of the filter, one chooses a sample rate (and corresponding Nyquist frequency) that will provide an acceptably small amount of aliasing.  In applications where the sample rate is predetermined (such as the CD rate), the filter is chosen based on the Nyquist frequency, rather than vice versa.

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

- Wikipedia: https://en.wikipedia.org/wiki/Nyquist_frequency