---
title: "Blind equalization"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Blind_equalization"
wikipedia_categories: ["Signal processing", "Telecommunication theory"]
related: ["[[Bandwidth (signal processing)]]", "[[Coherence (signal processing)]]", "[[Detection theory]]", "[[Filter (signal processing)]]", "[[Hilbert–Huang transform]]", "[[Multidimensional empirical mode decomposition]]", "[[Pulse duration]]", "[[Pulse shaping]]", "[[Quantization (signal processing)]]", "[[Signal]]"]
---

# Blind equalization

Blind equalization is a digital signal processing technique in which the transmitted signal is inferred (equalized) from the received signal, while making use only of the transmitted signal statistics. Hence, the use of the word blind in the name.
Blind equalization is essentially blind deconvolution applied to digital communications. Nonetheless, the emphasis in blind equalization is on online estimation of the equalization filter, which is the inverse of the channel impulse response, rather than the estimation of the channel impulse response itself. This is due to blind deconvolution common mode of usage in digital communications systems, as a means to extract the continuously transmitted signal from the received signal, with the channel impulse response being of secondary intrinsic importance.
The estimated equalizer is then convolved with the received signal to yield an estimation of the transmitted signal.

## Related

- [[Bandwidth (signal processing)]]
- [[Coherence (signal processing)]]
- [[Detection theory]]
- [[Filter (signal processing)]]
- [[Hilbert–Huang transform]]
- [[Multidimensional empirical mode decomposition]]
- [[Pulse duration]]
- [[Pulse shaping]]
- [[Quantization (signal processing)]]
- [[Signal]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Blind_equalization