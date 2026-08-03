---
title: "Rand index"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Rand_index"
wikipedia_categories: ["Clustering criteria", "Summary statistics for contingency tables"]
related: ["[[Adjusted mutual information]]", "[[Automatic clustering algorithms]]", "[[Balanced clustering]]", "[[Davies–Bouldin index]]", "[[Determining the number of clusters in a data set]]", "[[Dunn index]]", "[[Elbow method (clustering)]]", "[[Fowlkes–Mallows index]]", "[[Hopkins statistic]]", "[[Jaccard index]]"]
---

# Rand index

The Rand index or Rand measure (named after William M. Rand) in statistics, and in particular in data clustering, is a similarity measure between two clusterings. It compares all pairs of elements and counts how often the two clusterings agree: either both place a pair in the same cluster, or both place the pair in different clusters. The Rand index has a value between 0 and 1, with 0 indicating that the two data clusterings do not agree on any pair of points and 1 indicating that the data clusterings are exactly the same.
The adjusted Rand index (ARI) is a version of the Rand index corrected for the similarity expected by chance. It is commonly used to compare a clustering algorithm's output with a reference clustering, such as known class labels or a ground-truth partition.

## Related

- [[Adjusted mutual information]]
- [[Automatic clustering algorithms]]
- [[Balanced clustering]]
- [[Davies–Bouldin index]]
- [[Determining the number of clusters in a data set]]
- [[Dunn index]]
- [[Elbow method (clustering)]]
- [[Fowlkes–Mallows index]]
- [[Hopkins statistic]]
- [[Jaccard index]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Rand_index