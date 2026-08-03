---
title: "Noise shaping"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Noise_shaping"
wikipedia_categories: ["Audio engineering", "Digital signal processing", "Noise (electronics)"]
related: ["[[Almost periodic function]]", "[[Audio normalization]]", "[[Audio time stretching and pitch scaling]]", "[[Dither]]", "[[Effective number of bits]]", "[[Instantaneous phase and frequency]]", "[[Pitch correction]]", "[[Pitch detection algorithm]]", "[[Pitch shifting]]", "[[Quantization (signal processing)]]"]
---

# Noise shaping

In signal processing, noise shaping is a technique typically used when processing digital audio, image, and video signals. It is usually used in combination with dithering, and forms part of the process of quantization or bit-depth reduction of a signal. Its purpose is to increase the apparent signal-to-noise ratio of the resultant signal. It does this by altering the spectral shape of the error that is introduced by dithering and quantization, such that the noise power is at a lower level in frequency bands at which noise is considered to be less desirable and at a correspondingly higher level in bands where it is considered to be more desirable. A popular noise shaping algorithm used in image processing is known as ‘Floyd Steinberg dithering’; and many noise shaping algorithms used in audio processing are based on an ‘Absolute threshold of hearing’ model.

## Related

- [[Almost periodic function]]
- [[Audio normalization]]
- [[Audio time stretching and pitch scaling]]
- [[Dither]]
- [[Effective number of bits]]
- [[Instantaneous phase and frequency]]
- [[Pitch correction]]
- [[Pitch detection algorithm]]
- [[Pitch shifting]]
- [[Quantization (signal processing)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Noise_shaping