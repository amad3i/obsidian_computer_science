---
title: "Echo removal"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Echo_removal"
wikipedia_categories: ["Signal processing", "Signal processing stubs"]
related: ["[[Adjacent channel power ratio]]", "[[Audio leveler]]", "[[Bandwidth expansion]]", "[[Constant amplitude zero autocorrelation waveform]]", "[[Cross-recurrence quantification]]", "[[Decorrelation]]", "[[Delay equalization]]", "[[Direction of arrival]]", "[[Fast folding algorithm]]", "[[Half time (electronics)]]"]
---

# Echo removal

Echo removal is the process of removing echo and reverberation artifacts from audio signals. The reverberation is typically modeled as the convolution of a (sometimes time-varying) impulse response with a hypothetical clean input signal, where both the clean input signal (which is to be recovered) and the impulse response are unknown. This is an example of an inverse problem. In almost all cases, there is insufficient information in the input signal to uniquely determine a plausible original image, making it an ill-posed problem. This is generally solved by the use of a regularization term to attempt to eliminate implausible solutions.
This problem is analogous to deblurring in the image processing domain.
Adaptive filtering remains the core of almost all commercial echo cancellation systems, but modern research adds deep learning techniques.

## Related

- [[Adjacent channel power ratio]]
- [[Audio leveler]]
- [[Bandwidth expansion]]
- [[Constant amplitude zero autocorrelation waveform]]
- [[Cross-recurrence quantification]]
- [[Decorrelation]]
- [[Delay equalization]]
- [[Direction of arrival]]
- [[Fast folding algorithm]]
- [[Half time (electronics)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Echo_removal