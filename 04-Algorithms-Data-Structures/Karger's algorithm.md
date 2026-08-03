---
title: "Karger's algorithm"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Karger's_algorithm"
wikipedia_categories: ["Graph algorithms", "Graph connectivity"]
related: ["[[Kosaraju's algorithm]]", "[[Path-based strong component algorithm]]", "[[Stoer–Wagner algorithm]]", "[[Tarjan's strongly connected components algorithm]]", "[[A- search algorithm]]", "[[Alpha–beta pruning]]", "[[Aperiodic graph]]", "[[B-]]", "[[Barabási–Albert model]]", "[[Belief propagation]]"]
---

# Karger's algorithm

In computer science and graph theory, Karger's algorithm is a randomized algorithm to compute a minimum cut of a connected graph. It was invented by David Karger and first published in 1993.
The idea of the algorithm is based on the concept of contraction of an edge 
  
    
      
        u
        ,
        v
      
    
    
  
 in an undirected graph 
  
    
      
        G
        (
        V
        ,
        E
      
    
    
  
. Informally, the contraction of an edge merges the nodes 
  
    
      
        u
      
    
    
  
 and 
  
    
      
        v
      
    
    
  
 into one, reducing the total number of nodes of the graph by one. All other edges connecting either 
  
    
      
        u
      
    
    
  
 or 
  
    
      
        v
      
    
    
  
 are "reattached" to the merged node, effectively producing a multigraph. Karger's basic algorithm iteratively contracts randomly chosen edges until only two nodes remain; those nodes represent a cut in the original graph. By iterating this basic algorithm a sufficient number of times, a minimum cut can be found with high probability.

## Related

- [[Kosaraju's algorithm]]
- [[Path-based strong component algorithm]]
- [[Stoer–Wagner algorithm]]
- [[Tarjan's strongly connected components algorithm]]
- [[A- search algorithm]]
- [[Alpha–beta pruning]]
- [[Aperiodic graph]]
- [[B-]]
- [[Barabási–Albert model]]
- [[Belief propagation]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Karger's_algorithm