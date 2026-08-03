---
title: "Logic of graphs"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Logic_of_graphs"
wikipedia_categories: ["Finite model theory", "Graph theory"]
related: ["[[Albertson index]]", "[[Bicircular matroid]]", "[[Bristol Bridges Walk]]", "[[Capacitated arc routing problem]]", "[[Centrality]]", "[[Chip-firing game]]", "[[Complex network]]", "[[Consensus dynamics]]", "[[Convex subgraph]]", "[[Copying mechanism]]"]
---

# Logic of graphs

In the mathematical fields of graph theory and finite model theory, the logic of graphs deals with formal specifications of graph properties using sentences of mathematical logic. There are several variations in the types of logical operation that can be used in these sentences. The first-order logic of graphs concerns sentences in which the variables and predicates concern individual vertices and edges of a graph, while monadic second-order graph logic allows quantification over sets of vertices or edges. Logics based on least fixed point operators allow more general predicates over tuples of vertices, but these predicates can only be constructed through fixed-point operators, restricting their power.
A sentence 
  
    
      
        S
      
    
    
  
 may be true for some graphs, and false for others; a graph 
  
    
      
        G
      
    
    
  
 is said to model 
  
    
      
        S
      
    
    
  
, written 
  
    
      
        G
        ⊨
        S
      
    
    
  
, if 
  
    
      
        S
      
    
    
  
 is true of the vertices and adjacency relation of 
  
    
      
        G
      
    
    
  
. The algorithmic problem of model checking concerns testing whether a given graph models a given sentence. The algorithmic problem of satisfiability concerns testing whether there exists a graph that models a given sentence.
Although both model checking and satisfiability are hard in general, several major algorithmic meta-theorems show that properties expressed in this way can be tested efficiently for important classes of graphs.
Other topics of research in the logic of graphs include investigations of the probability that a random graph has a property specified within a particular type of logic, and methods for data compression based on finding logical sentences that are modeled by a unique graph.

## Related

- [[Albertson index]]
- [[Bicircular matroid]]
- [[Bristol Bridges Walk]]
- [[Capacitated arc routing problem]]
- [[Centrality]]
- [[Chip-firing game]]
- [[Complex network]]
- [[Consensus dynamics]]
- [[Convex subgraph]]
- [[Copying mechanism]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Logic_of_graphs