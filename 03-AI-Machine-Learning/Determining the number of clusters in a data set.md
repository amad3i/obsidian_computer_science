---
title: "Determining the number of clusters in a data set"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Determining_the_number_of_clusters_in_a_data_set"
wikipedia_categories: ["Cluster analysis", "Clustering criteria"]
related: ["[[Silhouette (clustering)]]", "[[Adjusted mutual information]]", "[[Archetypal analysis]]", "[[Automatic clustering algorithms]]", "[[Balanced clustering]]", "[[Behavioral clustering]]", "[[Biclustering]]", "[[Brown clustering]]", "[[Cluster analysis]]", "[[Clustering high-dimensional data]]"]
---

# Determining the number of clusters in a data set

Determining the number of clusters in a data set, a quantity often labelled k as in the k-means algorithm, is a frequent problem in data clustering, and is a distinct issue from the process of actually solving the clustering problem.
For a certain class of clustering algorithms (in particular k-means, k-medoids and expectation–maximization algorithm), there is a parameter commonly referred to as k that specifies the number of clusters to detect. Other algorithms such as DBSCAN and OPTICS algorithm do not require the specification of this parameter; hierarchical clustering avoids the problem altogether.
The correct choice of k is often ambiguous, with interpretations depending on the shape and scale of the distribution of points in a data set and the desired clustering resolution of the user. In addition, increasing k without penalty will always reduce the amount of error in the resulting clustering, to the extreme case of zero error if each data point is considered its own cluster (i.e., when k equals the number of data points, n). Intuitively then, the optimal choice of k will strike a balance between maximum compression of the data using a single cluster, and maximum accuracy by assigning each data point to its own cluster. If an appropriate value of k is not apparent from prior knowledge of the properties of the data set, it must be chosen somehow. There are several categories of methods for making this decision.

## Related

- [[Silhouette (clustering)]]
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

- Wikipedia: https://en.wikipedia.org/wiki/Determining_the_number_of_clusters_in_a_data_set