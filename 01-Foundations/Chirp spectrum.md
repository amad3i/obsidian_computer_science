---
title: "Chirp spectrum"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Chirp_spectrum"
wikipedia_categories: ["Signal processing"]
related: ["[[Adaptive beamformer]]", "[[Adjacent channel power ratio]]", "[[Algebraic signal processing]]", "[[Aliasing]]", "[[Ambiguity function]]", "[[Analog signal processing]]", "[[Analytic signal]]", "[[Angle of arrival]]", "[[Apodization]]", "[[Argument (complex analysis)]]"]
---

# Chirp spectrum

The spectrum of a chirp pulse describes its characteristics in terms of its frequency components.   This frequency-domain representation is an alternative to the more familiar time-domain waveform, and the two versions are mathematically related by the Fourier transform.  The spectrum is of particular interest when pulses are subject to signal processing.    For example, when a chirp pulse is compressed by its matched filter, the resulting waveform contains not only a main narrow pulse but, also, a variety of unwanted artifacts many of which are directly attributable to features in the chirp's spectral characteristics.
A simple way to derive the spectrum of a chirp using a computer is to sample the time-domain waveform at a frequency well above the Nyquist limit and use an FFT algorithm to obtain the desired result.  As this approach was not an option for the early designers, they resorted to analytic analysis, or and to graphical or approximation methods. These early methods still remain helpful, however, as they give additional insight into the behavior and properties of chirps.

## Related

- [[Adaptive beamformer]]
- [[Adjacent channel power ratio]]
- [[Algebraic signal processing]]
- [[Aliasing]]
- [[Ambiguity function]]
- [[Analog signal processing]]
- [[Analytic signal]]
- [[Angle of arrival]]
- [[Apodization]]
- [[Argument (complex analysis)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Chirp_spectrum