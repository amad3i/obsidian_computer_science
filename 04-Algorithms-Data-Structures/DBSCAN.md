---
title: "DBSCAN"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/DBSCAN"
wikipedia_categories: ["Cluster analysis algorithms"]
related: ["[[Automatic clustering algorithms]]", "[[BIRCH]]", "[[Canopy clustering algorithm]]", "[[Cluster-weighted modeling]]", "[[Cobweb (clustering)]]", "[[Constrained clustering]]", "[[Data stream clustering]]", "[[FLAME clustering]]", "[[Fuzzy clustering]]", "[[Hierarchical clustering]]"]
---

# DBSCAN

Density-based spatial clustering of applications with noise (DBSCAN) is a data clustering algorithm proposed by Martin Ester, Hans-Peter Kriegel, Jörg Sander, and Xiaowei Xu in 1996.
It is a density-based clustering algorithm that does not assume a fixed parametric model for the clusters, such as Gaussian blobs, and it does not require the number of clusters to be specified in advance. Given a set of points in some space, it groups together points that are closely packed (points with many nearby neighbors), and marks as outliers points that lie alone in low-density regions (those whose nearest neighbors are too far away).
DBSCAN is one of the most commonly used and cited clustering algorithms.
In 2014, the algorithm was awarded the Test of Time Award (an award given to algorithms which have received substantial attention in theory and practice) at the leading data mining conference, ACM SIGKDD. As of July 2020, the follow-up paper "DBSCAN Revisited, Revisited: Why and How You Should (Still) Use DBSCAN" appears in the list of the 8 most downloaded articles of the prestigious ACM Transactions on Database Systems (TODS) journal.
Another follow-up, HDBSCAN*, was initially published by Ricardo J. G. Campello, David Moulavi, and Jörg Sander in 2013, then expanded upon with Arthur Zimek in 2015. It revises some of the original decisions such as the border points, and produces a hierarchical instead of a flat result.

## Related

- [[Automatic clustering algorithms]]
- [[BIRCH]]
- [[Canopy clustering algorithm]]
- [[Cluster-weighted modeling]]
- [[Cobweb (clustering)]]
- [[Constrained clustering]]
- [[Data stream clustering]]
- [[FLAME clustering]]
- [[Fuzzy clustering]]
- [[Hierarchical clustering]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/DBSCAN