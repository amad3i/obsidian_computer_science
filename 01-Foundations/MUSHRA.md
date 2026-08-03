---
title: "MUSHRA"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/MUSHRA"
wikipedia_categories: ["ITU-R recommendations", "Psychophysics", "Signal processing"]
related: ["[[Detection theory]]", "[[Adaptive beamformer]]", "[[Adjacent channel power ratio]]", "[[Algebraic signal processing]]", "[[Aliasing]]", "[[Ambiguity function]]", "[[Analog signal processing]]", "[[Analytic signal]]", "[[Angle of arrival]]", "[[Apodization]]"]
---

# MUSHRA

MUSHRA stands for Multiple Stimuli with Hidden Reference and Anchor and is a methodology for conducting a codec listening test to evaluate the perceived quality of the output from lossy audio compression algorithms. It is defined by ITU-R recommendation BS.1534-3. The MUSHRA methodology is recommended for assessing "intermediate audio quality". For very small or sensitive audio impairments, Recommendation ITU-R BS.1116-3 (ABC/HR) is recommended instead.
MUSHRA can be used to test audio codecs across a broad spectrum of use cases: music and film consumption, speech for e.g. podcasts and radio, online streaming (in which trade-offs between quality and efficiency of size and computation are paramount), modern digital telephony, and VOIP applications (which require quasi-real-time, low-bitrate encoding that remains intelligible). Professional, "audiophile", and "prosumer" uses are typically better suited to alternative tests, like the aforementioned ABC/HR, with a base assumption of high-quality, high-resolution audio wherein there will be minimal detectable differences between reference material and the codec output.
The main advantage over the mean opinion score (MOS) methodology (which serves a similar purpose) is that MUSHRA requires fewer participants to obtain statistically significant results. This is because all codecs are presented at the same time, to the same participants, such that a paired t-test or repeated measures analysis of variance can be used for statistical analysis. Furthermore, the 0–100 scale used by MUSHRA makes it possible to express perceptible differences with a high degree of granularity, especially compared to the 0-5 modified Likert scale often used by MOS experiments.
In MUSHRA, the listener is presented with the reference (labeled as such), a certain number of test samples, a hidden version of the reference, and one or more anchors (i.e. severely impaired encodings that both the experimenters and participants are supposed to immediately recognise as such; used similarly to the reference to provide a baseline demonstrating - "anchoring" - for participants the actuality of the low end of the quality scale). The recommendation specifies that a low-range and a mid-range anchor should be included in the test signals. These are typically a 7 kHz and a 3.5 kHz low-pass version of the reference. The purpose of the anchors is to calibrate the scale so that minor artifacts are not unduly penalized. This is particularly important when comparing or pooling results from different labs.

## Related

- [[Detection theory]]
- [[Adaptive beamformer]]
- [[Adjacent channel power ratio]]
- [[Algebraic signal processing]]
- [[Aliasing]]
- [[Ambiguity function]]
- [[Analog signal processing]]
- [[Analytic signal]]
- [[Angle of arrival]]
- [[Apodization]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/MUSHRA