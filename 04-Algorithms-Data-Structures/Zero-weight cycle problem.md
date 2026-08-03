---
title: "Zero-weight cycle problem"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Zero-weight_cycle_problem"
wikipedia_categories: ["Graph algorithms", "NP-complete problems"]
related: ["[[Bottleneck traveling salesman problem]]", "[[Subgraph isomorphism problem]]", "[[Substructure search]]", "[[Travelling salesman problem]]", "[[Wiener connector]]", "[[1-in-3-SAT]]", "[[3-dimensional matching]]", "[[A- search algorithm]]", "[[Alpha–beta pruning]]", "[[Aperiodic graph]]"]
---

# Zero-weight cycle problem

In computer science and graph theory, the zero-weight cycle problem is the problem of deciding whether a directed graph with weights on the edges (which may be positive or negative or zero) has a cycle in which the sum of weights is 0.
A related problem is to decide whether the graph has a negative cycle, a cycle in which the sum of weights is less than 0. This related problem can be solved in polynomial time using the Bellman–Ford algorithm. If there is no negative cycle, then the distances found by the Bellman–Ford algorithm can be used, as in Johnson's algorithm, to reweight the edges of the graph in such a way that all edge weights become non-negative and all cycle lengths remain unchanged. With this reweighting, a zero-weight cycle becomes trivial to detect: it exists if and only if the zero-weight edges do not form a directed acyclic graph. Therefore, the special case of the zero-weight cycle problem, on graphs with no negative cycle, has a polynomial-time algorithm.
In contrast, for graphs that contain negative cycles, detecting a simple cycle of weight exactly 0 is an NP-complete problem. This is true even when the weights are integers of polynomial magnitude. In particular, there is a reduction from the Hamiltonian path problem, on an 
  
    
      
        n
      
    
    
  
-vertex unweighted graph 
  
    
      
        G
      
    
    
  
 with specified starting and ending vertices 
  
    
      
        s
      
    
    
  
 and 
  
    
      
        t
      
    
    
  
, to the zero-weight cycle problem on a weighted graph obtained by giving all edges of 
  
    
      
        G
      
    
    
  
 weight equal to one, and adding an additional edge from 
  
    
      
        t
      
    
    
  
 to 
  
    
      
        s
      
    
    
  
 with weight 
  
    
      
        1
        n
      
    
    
  
.

## Related

- [[Bottleneck traveling salesman problem]]
- [[Subgraph isomorphism problem]]
- [[Substructure search]]
- [[Travelling salesman problem]]
- [[Wiener connector]]
- [[1-in-3-SAT]]
- [[3-dimensional matching]]
- [[A- search algorithm]]
- [[Alpha–beta pruning]]
- [[Aperiodic graph]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Zero-weight_cycle_problem