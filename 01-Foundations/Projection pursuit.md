---
title: "Projection pursuit"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Projection_pursuit"
wikipedia_categories: ["Exploratory data analysis", "Multivariate statistics"]
related: ["[[Cluster-weighted modeling]]", "[[Geometric median]]", "[[Hajek projection]]", "[[High-dimensional statistics]]", "[[Information bottleneck method]]", "[[Least-squares spectral analysis]]", "[[Matching pursuit]]"]
---

# Projection pursuit

Projection pursuit (PP) is a type of statistical technique that involves finding the most "interesting" possible projections in multidimensional data. Often, projections that deviate more from a normal distribution are considered to be more interesting.  As each projection is found, the data are reduced by removing the component along that projection, and the process is repeated to find new projections; this is the "pursuit" aspect that motivated the technique known as matching pursuit.
The idea of projection pursuit is to locate the projection or projections from high-dimensional space to low-dimensional space that reveal the most details about the structure of the data set. Once an interesting set of projections has been found, existing structures (clusters, surfaces, etc.) can be extracted and analyzed separately.
Projection pursuit has been widely used for blind source separation, so it is very important in independent component analysis. Projection pursuit seeks one projection at a time such that the extracted signal is as non-Gaussian as possible.

## Related

- [[Cluster-weighted modeling]]
- [[Geometric median]]
- [[Hajek projection]]
- [[High-dimensional statistics]]
- [[Information bottleneck method]]
- [[Least-squares spectral analysis]]
- [[Matching pursuit]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Projection_pursuit