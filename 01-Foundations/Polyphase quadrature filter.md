---
title: "Polyphase quadrature filter"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Polyphase_quadrature_filter"
wikipedia_categories: ["Digital signal processing", "Linear filters", "Signal processing stubs"]
related: ["[[Adjoint filter]]", "[[All-pass filter]]", "[[Anti-aliasing filter]]", "[[Delay equalization]]", "[[Encoding law]]", "[[Fast Walsh–Hadamard transform]]", "[[Filter bank]]", "[[High frequency content measure]]", "[[Lattice delay network]]", "[[Reconstruction filter]]"]
---

# Polyphase quadrature filter

A polyphase quadrature filter, or PQF, is a filter bank which splits an input signal into a given number N (mostly a power of 2) of equally distant sub-bands. A factor of N subsamples these sub-bands, so they are critically sampled.
An important application of the polyphase filters (of FIR type) concerns the filtering and decimation of large band (and so high sample rate) input signals, e.g. coming from a high rate ADC, which can not be directly processed by an FPGA or in some case by an ASIC either. Suppose the ADC plus FPGA/ASIC interface implements a demultiplexer of the ADC samples in N internal FPGA/ASIC registers. In that case, the polyphase filter transforms the decimator FIR filter canonic structure in N parallel branches clocked at 1÷N of the ADC clock, allowing digital processing when N=Clock(ADC)÷Clock(FPGA).
This critical sampling introduces aliasing. Similar to the MDCT time domain alias cancellation the aliasing of polyphase quadrature filters is canceled by neighbouring sub-bands, i.e. signals are typically stored in two sub-bands.
Note that signal in odd subbands is stored frequency inverted.
PQF filters are used in MPEG-1 Audio Layer I and II, Musepack (which was based on MPEG-1 layer II), in MPEG-1 Layer III with an additional MDCT, in MPEG-4 AAC-SSR for the 4 band PQF bank, in MPEG-4 V3 SBR
for the analysis of the upper spectral replicated band, and in DTS.
PQF has an advantage over the very similar stacked quadrature mirror filter (QMF). Delay and computational effort are much lower.
A PQF filter bank is constructed using a base filter, which is a low-pass at fs÷4N. This lowpass is modulated by N cosine functions and converted to N band-passes with a bandwidth of fs÷2N.
The base lowpass is typically a FIR filter with a length of 10×N ... 24×N taps. Note that it is also possible to build PQF filters using recursive IIR filters.

## Related

- [[Adjoint filter]]
- [[All-pass filter]]
- [[Anti-aliasing filter]]
- [[Delay equalization]]
- [[Encoding law]]
- [[Fast Walsh–Hadamard transform]]
- [[Filter bank]]
- [[High frequency content measure]]
- [[Lattice delay network]]
- [[Reconstruction filter]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Polyphase_quadrature_filter