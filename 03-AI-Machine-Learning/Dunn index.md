---
title: "Dunn index"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Dunn_index"
wikipedia_categories: ["Clustering criteria"]
related: ["[[Adjusted mutual information]]", "[[Automatic clustering algorithms]]", "[[Balanced clustering]]", "[[Davies–Bouldin index]]", "[[Determining the number of clusters in a data set]]", "[[Elbow method (clustering)]]", "[[Fowlkes–Mallows index]]", "[[Hopkins statistic]]", "[[Jaccard index]]", "[[MinHash]]"]
---

# Dunn index

The Dunn index, introduced by Joseph C. Dunn in 1974, is a metric for evaluating clustering algorithms. This is part of a group of validity indices including the Davies–Bouldin index or Silhouette index, in that it is an internal evaluation scheme, where the result is based on the clustered data itself. As do all other such indices, the aim is to identify sets of clusters that are compact, with a small variance between members of the cluster, and well separated, where the means of different clusters are sufficiently far apart, as compared to the within cluster variance. For a given assignment of clusters, a higher Dunn index indicates better clustering. One of the drawbacks of using this is the computational cost as the number of clusters and dimensionality of the data increase.
A scientific article published in 2025 claimed that the Dunn index can be less informative than Silhouette coefficient and the Davies-Bouldin index when used to assess convex-shaped clusters.

## Related

- [[Adjusted mutual information]]
- [[Automatic clustering algorithms]]
- [[Balanced clustering]]
- [[Davies–Bouldin index]]
- [[Determining the number of clusters in a data set]]
- [[Elbow method (clustering)]]
- [[Fowlkes–Mallows index]]
- [[Hopkins statistic]]
- [[Jaccard index]]
- [[MinHash]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Dunn_index