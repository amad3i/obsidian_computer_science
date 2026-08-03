---
title: "Signal subspace"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Signal_subspace"
wikipedia_categories: ["Noise reduction", "Signal processing"]
related: ["[[Adaptive beamformer]]", "[[Adjacent channel power ratio]]", "[[Algebraic signal processing]]", "[[Aliasing]]", "[[Ambiguity function]]", "[[Analog signal processing]]", "[[Analytic signal]]", "[[Angle of arrival]]", "[[Apodization]]", "[[Argument (complex analysis)]]"]
---

# Signal subspace

In signal processing, signal subspace methods are empirical linear methods for dimensionality reduction and noise reduction. These approaches have attracted significant interest and investigation recently in the context of speech enhancement, speech modeling, and speech classification research. The signal subspace is also used in radio direction finding using the MUSIC (algorithm).
Essentially the methods represent the application of a principal components analysis (PCA) approach to ensembles of observed time-series obtained by sampling, for example sampling an audio signal. Such samples can be viewed as vectors in a high-dimensional vector space over the real numbers. PCA is used to identify a set of orthogonal basis vectors (basis signals) which capture as much as possible of the energy in the ensemble of observed samples. The vector space spanned by the basis vectors identified by the analysis is then the signal subspace. The underlying assumption is that information in speech signals is almost completely contained in a small linear subspace of the overall space of possible sample vectors, whereas additive noise is typically distributed through the larger space isotropically (for example when it is white noise).
By projecting a sample on a signal subspace, that is, keeping only the component of the sample that is in the signal subspace defined by linear combinations of the first few most energized basis vectors, and throwing away the rest of the sample, which is in the remainder of the space orthogonal to this subspace, a certain amount of noise filtering is then obtained.
Signal subspace noise-reduction can be compared to Wiener filter methods. There are two main differences:

The basis signals used in Wiener filtering are usually harmonic sine waves, into which a signal can be decomposed by Fourier transform. In contrast, the basis signals used to construct the signal subspace are identified empirically, and may for example be chirps, or particular characteristic shapes of transients after particular triggering events, rather than pure sinusoids.
The Wiener filter grades smoothly between linear components that are dominated by signal, and linear components that are dominated by noise. The noise components are filtered out, but not quite completely; the signal components are retained, but not quite completely; and there is a transition zone which is partly accepted. In contrast, the signal subspace approach represents a sharp cut-off: an orthogonal component either lies within the signal subspace, in which case it is 100% accepted, or orthogonal to it, in which case it is 100% rejected. This reduction in dimensionality, abstracting the signal into a much shorter vector, can be a particularly desired feature of the method.
In the simplest case signal subspace methods assume white noise, but extensions of the approach to colored noise removal and the evaluation of the subspace-based speech enhancement for robust speech recognition have also been reported.

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

- Wikipedia: https://en.wikipedia.org/wiki/Signal_subspace