---
title: "Lanczos resampling"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Lanczos_resampling"
wikipedia_categories: ["Multivariate interpolation", "Signal processing"]
related: ["[[Adaptive beamformer]]", "[[Adjacent channel power ratio]]", "[[Algebraic signal processing]]", "[[Aliasing]]", "[[Ambiguity function]]", "[[Analog signal processing]]", "[[Analytic signal]]", "[[Angle of arrival]]", "[[Apodization]]", "[[Argument (complex analysis)]]"]
---

# Lanczos resampling

Lanczos filtering and Lanczos resampling are two applications of a certain mathematical formula. It can be used as a low-pass filter or used to smoothly interpolate the value of a digital signal between its samples.  In the latter case, it maps each sample of the given signal to a translated and scaled copy of the Lanczos kernel, which is a sinc function windowed by the central lobe of a second, longer, sinc function.  The sum of these translated and scaled kernels is then evaluated at the desired points.
Lanczos resampling is typically used to increase the sampling rate of a digital signal, or to shift it by a fraction of the sampling interval.  It is often used also for multivariate interpolation, for example to resize or rotate a digital image.  It has been considered the "best compromise" among several simple filters for this purpose.
The filter was invented by Claude Duchon, who named it after Cornelius Lanczos due to Duchon's use of the sigma approximation in constructing the filter, a technique created by Lanczos.

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

- Wikipedia: https://en.wikipedia.org/wiki/Lanczos_resampling