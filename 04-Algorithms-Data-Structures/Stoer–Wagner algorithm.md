---
title: "Stoer–Wagner algorithm"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Stoer–Wagner_algorithm"
wikipedia_categories: ["Graph algorithms", "Graph connectivity"]
related: ["[[Karger's algorithm]]", "[[Kosaraju's algorithm]]", "[[Path-based strong component algorithm]]", "[[Tarjan's strongly connected components algorithm]]", "[[A- search algorithm]]", "[[Alpha–beta pruning]]", "[[Aperiodic graph]]", "[[B-]]", "[[Barabási–Albert model]]", "[[Belief propagation]]"]
---

# Stoer–Wagner algorithm

In graph theory, the Stoer–Wagner algorithm is a recursive algorithm to solve the minimum cut problem in undirected weighted graphs with non-negative weights. It was proposed by Mechthild Stoer and Frank Wagner in 1995. The essential idea of this algorithm is to shrink the graph by merging the most intensive vertices, until the graph only contains two combined vertex sets. At each phase, the algorithm finds the minimum 
  
    
      
        s
      
    
    
  
-
  
    
      
        t
      
    
    
  
 cut for two vertices 
  
    
      
        s
      
    
    
  
 and 
  
    
      
        t
      
    
    
  
 chosen at its will. Then the algorithm shrinks the edge between 
  
    
      
        s
      
    
    
  
 and 
  
    
      
        t
      
    
    
  
 to search for non 
  
    
      
        s
      
    
    
  
-
  
    
      
        t
      
    
    
  
 cuts. The minimum cut found in all phases will be the minimum weighted cut of the graph.
A cut is a partition of the vertices of a graph into two non-empty, disjoint subsets. A minimum cut is a cut for which the size or weight of the cut is not larger than the size of any other cut. For an unweighted graph, the minimum cut would simply be the cut with the least edges. For a weighted graph, the sum of all edges' weight on the cut determines whether it is a minimum cut. In practice, the minimum cut problem is always discussed with the maximum flow problem, to explore the maximum capacity of a network, since the minimum cut is a bottleneck in a graph or network.

## Related

- [[Karger's algorithm]]
- [[Kosaraju's algorithm]]
- [[Path-based strong component algorithm]]
- [[Tarjan's strongly connected components algorithm]]
- [[A- search algorithm]]
- [[Alpha–beta pruning]]
- [[Aperiodic graph]]
- [[B-]]
- [[Barabási–Albert model]]
- [[Belief propagation]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Stoer–Wagner_algorithm