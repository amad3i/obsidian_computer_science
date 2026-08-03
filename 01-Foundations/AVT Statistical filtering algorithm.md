---
title: "AVT Statistical filtering algorithm"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/AVT_Statistical_filtering_algorithm"
wikipedia_categories: ["Algorithms"]
related: ["[[Adaptive algorithm]]", "[[Algorism]]", "[[Algorithm]]", "[[Algorithm characterizations]]", "[[Algorithm engineering]]", "[[Algorithm IMED]]", "[[Algorithmic amplification]]", "[[Algorithmic logic]]", "[[Algorithmic management]]", "[[Algorithmic mechanism design]]"]
---

# AVT Statistical filtering algorithm

AVT Statistical filtering algorithm is an approach to improving quality of raw data collected from various sources. It is most effective in cases when there is inband noise present. In those cases AVT is better at filtering data then, band-pass filter or any digital filtering based on variation of.
Conventional filtering is useful when signal/data has different frequency than noise and signal/data is separated/filtered by frequency discrimination of noise. Frequency discrimination filtering is done using Low Pass, High Pass and Band Pass filtering which refers to relative frequency filtering criteria target for such configuration. Those filters are created using passive and active components and sometimes are implemented using software algorithms based on Fast Fourier transform (FFT).
AVT filtering is implemented in software and its inner working is based on statistical analysis of raw data.
When signal frequency/(useful data distribution frequency) coincides with noise frequency/(noisy data distribution frequency) we have inband noise. In this situations frequency discrimination filtering does not work since the noise and useful signal are indistinguishable and where AVT excels. To achieve filtering in such conditions there are several methods/algorithms available which are briefly described below.

## Related

- [[Adaptive algorithm]]
- [[Algorism]]
- [[Algorithm]]
- [[Algorithm characterizations]]
- [[Algorithm engineering]]
- [[Algorithm IMED]]
- [[Algorithmic amplification]]
- [[Algorithmic logic]]
- [[Algorithmic management]]
- [[Algorithmic mechanism design]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/AVT_Statistical_filtering_algorithm