---
title: "Blossom algorithm"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Blossom_algorithm"
wikipedia_categories: ["Graph algorithms", "Matching (graph theory)"]
related: ["[[Dulmage–Mendelsohn decomposition]]", "[[Gallai–Edmonds decomposition]]", "[[Hall-type theorems for hypergraphs]]", "[[Hopcroft–Karp algorithm]]", "[[3-dimensional matching]]", "[[A- search algorithm]]", "[[Alpha–beta pruning]]", "[[Aperiodic graph]]", "[[B-]]", "[[Barabási–Albert model]]"]
---

# Blossom algorithm

In graph theory, the blossom algorithm is an algorithm for constructing maximum matchings on graphs. The algorithm was developed by Jack Edmonds in 1961, and published in 1965. Given a general graph G = (V, E), the algorithm finds a matching M such that each vertex in V is incident with at most one edge in M and |M| is maximized. The matching is constructed by iteratively improving an initial empty matching along augmenting paths in the graph. Unlike bipartite matching, the key new idea is that an odd-length cycle in the graph (blossom) is contracted to a single vertex, with the search continuing iteratively in the contracted graph.
The algorithm runs in time O(|E||V|2), where |E| is the number of edges of the graph and |V| is its number of vertices. A better running time of 
  
    
      
        O
        
          |
        
        E
        
          |
        
        
          
            
              |
            
            V
            
              |
            
          
        
      
    
    
  
 for the same task can be achieved with the more complicated algorithm of Micali and Vazirani.
A major reason that the blossom algorithm is important is that it gave the first proof that a maximum-size matching could be found using a polynomial amount of computation time. Another reason is that it led to a linear programming polyhedral description of the matching polytope, yielding an algorithm for min-weight matching. 
As elaborated by Alexander Schrijver, further significance of the result comes from the fact that this was the first polytope whose proof of integrality "does not simply follow just from total unimodularity, and its description was a breakthrough in polyhedral combinatorics."

## Related

- [[Dulmage–Mendelsohn decomposition]]
- [[Gallai–Edmonds decomposition]]
- [[Hall-type theorems for hypergraphs]]
- [[Hopcroft–Karp algorithm]]
- [[3-dimensional matching]]
- [[A- search algorithm]]
- [[Alpha–beta pruning]]
- [[Aperiodic graph]]
- [[B-]]
- [[Barabási–Albert model]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Blossom_algorithm