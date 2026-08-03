---
title: "Medoid"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Medoid"
wikipedia_categories: ["Cluster analysis", "Means"]
related: ["[[Archetypal analysis]]", "[[Behavioral clustering]]", "[[Biclustering]]", "[[Brown clustering]]", "[[Cluster analysis]]", "[[Clustering high-dimensional data]]", "[[Clustering illusion]]", "[[Composite portrait]]", "[[Consensus clustering]]", "[[Constrained clustering]]"]
---

# Medoid

Medoids are representative objects of a data set or a cluster within a data set whose sum of dissimilarities to all the objects in the cluster is minimal. Medoids are similar in concept to means or centroids, but medoids are always restricted to be members of the data set. Medoids are most commonly used on data when a mean or centroid cannot be defined, such as graphs. They are also used in contexts where the centroid is not representative of the dataset like in images, 3-D trajectories and  gene expression (where while the data is sparse the medoid need not be).  These are also of interest while wanting to find a representative using some distance other than squared euclidean distance (for instance in movie-ratings).
For some data sets there may be more than one medoid, as with medians.
A common application of the medoid is the k-medoids clustering algorithm, which is similar to the k-means algorithm but works when a mean or centroid is not definable. This algorithm basically works as follows. First, a set of medoids is chosen at random. Second, the distances to the other points are computed. Third, data are clustered according to the medoid they are most similar to. Fourth, the medoid set is optimized via an iterative process.
Note that a medoid is not equivalent to a median, a geometric median, or centroid. A median is only defined on 1-dimensional data, and it only minimizes dissimilarity to other points for metrics induced by a norm (such as the Manhattan distance or Euclidean distance). A geometric median is defined in any dimension, but unlike a medoid, it is not necessarily a point from within the original dataset.

## Related

- [[Archetypal analysis]]
- [[Behavioral clustering]]
- [[Biclustering]]
- [[Brown clustering]]
- [[Cluster analysis]]
- [[Clustering high-dimensional data]]
- [[Clustering illusion]]
- [[Composite portrait]]
- [[Consensus clustering]]
- [[Constrained clustering]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Medoid