---
title: "Discrete-time Fourier transform"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Discrete-time_Fourier_transform"
wikipedia_categories: ["Digital signal processing", "Fourier analysis", "Transforms"]
related: ["[[Non-uniform discrete Fourier transform]]", "[[Almost periodic function]]", "[[Bilinear transform]]", "[[Chirplet transform]]", "[[DFT matrix]]", "[[Dirac delta function]]", "[[Discrete cosine transform]]", "[[Discrete Fourier transform]]", "[[Fourier analysis]]", "[[Instantaneous phase and frequency]]"]
---

# Discrete-time Fourier transform

In mathematics, the discrete-time Fourier transform (DTFT) is a form of Fourier analysis that is applicable to a sequence of discrete values.
The DTFT is often used to analyze samples of a continuous function. The term discrete-time refers to the fact that the transform operates on discrete data, often samples whose interval has units of time. From uniformly spaced samples it produces a function of frequency that is a periodic summation of the continuous Fourier transform of the original continuous function. In simpler terms, when you take the DTFT of regularly-spaced samples of a continuous signal, you get repeating (and possibly overlapping) copies of the signal's frequency spectrum, spaced at intervals corresponding to the sampling frequency. Under certain theoretical conditions, described by the sampling theorem, the original continuous function can be recovered perfectly from the DTFT and thus from the original discrete samples. The DTFT itself is a continuous function of frequency, but discrete samples of it can be readily calculated via the discrete Fourier transform (DFT) (see § Sampling the DTFT), which is by far the most common method of modern Fourier analysis.
Both transforms are invertible. The inverse DTFT reconstructs the original sampled data sequence, while the inverse DFT produces a periodic summation of the original sequence. The fast Fourier transform (FFT) is an algorithm for computing one cycle of the DFT, and its inverse produces one cycle of the inverse DFT.

## Related

- [[Non-uniform discrete Fourier transform]]
- [[Almost periodic function]]
- [[Bilinear transform]]
- [[Chirplet transform]]
- [[DFT matrix]]
- [[Dirac delta function]]
- [[Discrete cosine transform]]
- [[Discrete Fourier transform]]
- [[Fourier analysis]]
- [[Instantaneous phase and frequency]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Discrete-time_Fourier_transform