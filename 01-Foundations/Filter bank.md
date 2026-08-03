---
title: "Filter bank"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Filter_bank"
wikipedia_categories: ["Digital signal processing", "Linear filters", "Wavelets"]
related: ["[[All-pass filter]]", "[[Anti-aliasing filter]]", "[[Discrete wavelet transform]]", "[[Lattice delay network]]", "[[Lifting scheme]]", "[[Polyphase matrix]]", "[[Polyphase quadrature filter]]", "[[Quadrature mirror filter]]", "[[Reconstruction filter]]", "[[2D adaptive filters]]"]
---

# Filter bank

In signal processing, a filter bank (or filterbank) is an array of bandpass filters that separates the input signal into multiple components, each one carrying a sub-band of the original signal. One application of a filter bank is a graphic equalizer, which can attenuate the components differently and recombine them into a modified version of the original signal.  The process of decomposition performed by the filter bank is called analysis (meaning analysis of the signal in terms of its components in each sub-band); the output of analysis is referred to as a subband signal with as many subbands as there are filters in the filter bank.  The reconstruction process is called synthesis, meaning reconstitution of a complete signal resulting from the filtering process.
In digital signal processing, the term filter bank is also commonly applied to a bank of receivers.  The difference is that receivers also down-convert the subbands to a low center frequency that can be re-sampled at a reduced rate.  The same result can sometimes be achieved by undersampling the bandpass subbands.
Another application of filter banks is lossy compression when some frequencies are more important than others.  After decomposition, the important frequencies can be coded with a fine resolution.  Small differences at these frequencies are significant and a coding scheme that preserves these differences must be used. On the other hand, less important frequencies do not have to be exact. A coarser coding scheme can be used, even though some of the finer (but less important) details will be lost in the coding.
The vocoder uses a filter bank to determine the amplitude information of the subbands of a modulator signal (such as a voice) and uses them to control the amplitude of the subbands of a carrier signal (such as the output of a guitar or synthesizer), thus imposing the dynamic characteristics of the modulator on the carrier.

Some filter banks work almost entirely in the time domain, using a series of filters such as quadrature mirror filters or the Goertzel algorithm to divide the signal into smaller bands.
Other filter banks use a fast Fourier transform (FFT).

## Related

- [[All-pass filter]]
- [[Anti-aliasing filter]]
- [[Discrete wavelet transform]]
- [[Lattice delay network]]
- [[Lifting scheme]]
- [[Polyphase matrix]]
- [[Polyphase quadrature filter]]
- [[Quadrature mirror filter]]
- [[Reconstruction filter]]
- [[2D adaptive filters]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Filter_bank