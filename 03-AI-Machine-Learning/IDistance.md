---
title: "IDistance"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/IDistance"
wikipedia_categories: ["Classification algorithms", "Machine learning algorithms"]
related: ["[[AdaBoost]]", "[[Co-training]]", "[[Decision tree learning]]", "[[Hyper basis function network]]", "[[K-nearest neighbors algorithm]]", "[[Logic learning machine]]", "[[LogitBoost]]", "[[Support vector machine]]", "[[(1+ε)-approximate nearest neighbor search]]", "[[Actor-critic algorithm]]"]
---

# IDistance

In pattern recognition, iDistance is an indexing and query processing technique for k-nearest neighbor queries on point data in multi-dimensional metric spaces. The kNN query is one of the hardest problems on multi-dimensional data, especially when the dimensionality of the data is high. iDistance is designed to process kNN queries in high-dimensional spaces efficiently and performs extremely well for skewed data distributions, which usually occur in real-life data sets.
iDistance employs a two-phase search strategy involving an initial filtering of candidate regions and a subsequent refinement of results, an approach aligned with the  Filter and Refine Principle (FRP). This means that the index first prunes the search space to eliminate unlikely candidates, then verifies the true nearest neighbors in a refinement step, following the general FRP paradigm used in database search algorithms. The iDistance index can also be augmented with machine learning models to learn data distributions for improved searching and storage of multi-dimensional data.

## Related

- [[AdaBoost]]
- [[Co-training]]
- [[Decision tree learning]]
- [[Hyper basis function network]]
- [[K-nearest neighbors algorithm]]
- [[Logic learning machine]]
- [[LogitBoost]]
- [[Support vector machine]]
- [[(1+ε)-approximate nearest neighbor search]]
- [[Actor-critic algorithm]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/IDistance