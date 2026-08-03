---
title: "Time–frequency analysis"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Time–frequency_analysis"
wikipedia_categories: ["Signal processing", "Time–frequency analysis"]
related: ["[[Ambiguity function]]", "[[Analytic signal]]", "[[Instantaneous phase and frequency]]", "[[Linear canonical transformation]]", "[[Low Frequency Analyzer and Recorder]]", "[[Multitaper]]", "[[Poisson wavelet]]", "[[Shearlet]]", "[[Short-time Fourier transform]]", "[[Spectral correlation density]]"]
---

# Time–frequency analysis

In signal processing, time–frequency analysis comprises those techniques that study a signal in both the time and frequency domains simultaneously, using various time–frequency representations. Rather than viewing a 1-dimensional signal (a function, real or complex-valued, whose domain is the real line) and some transform (another function whose domain is the real line, obtained from the original via some transform), time–frequency analysis studies a two-dimensional signal – a function whose domain is the two-dimensional real plane, obtained from the signal via a time–frequency transform.
The mathematical motivation for this study is that functions and their transform representation are tightly connected, and they can be understood better by studying them jointly, as a two-dimensional object, rather than separately. A simple example is that the 4-fold periodicity of the Fourier transform – and the fact that two-fold Fourier transform reverses direction – can be interpreted by considering the Fourier transform as a 90° rotation in the associated time–frequency plane: 4 such rotations yield the identity, and 2 such rotations simply reverse direction (reflection through the origin).
The practical motivation for time–frequency analysis is that classical Fourier analysis assumes that signals are infinite in time or periodic, while many signals in practice are of short duration, and change substantially over their duration. For example, traditional musical instruments do not produce infinite duration sinusoids, but instead begin with an attack, then gradually decay. This is poorly represented by traditional methods, which motivates time–frequency analysis.
One of the most basic forms of time–frequency analysis is the short-time Fourier transform (STFT), but more sophisticated techniques have been developed, notably wavelets and least-squares spectral analysis methods for unevenly spaced data.

## Related

- [[Ambiguity function]]
- [[Analytic signal]]
- [[Instantaneous phase and frequency]]
- [[Linear canonical transformation]]
- [[Low Frequency Analyzer and Recorder]]
- [[Multitaper]]
- [[Poisson wavelet]]
- [[Shearlet]]
- [[Short-time Fourier transform]]
- [[Spectral correlation density]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Time–frequency_analysis