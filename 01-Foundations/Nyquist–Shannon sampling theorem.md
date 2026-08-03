---
title: "Nyquist–Shannon sampling theorem"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Nyquist–Shannon_sampling_theorem"
wikipedia_categories: ["Claude Shannon", "Data compression", "Digital signal processing", "Information theory", "Mathematical theorems in theoretical computer science", "Telecommunication theory", "Theorems in Fourier analysis"]
related: ["[[Shannon–Hartley theorem]]", "[[Cheung–Marks theorem]]", "[[Information theory]]", "[[Quantization (signal processing)]]", "[[Shannon's source coding theorem]]", "[[A Mathematical Theory of Communication]]", "[[A Symbolic Analysis of Relay and Switching Circuits]]", "[[Channel capacity]]", "[[Channel state information]]", "[[Claude Shannon]]"]
---

# Nyquist–Shannon sampling theorem

The Nyquist–Shannon sampling theorem is a theorem in the field of signal processing which serves as a fundamental bridge between continuous-time signals and discrete-time signals. In the case of uniformly spaced (periodic) sampling, it establishes a sufficient condition on the sample rate that permits a discrete sequence of samples to capture all the information from a continuous-time signal of finite bandwidth, such that
the original signal can be reconstructed exactly from those samples.
Strictly speaking, the theorem only applies to a class of mathematical functions having a Fourier transform that is zero outside of a finite region of frequencies. Intuitively we expect that when one reduces a continuous function to a discrete sequence and interpolates back to a continuous function, the fidelity of the result depends on the density (or sample rate) of the original samples. The sampling theorem introduces the concept of a sample rate that is sufficient for perfect fidelity for the class of functions that are band-limited to a given bandwidth, such that no actual information is lost in the sampling process. It expresses the sufficient sample rate in terms of the bandwidth for the class of functions. The theorem also leads to a formula for perfectly reconstructing the original continuous-time function from the samples.
Perfect reconstruction may still be possible when the sample-rate criterion is not satisfied, provided other constraints on the signal are known (see § Sampling of non-baseband signals below and compressed sensing). In some cases (when the sample-rate criterion is not satisfied), utilizing additional constraints allows for approximate reconstructions. The fidelity of these reconstructions can be verified and quantified utilizing Bochner's theorem.
An important consequence of the sampling theorem is the concept of Nyquist frequency, which holds that in order to reconstruct a bandlimited signal free of aliasing, the sampling rate must be at least twice the signal's bandwidth.
The name Nyquist–Shannon sampling theorem honours Harry Nyquist and Claude Shannon, but the theorem was also previously discovered by E. T. Whittaker (published in 1915), and Shannon cited Whittaker's paper in his work. The theorem is thus also known by the names Whittaker–Shannon sampling theorem, Whittaker–Shannon, and Whittaker–Nyquist–Shannon, and may also be referred to as the cardinal theorem of interpolation.

## Related

- [[Shannon–Hartley theorem]]
- [[Cheung–Marks theorem]]
- [[Information theory]]
- [[Quantization (signal processing)]]
- [[Shannon's source coding theorem]]
- [[A Mathematical Theory of Communication]]
- [[A Symbolic Analysis of Relay and Switching Circuits]]
- [[Channel capacity]]
- [[Channel state information]]
- [[Claude Shannon]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Nyquist–Shannon_sampling_theorem