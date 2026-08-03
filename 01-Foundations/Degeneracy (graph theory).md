---
title: "Degeneracy (graph theory)"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Degeneracy_(graph_theory)"
wikipedia_categories: ["Graph algorithms", "Graph invariants"]
related: ["[[Graph bandwidth]]", "[[A- search algorithm]]", "[[Albertson index]]", "[[Alpha–beta pruning]]", "[[Aperiodic graph]]", "[[B-]]", "[[Barabási–Albert model]]", "[[Belief propagation]]", "[[Bellman–Ford algorithm]]", "[[Bianconi–Barabási model]]"]
---

# Degeneracy (graph theory)

In graph theory, a k-degenerate graph is an undirected graph in which every non-empty subgraph has at least one vertex of degree at most 
  
    
      
        k
      
    
    
  
. That is, some vertex in the subgraph touches 
  
    
      
        k
      
    
    
  
 or fewer of the subgraph's edges. The degeneracy of a graph is the smallest value of 
  
    
      
        k
      
    
    
  
 for which it is 
  
    
      
        k
      
    
    
  
-degenerate. The degeneracy of a graph is a measure of how sparse it is, and is within a constant factor of other sparsity measures such as the arboricity of a graph.
Degeneracy is also known as the  k-core number, width, and linkage, and is essentially the same as the coloring number or Szekeres–Wilf number (named after Szekeres and  Wilf (1968)). The 
  
    
      
        k
      
    
    
  
-degenerate graphs have also been called k-inductive graphs. The degeneracy of a graph may be computed in linear time by an algorithm that repeatedly removes minimum-degree vertices. The connected components that are left after all vertices of degree less than 
  
    
      
        k
      
    
    
  
 have been (repeatedly) removed are called the k-cores of the graph and the degeneracy of a graph is the largest value 
  
    
      
        k
      
    
    
  
 such that it has a 
  
    
      
        k
      
    
    
  
-core.

## Related

- [[Graph bandwidth]]
- [[A- search algorithm]]
- [[Albertson index]]
- [[Alpha–beta pruning]]
- [[Aperiodic graph]]
- [[B-]]
- [[Barabási–Albert model]]
- [[Belief propagation]]
- [[Bellman–Ford algorithm]]
- [[Bianconi–Barabási model]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Degeneracy_(graph_theory)