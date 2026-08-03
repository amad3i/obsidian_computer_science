---
title: "Phase vocoder"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Phase_vocoder"
wikipedia_categories: ["Signal processing", "Speech synthesis"]
related: ["[[International Speech Communication Association]]", "[[Adaptive beamformer]]", "[[Adjacent channel power ratio]]", "[[Algebraic signal processing]]", "[[Aliasing]]", "[[Ambiguity function]]", "[[Analog signal processing]]", "[[Analytic signal]]", "[[Angle of arrival]]", "[[Apodization]]"]
---

# Phase vocoder

A phase vocoder is a type of vocoder-purposed algorithm which can interpolate information present in the frequency and time domains of audio signals by using phase information extracted from a frequency transform.  The computer algorithm allows frequency-domain modifications to a digital sound file (typically time expansion/compression and pitch shifting).
At the heart of the phase vocoder is the short-time Fourier transform (STFT), typically coded using fast Fourier transforms. The STFT converts a time domain representation of sound into a time-frequency representation (the "analysis" phase), allowing modifications to the amplitudes or phases of specific frequency components of the sound, before resynthesis of the time-frequency domain representation into the time domain by the inverse STFT. The time evolution of the resynthesized sound can be changed by means of  modifying the time position of the STFT frames prior to the resynthesis operation
allowing for time-scale modification of the original sound file.

## Related

- [[International Speech Communication Association]]
- [[Adaptive beamformer]]
- [[Adjacent channel power ratio]]
- [[Algebraic signal processing]]
- [[Aliasing]]
- [[Ambiguity function]]
- [[Analog signal processing]]
- [[Analytic signal]]
- [[Angle of arrival]]
- [[Apodization]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Phase_vocoder