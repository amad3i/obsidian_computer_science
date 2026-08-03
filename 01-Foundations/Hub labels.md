---
title: "Hub labels"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Hub_labels"
wikipedia_categories: ["Graph algorithms", "Mathematical logic", "Theoretical computer science"]
related: ["[[Knuth's Simpath algorithm]]", "[[Algorithm]]", "[[Algorithmic technique]]", "[[Institutional model theory]]", "[[Recursive definition]]", "[[Regular numerical predicate]]", "[[A- search algorithm]]", "[[Absoluteness (logic)]]", "[[Abstract logic]]", "[[Abstract model theory]]"]
---

# Hub labels

In computer science, hub labels or the hub-labelling algorithm is a speedup technique that consumes much fewer resources than the lookup table but is still extremely fast for finding the shortest paths between nodes in a graph, which may represent, for example, road networks.
This method allows at the most with two SELECT statements and the analysis of two strings to compute the shortest path between two vertices of a graph.
For a graph that is oriented like a road graph, this technique requires the prior computation of two tables from structures constructed using the method of the contraction hierarchies. 
In the end, these two computed tables will have as many rows as nodes present within the graph. For each row (each node), a label will be calculated.
A label is a string containing the distance information between the current node (the node of the row) and all the other nodes that can be reached with an ascending search on the relative multi-level structure. The advantage of these distances is that they all represent the shortest paths. 
So, for future queries, the search of a shortest path will start from the source on the first table and the destination on the second table, from which it will search within the labels for the common nodes with the associated distance information. Only the smallest sum of distances will be kept as the shortest path result.

## Related

- [[Knuth's Simpath algorithm]]
- [[Algorithm]]
- [[Algorithmic technique]]
- [[Institutional model theory]]
- [[Recursive definition]]
- [[Regular numerical predicate]]
- [[A- search algorithm]]
- [[Absoluteness (logic)]]
- [[Abstract logic]]
- [[Abstract model theory]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Hub_labels