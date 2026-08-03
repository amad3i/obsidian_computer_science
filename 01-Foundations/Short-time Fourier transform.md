---
title: "Short-time Fourier transform"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Short-time_Fourier_transform"
wikipedia_categories: ["Fourier analysis", "Signal processing", "Time–frequency analysis", "Transforms"]
related: ["[[Analytic signal]]", "[[Chirplet transform]]", "[[Instantaneous phase and frequency]]", "[[Linear canonical transformation]]", "[[Overlap–add method]]", "[[Overlap–save method]]", "[[Ambiguity function]]", "[[Discrete-time Fourier transform]]", "[[Low Frequency Analyzer and Recorder]]", "[[Modified Wigner distribution function]]"]
---

# Short-time Fourier transform

The short-time Fourier transform (STFT) is a Fourier-related transform used to determine the sinusoidal frequency and phase content of local sections of a signal as it changes over time. In practice, the procedure for computing STFTs is to divide a longer time signal into shorter segments of equal length and then compute the Fourier transform separately on each shorter segment. This reveals the Fourier spectrum on each shorter segment.  One then usually plots the changing spectra as a function of time, known as a spectrogram or waterfall plot, such as commonly used in software defined radio (SDR) based spectrum displays. Full bandwidth displays covering the whole range of an SDR commonly use fast Fourier transforms (FFTs).

## Related

- [[Analytic signal]]
- [[Chirplet transform]]
- [[Instantaneous phase and frequency]]
- [[Linear canonical transformation]]
- [[Overlap–add method]]
- [[Overlap–save method]]
- [[Ambiguity function]]
- [[Discrete-time Fourier transform]]
- [[Low Frequency Analyzer and Recorder]]
- [[Modified Wigner distribution function]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Short-time_Fourier_transform