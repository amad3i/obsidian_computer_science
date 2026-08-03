---
title: "Hierarchical navigable small world"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Hierarchical_navigable_small_world"
wikipedia_categories: ["Data mining", "Database index techniques", "Graphs", "Machine learning", "Network science", "Search algorithms"]
related: ["[[Anomaly detection]]", "[[Astrostatistics]]", "[[BitFunnel]]", "[[Concept drift]]", "[[Discovery system (artificial intelligence)]]", "[[Document classification]]", "[[Feature (machine learning)]]", "[[Formal concept analysis]]", "[[Instance selection]]", "[[Inverted index]]"]
---

# Hierarchical navigable small world

Hierarchical navigable small world (HNSW) is an algorithm for approximate nearest neighbor search. It is used to find items that are similar to a query item in a large collection, without comparing the query with every item one by one.
The algorithm is commonly used for searching vector data. In these systems, an item such as a document, image, song, or user profile is represented by a list of numbers called a vector. Items with similar vectors are treated as similar according to the model that produced the vectors. HNSW provides a way to search these vectors quickly, especially in large datasets.
HNSW stores vectors in a graph. Each vector is a node, and links connect it to some nearby vectors. The graph has several layers: upper layers contain fewer nodes and act like a rough map, while the bottom layer contains all nodes and gives a more detailed view. A search starts in an upper layer, follows links toward nodes that are closer to the query, and then repeats the process in lower layers until it finds a set of likely nearest neighbors.

## Related

- [[Anomaly detection]]
- [[Astrostatistics]]
- [[BitFunnel]]
- [[Concept drift]]
- [[Discovery system (artificial intelligence)]]
- [[Document classification]]
- [[Feature (machine learning)]]
- [[Formal concept analysis]]
- [[Instance selection]]
- [[Inverted index]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Hierarchical_navigable_small_world