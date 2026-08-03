---
title: "OPTICS algorithm"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/OPTICS_algorithm"
wikipedia_categories: ["Cluster analysis algorithms"]
related: ["[[Automatic clustering algorithms]]", "[[BIRCH]]", "[[Canopy clustering algorithm]]", "[[Cluster-weighted modeling]]", "[[Cobweb (clustering)]]", "[[Constrained clustering]]", "[[Data stream clustering]]", "[[DBSCAN]]", "[[FLAME clustering]]", "[[Fuzzy clustering]]"]
---

# OPTICS algorithm

Ordering points to identify the clustering structure (OPTICS) is an algorithm for finding density-based clusters in spatial data. It was presented in 1999 by Mihael Ankerst, Markus M. Breunig, Hans-Peter Kriegel and Jörg Sander.
Its basic idea is similar to DBSCAN, but it addresses one of DBSCAN's major weaknesses: the problem of detecting meaningful clusters in data of varying density. To do so, the points of the database are (linearly) ordered such that spatially closest points become neighbors in the ordering. Additionally, a special distance is stored for each point that represents the density that must be accepted for a cluster so that both points belong to the same cluster. This is represented as a dendrogram.

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

- Wikipedia: https://en.wikipedia.org/wiki/OPTICS_algorithm