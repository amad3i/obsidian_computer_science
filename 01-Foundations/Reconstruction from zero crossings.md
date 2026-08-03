---
title: "Reconstruction from zero crossings"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Reconstruction_from_zero_crossings"
wikipedia_categories: ["Signal processing"]
related: ["[[Adaptive beamformer]]", "[[Adjacent channel power ratio]]", "[[Algebraic signal processing]]", "[[Aliasing]]", "[[Ambiguity function]]", "[[Analog signal processing]]", "[[Analytic signal]]", "[[Angle of arrival]]", "[[Apodization]]", "[[Argument (complex analysis)]]"]
---

# Reconstruction from zero crossings

The problem of reconstruction from zero crossings can be stated as: given the zero crossings of a continuous signal, is it possible to reconstruct the signal (to within a constant factor)? Worded differently, what are the conditions under which a signal can be reconstructed from its zero crossings?
This problem has two parts. Firstly, proving that there is a unique reconstruction of the signal from the zero crossings, and secondly, how to actually go about reconstructing the signal. Though there have been quite a few attempts, no conclusive solution has yet been found. Ben Logan from Bell Labs wrote an article in 1977 in the Bell System Technical Journal giving some criteria under which unique reconstruction is possible. Though this has been a major step towards the solution, many people are dissatisfied with the type of condition that results from his article.
According to Logan, a signal is uniquely reconstructible from its zero crossings if:

The signal x(t) and its Hilbert transform xt have no zeros in common with each other.
The frequency-domain representation of the signal is at most 1 octave long, in other words, it is bandpass-limited between some frequencies B and 2B.

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

- Wikipedia: https://en.wikipedia.org/wiki/Reconstruction_from_zero_crossings