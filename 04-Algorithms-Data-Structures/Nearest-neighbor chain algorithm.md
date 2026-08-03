---
title: "Nearest-neighbor chain algorithm"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Nearest-neighbor_chain_algorithm"
wikipedia_categories: ["Cluster analysis algorithms"]
related: ["[[Automatic clustering algorithms]]", "[[BIRCH]]", "[[Canopy clustering algorithm]]", "[[Cluster-weighted modeling]]", "[[Cobweb (clustering)]]", "[[Constrained clustering]]", "[[Data stream clustering]]", "[[DBSCAN]]", "[[FLAME clustering]]", "[[Fuzzy clustering]]"]
---

# Nearest-neighbor chain algorithm

In the theory of cluster analysis, the nearest-neighbor chain algorithm is an algorithm that can speed up several methods for agglomerative hierarchical clustering. These are methods that take a collection of points as input, and create a hierarchy of clusters of points by repeatedly merging pairs of smaller clusters to form larger clusters. The clustering methods that the nearest-neighbor chain algorithm can be used for include Ward's method, complete-linkage clustering, and single-linkage clustering; these all work by repeatedly merging the closest two clusters but use different definitions of the distance between clusters. The cluster distances for which the nearest-neighbor chain algorithm works are called reducible and are characterized by a simple inequality among certain cluster distances.
The main idea of the algorithm is to find pairs of clusters to merge by following paths in the nearest neighbor graph of the clusters. Every such path will eventually terminate at a pair of clusters that are nearest neighbors of each other, and the algorithm chooses that pair of clusters as the pair to merge. In order to save work by re-using as much as possible of each path, the algorithm uses a stack data structure to keep track of each path that it follows. By following paths in this way, the nearest-neighbor chain algorithm merges its clusters in a different order than methods that always find and merge the closest pair of clusters. However, despite that difference, it always generates the same hierarchy of clusters.
The nearest-neighbor chain algorithm constructs a clustering in time proportional to the square of the number of points to be clustered. This is also proportional to the size of its input, when the input is provided in the form of an explicit distance matrix. The algorithm uses an amount of memory proportional to the number of points, when it is used for clustering methods such as Ward's method that allow constant-time calculation of the distance between clusters. However, for some other clustering methods it uses a larger amount of memory in an auxiliary data structure with which it keeps track of the distances between pairs of clusters.

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

- Wikipedia: https://en.wikipedia.org/wiki/Nearest-neighbor_chain_algorithm