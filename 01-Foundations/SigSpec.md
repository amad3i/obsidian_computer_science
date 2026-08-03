---
title: "SigSpec"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/SigSpec"
wikipedia_categories: ["Digital signal processing", "Fourier analysis", "Statistical signal processing"]
related: ["[[Almost periodic function]]", "[[DFT matrix]]", "[[Dirac delta function]]", "[[Discrete cosine transform]]", "[[Discrete Fourier transform]]", "[[Discrete-time Fourier transform]]", "[[Fourier analysis]]", "[[Instantaneous phase and frequency]]", "[[Least-squares spectral analysis]]", "[[Non-uniform discrete Fourier transform]]"]
---

# SigSpec

SigSpec (acronym of SIGnificance SPECtrum) is a statistical technique to provide the reliability of periodicities in a measured (noisy and not necessarily equidistant) time series. It relies on the amplitude spectrum obtained by the Discrete Fourier transform (DFT) and assigns a quantity called the spectral significance (frequently abbreviated by “sig”) to each amplitude. This quantity is a logarithmic measure of the probability that the given amplitude level would be seen in white noise, in the sense of a type I error. It represents the answer to the question, “What would be the chance to obtain an amplitude like the measured one or higher, if the analysed time series were random?”
SigSpec may be considered a formal extension to the Lomb–Scargle periodogram, appropriately incorporating a time series to be averaged to zero before applying the DFT, which is done in many practical applications. When a zero-mean corrected dataset has to be statistically compared to a random sample, the sample mean (rather than the population mean only) has to be zero.

## Related

- [[Almost periodic function]]
- [[DFT matrix]]
- [[Dirac delta function]]
- [[Discrete cosine transform]]
- [[Discrete Fourier transform]]
- [[Discrete-time Fourier transform]]
- [[Fourier analysis]]
- [[Instantaneous phase and frequency]]
- [[Least-squares spectral analysis]]
- [[Non-uniform discrete Fourier transform]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/SigSpec