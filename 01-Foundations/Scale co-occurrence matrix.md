---
title: "Scale co-occurrence matrix"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Scale_co-occurrence_matrix"
wikipedia_categories: ["Feature detection (computer vision)", "Image compression", "Image processing software", "Numerical analysis", "Wavelets"]
related: ["[[Discrete wavelet transform]]", "[[Multigrid method]]", "[[Progressive Graphics File]]", "[[Transfer matrix]]", "[[Wavelet transform]]", "[[2Sum]]", "[[Abramowitz and Stegun]]", "[[Adaptive step size]]", "[[Adjoint state method]]", "[[Affine arithmetic]]"]
---

# Scale co-occurrence matrix

Scale co-occurrence matrix (SCM) is a method for image feature extraction within scale space after wavelet transformation, proposed by Wu Jun and Zhao Zhongming (Institute of Remote Sensing Application, China). In practice, we first do discrete wavelet transformation for one gray image and get sub images with different scales. Then we construct a series of scale based concurrent matrices, every matrix describing the gray level variation between two adjacent scales. Last we use selected functions (such as Harris statistical approach) to calculate measurements with SCM and do feature extraction and classification. 
One basis of the method is the fact: way texture information changes from one scale to another can represent that texture in some extent thus it can be used as a criterion for feature extraction. The matrix captures the relation of features between different scales rather than the features within a single scale space, which can represent the scale property of texture better. Also, there are several experiments showing that it can get more accurate results for texture classification than the traditional texture classification.

## Related

- [[Discrete wavelet transform]]
- [[Multigrid method]]
- [[Progressive Graphics File]]
- [[Transfer matrix]]
- [[Wavelet transform]]
- [[2Sum]]
- [[Abramowitz and Stegun]]
- [[Adaptive step size]]
- [[Adjoint state method]]
- [[Affine arithmetic]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Scale_co-occurrence_matrix