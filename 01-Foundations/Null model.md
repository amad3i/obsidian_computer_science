---
title: "Null model"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Null_model"
wikipedia_categories: ["Graph theory", "Graph theory stubs", "Statistical methods"]
related: ["[[Convex subgraph]]", "[[Corona product]]", "[[Cycle decomposition (graph theory)]]", "[[Homomorphic equivalence]]", "[[Nullity (graph theory)]]", "[[Simplicial vertex]]", "[[Albertson index]]", "[[Bicircular matroid]]", "[[Bristol Bridges Walk]]", "[[Capacitated arc routing problem]]"]
---

# Null model

In mathematics, for example in the study of statistical properties of graphs, a null model is a type of random object that matches one specific object in some of its features, or more generally satisfies a collection of constraints, but which is otherwise taken to be an unbiasedly random structure. The null model is used as a term of comparison, to verify whether the object in question displays some non-trivial features (properties that wouldn't be expected on the basis of chance alone or as a consequence of the constraints), such as community structure in graphs. An appropriate null model behaves in accordance with a reasonable null hypothesis for the behavior of the system under investigation.
One null model of utility in the study of complex networks is that proposed by Newman and Girvan, consisting of a randomized version of an original graph 
  
    
      
        G
      
    
    
  
, produced through edges being rewired at random, under the constraint that the expected degree of each vertex matches the degree of the vertex in the original graph.
The null model is the basic concept behind the definition of modularity, a function which evaluates the goodness of partitions of a graph into clusters. In particular, given a graph 
  
    
      
        G
      
    
    
  
 and a specific community partition 
  
    
      
        σ
        :
        V
        G
        →
        1
        ,
        .
        .
        .
        ,
        b
      
    
    
  
 (an assignment of a community-index 
  
    
      
        σ
        v
      
    
    
  
 (here taken as an integer from 
  
    
      
        1
      
    
    
  
 to 
  
    
      
        b
      
    
    
  
) to each vertex 
  
    
      
        v
        ∈
        V
        G
      
    
    
  
 in the graph), the modularity measures the difference between the number of links from/to each pair of communities, from that expected in a graph that is completely random in all respects other than the set of degrees of each of the vertices (the degree sequence). In other words, the modularity contrasts the exhibited community structure in 
  
    
      
        G
      
    
    
  
 with that of a null model, which in this case is the configuration model (the maximally random graph subject to a constraint on the degree of each vertex).

## Related

- [[Convex subgraph]]
- [[Corona product]]
- [[Cycle decomposition (graph theory)]]
- [[Homomorphic equivalence]]
- [[Nullity (graph theory)]]
- [[Simplicial vertex]]
- [[Albertson index]]
- [[Bicircular matroid]]
- [[Bristol Bridges Walk]]
- [[Capacitated arc routing problem]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Null_model