---
title: "Single-linkage clustering"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Single-linkage_clustering"
wikipedia_categories: ["Cluster analysis algorithms"]
related: ["[[Automatic clustering algorithms]]", "[[BIRCH]]", "[[Canopy clustering algorithm]]", "[[Cluster-weighted modeling]]", "[[Cobweb (clustering)]]", "[[Constrained clustering]]", "[[Data stream clustering]]", "[[DBSCAN]]", "[[FLAME clustering]]", "[[Fuzzy clustering]]"]
---

# Single-linkage clustering

In statistics, single-linkage clustering is one of several methods of hierarchical clustering. It is based on grouping clusters in bottom-up fashion (agglomerative clustering), at each step combining two clusters that contain the closest pair of elements not yet belonging to the same cluster as each other.
This method tends to produce long thin clusters in which nearby elements of the same cluster have small distances, but elements at opposite ends of a cluster may be much farther from each other than two elements of other clusters. For some classes of data, this may lead to difficulties in defining classes that could usefully subdivide the data. However, it is popular in astronomy for analyzing galaxy clusters, which may often involve long strings of matter; in this application, it is also known as the friends-of-friends algorithm.

## Related

- [[Automatic clustering algorithms]]
- [[BIRCH]]
- [[Canopy clustering algorithm]]
- [[Cluster-weighted modeling]]
- [[Cobweb (clustering)]]
- [[Constrained clustering]]
- [[Data stream clustering]]
- [[DBSCAN]]
- [[FLAME clustering]]
- [[Fuzzy clustering]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Single-linkage_clustering