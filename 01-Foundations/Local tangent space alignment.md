---
title: "Local tangent space alignment"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Local_tangent_space_alignment"
wikipedia_categories: ["Dimension reduction", "Manifolds", "Statistics stubs"]
related: ["[[Canonical correspondence analysis]]", "[[Generalized multidimensional scaling]]", "[[Multidimensional analysis]]", "[[Sammon mapping]]", "[[Semantic mapping (statistics)]]", "[[Tucker decomposition]]", "[[Accuracy paradox]]", "[[Aggregate pattern]]", "[[Artificial precision]]", "[[Astrostatistics]]"]
---

# Local tangent space alignment

Local tangent space alignment (LTSA) is a method for manifold learning, which can efficiently learn a nonlinear embedding into low-dimensional coordinates from high-dimensional data, and can also reconstruct high-dimensional coordinates from embedding coordinates.  It is based on the intuition that when a manifold is correctly unfolded, all of the tangent hyperplanes to the manifold will become aligned.  It begins by computing the k-nearest neighbors of every point.  It computes the tangent space at every point by computing the d-first principal components in each local neighborhood.  It then optimizes to find an embedding that aligns the tangent spaces, but it ignores the label information conveyed by data samples, and thus can not be used for classification directly.

## Related

- [[Canonical correspondence analysis]]
- [[Generalized multidimensional scaling]]
- [[Multidimensional analysis]]
- [[Sammon mapping]]
- [[Semantic mapping (statistics)]]
- [[Tucker decomposition]]
- [[Accuracy paradox]]
- [[Aggregate pattern]]
- [[Artificial precision]]
- [[Astrostatistics]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Local_tangent_space_alignment