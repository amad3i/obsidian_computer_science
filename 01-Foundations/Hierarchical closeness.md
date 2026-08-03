---
title: "Hierarchical closeness"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Hierarchical_closeness"
wikipedia_categories: ["Algebraic graph theory", "Graph algorithms", "Graph theory", "Network analysis", "Network theory", "Networks"]
related: ["[[Centrality]]", "[[Group centrality]]", "[[Semantic Brand Score]]", "[[Clique percolation method]]", "[[Girvan–Newman algorithm]]", "[[Network theory]]", "[[Albertson index]]", "[[Capacitated arc routing problem]]", "[[Complex network]]", "[[Consensus dynamics]]"]
---

# Hierarchical closeness

Hierarchical closeness (HC) is a structural centrality measure used in network theory or graph theory. It is extended from closeness centrality to rank how centrally located a node is in a directed network. While the original closeness centrality of a directed network considers the most important node to be that with the least total distance from all other nodes, hierarchical closeness evaluates the most important node as the one which reaches the most nodes by the shortest paths.  The hierarchical closeness explicitly includes information about the range of other nodes that can be affected by the given node. In a directed network 
  
    
      
        G
        V
        ,
        A
      
    
    
  
 where 
  
    
      
        V
      
    
    
  
 is the set of nodes and 
  
    
      
        A
      
    
    
  
 is the set of interactions, hierarchical closeness of a node 
  
    
      
        i
      
    
    
  
 ∈ 
  
    
      
        V
      
    
    
  
 called 
  
    
      
        
          C
          
            h
            c
          
        
        i
      
    
    
  
 was proposed by Tran and Kwon as follows:

  
    
      
        
          C
          
            h
            c
          
        
        i
        =
        
          N
          
            R
          
        
        i
        +
        
          C
          
            c
            l
            o
            i
          
        
        i
      
    
    
  

where:

  
    
      
        
          N
          
            R
          
        
        i
        ∈
        0
        ,
        
          |
        
        V
        
          |
        
        1
      
    
    
  
 is the reachability of a node 
  
    
      
        i
      
    
    
  
 defined by 
  
    
      
        
          N
          
            R
          
        
        i
        =
        
          |
        
        j
        ∈
        V
        :
        ∃
      
    
    
        
          |
        
      
    
    |}
  
, and

  
    
      
        
          C
          
            c
            l
            o
          
        
        i
      
    
    
  
 is the normalized form of original closeness (Sabidussi, 1966). It can use a variant definition of closeness as follows:  
  
    
      
        
          C
          
            c
            l
            o
            i
          
        
        i
        =
        
          
            1
            
              
                |
              
              V
              
                |
              
              1
            
          
        
        
          ∑
          
            j
            ∈
            V
            ∖
            i
          
        
        
          
            1
            
              d
              i
              ,
              j
            
          
        
      
    
    
  
 where 
  
    
      
        d
        i
        ,
        j
      
    
    
  
 is the distance of the shortest path, if any, from 
  
    
      
        i
      
    
    
  
 to 
  
    
      
        j
      
    
    
  
; otherwise, 
  
    
      
        d
        i
        ,
        j
      
    
    
  
 is specified as an infinite value.
In the formula, 
  
    
      
        
          N
          
            R
          
        
        i
      
    
    
  
 represents the number of nodes in 
  
    
      
        V
      
    
    
  
 that can be reachable from 
  
    
      
        i
      
    
    
  
. It can also represent the hierarchical position of a node in a directed network. It notes that if 
  
    
      
        
          N
          
            R
          
        
        i
        =
        0
      
    
    
  
, then 
  
    
      
        
          C
          
            h
            c
          
        
        i
        =
        0
      
    
    
  
 because 
  
    
      
        
          C
          
            c
            l
            o
            i
          
        
        i
      
    
    
  
 is 
  
    
      
        0
      
    
    
  
. In cases where 
  
    
      
        
          N
          
            R
          
        
        i
        >
        0
      
    
    
  
, the reachability is a dominant factor because 
  
    
      
        
          N
          
            R
          
        
        i
        ≥
        1
      
    
    
  
 but 
  
    
      
        
          C
          
            c
            l
            o
            i
          
        
        i
        <
        1
      
    
    
  
. In other words, the first term indicates the level of the global hierarchy and the second term presents the level of the local centrality.

## Related

- [[Centrality]]
- [[Group centrality]]
- [[Semantic Brand Score]]
- [[Clique percolation method]]
- [[Girvan–Newman algorithm]]
- [[Network theory]]
- [[Albertson index]]
- [[Capacitated arc routing problem]]
- [[Complex network]]
- [[Consensus dynamics]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Hierarchical_closeness