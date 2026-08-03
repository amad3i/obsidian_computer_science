---
title: "Graph isomorphism"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Graph_isomorphism"
wikipedia_categories: ["Graph algorithms", "Graph theory", "Morphisms"]
related: ["[[Capacitated arc routing problem]]", "[[Centrality]]", "[[Fibrations of graphs]]", "[[Graph edit distance]]", "[[Graph homomorphism]]", "[[Graph isomorphism problem]]", "[[Group centrality]]", "[[Hierarchical closeness]]", "[[Semantic Brand Score]]", "[[Transitive reduction]]"]
---

# Graph isomorphism

In graph theory, an isomorphism of graphs G and H is a bijection between the vertex sets of G and H

  
    
      
        f
        :
        V
        G
        →
        V
        H
      
    
    
  

such that any two vertices u and v of G are adjacent in G if and only if 
  
    
      
        f
        u
      
    
    
  
 and 
  
    
      
        f
        v
      
    
    
  
 are adjacent in H. This kind of bijection is commonly described as "edge-preserving bijection", in accordance with the general notion of isomorphism being a structure-preserving bijection.
If an isomorphism exists between two graphs, then the graphs are called isomorphic, often denoted by 
  
    
      
        G
        ≃
        H
      
    
    
  
. In the case when the isomorphism is a mapping of a graph onto itself, i.e., when G and H are one and the same graph, the isomorphism is called an automorphism of G.
Graph isomorphism is an equivalence relation on graphs and as such it partitions the class of all graphs into equivalence classes. A set of graphs isomorphic to each other is called an isomorphism class of graphs. The question of whether graph isomorphism can be determined in polynomial time is a major unsolved problem in computer science, known as the graph isomorphism problem.
The two graphs shown below are isomorphic, despite their different looking drawings.

## Related

- [[Capacitated arc routing problem]]
- [[Centrality]]
- [[Fibrations of graphs]]
- [[Graph edit distance]]
- [[Graph homomorphism]]
- [[Graph isomorphism problem]]
- [[Group centrality]]
- [[Hierarchical closeness]]
- [[Semantic Brand Score]]
- [[Transitive reduction]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Graph_isomorphism