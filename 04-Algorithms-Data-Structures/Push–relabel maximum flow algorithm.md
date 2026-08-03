---
title: "Push–relabel maximum flow algorithm"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Push–relabel_maximum_flow_algorithm"
wikipedia_categories: ["Graph algorithms", "Network flow problem"]
related: ["[[Dinic's algorithm]]", "[[Edmonds–Karp algorithm]]", "[[Ford–Fulkerson algorithm]]", "[[Gomory–Hu tree]]", "[[Network flow problem]]", "[[Network simplex algorithm]]", "[[A- search algorithm]]", "[[Alpha–beta pruning]]", "[[Aperiodic graph]]", "[[B-]]"]
---

# Push–relabel maximum flow algorithm

In mathematical optimization, the push–relabel algorithm (alternatively, preflow–push algorithm) is an algorithm for computing maximum flows in a flow network. The name "push–relabel" comes from the two basic operations used in the algorithm. Throughout its execution, the algorithm maintains a "preflow" and gradually converts it into a maximum flow by moving flow locally between neighboring nodes using push operations under the guidance of an admissible network maintained by relabel operations. In comparison, the Ford–Fulkerson algorithm performs global augmentations that send flow following paths from the source all the way to the sink.
The push–relabel algorithm is considered one of the most efficient maximum flow algorithms. The generic algorithm has a strongly polynomial O(V 2E) time complexity, which is asymptotically more efficient than the O(VE 2) Edmonds–Karp algorithm. Specific variants of the algorithms achieve even lower time complexities. The variant based on the highest label node selection rule has O(V 2√E) time complexity and is generally regarded as the benchmark for maximum flow algorithms. Subcubic O(VElog(V 2/E)) time complexity can be achieved using dynamic trees, although in practice it is less efficient.
The push–relabel algorithm has been extended to compute minimum cost flows. The idea of distance labels has led to a more efficient augmenting path algorithm, which in turn can be incorporated back into the push–relabel algorithm to create a variant with even higher empirical performance.

## Related

- [[Dinic's algorithm]]
- [[Edmonds–Karp algorithm]]
- [[Ford–Fulkerson algorithm]]
- [[Gomory–Hu tree]]
- [[Network flow problem]]
- [[Network simplex algorithm]]
- [[A- search algorithm]]
- [[Alpha–beta pruning]]
- [[Aperiodic graph]]
- [[B-]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Push–relabel_maximum_flow_algorithm