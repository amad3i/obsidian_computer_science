---
title: "Silhouette (clustering)"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Silhouette_(clustering)"
wikipedia_categories: ["Cluster analysis", "Clustering criteria", "Statistical methods"]
related: ["[[Determining the number of clusters in a data set]]", "[[Adjusted mutual information]]", "[[Archetypal analysis]]", "[[Automatic clustering algorithms]]", "[[Balanced clustering]]", "[[Behavioral clustering]]", "[[Biclustering]]", "[[Brown clustering]]", "[[Cluster analysis]]", "[[Clustering high-dimensional data]]"]
---

# Silhouette (clustering)

Silhouette is a method of interpretation and validation of consistency within clusters of data. The technique provides a succinct graphical representation of how well each object has been classified. It was proposed by Belgian statistician Peter Rousseeuw in 1987.
The silhouette value is a measure of how similar an object is to its own cluster (cohesion) compared to other clusters (separation). The silhouette value ranges from −1 to +1, where a high value indicates that the object is well matched to its own cluster and poorly matched to neighboring clusters. If most objects have a high value, then the clustering configuration is appropriate. If many points have a low or negative value, then the clustering configuration may have too many or too few clusters. A clustering with an average silhouette width of over 0.7 is considered to be "strong", a value over 0.5 "reasonable", and over 0.25 "weak". However, with an increasing dimensionality of the data, it becomes difficult to achieve such high values because of the curse of dimensionality, as the distances become more similar.  The silhouette score is specialized for measuring cluster quality when the clusters are convex-shaped, and may not perform well if the data clusters have irregular shapes or are of varying sizes. The silhouette value can be calculated with any distance metric, such as Euclidean distance or Manhattan distance.

## Related

- [[Determining the number of clusters in a data set]]
- [[Adjusted mutual information]]
- [[Archetypal analysis]]
- [[Automatic clustering algorithms]]
- [[Balanced clustering]]
- [[Behavioral clustering]]
- [[Biclustering]]
- [[Brown clustering]]
- [[Cluster analysis]]
- [[Clustering high-dimensional data]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Silhouette_(clustering)