---
title: "Region (model checking)"
tags: ["cs", "theory-of-computation", "advanced"]
domain: Theory of Computation
level: advanced
source: "https://en.wikipedia.org/wiki/Region_(model_checking)"
wikipedia_categories: ["Convex geometry"]
related: ["[[Absolutely convex set]]", "[[Algorithmic problems on convex sets]]", "[[Antimatroid]]", "[[Asymptotic geometry]]", "[[Convex cone]]", "[[Graph of a polytope]]", "[[Klee–Minty cube]]", "[[Normal cone (convex analysis)]]"]
---

# Region (model checking)

In model checking, a field of computer science, a region is a convex polytope in 
  
    
      
        
          
            R
          
          
            d
          
        
      
    
    
  
 for some dimension 
  
    
      
        d
      
    
    
  
, and more precisely a zone, satisfying some minimality property. The regions partition 
  
    
      
        
          
            R
          
          
            d
          
        
      
    
    
  
.
The set of zones depends on a set 
  
    
      
        K
      
    
    
  
 of constraints of the form 
  
    
      
        x
        ≤
        c
      
    
    
  
, 
  
    
      
        x
        ≥
        c
      
    
    
  
, 
  
    
      
        
          x
          
            1
          
        
        ≤
        
          x
          
            2
          
        
        c
      
    
    
  
 and 
  
    
      
        
          x
          
            1
          
        
        ≥
        
          x
          
            2
          
        
        c
      
    
    
  
, with 
  
    
      
        
          x
          
            1
          
        
      
    
    
  
 and 
  
    
      
        
          x
          
            2
          
        
      
    
    
  
 some variables, and 
  
    
      
        c
      
    
    
  
 a constant. The regions are defined such that if two vectors 
  
    
      
        
          
            
              x
              →
            
          
        
      
    
    
  
 and 
  
    
      
        
          
            
              
                x
                →
              
            
          
          ′
        
      
    
    
  
 belong to the same region, then they satisfy the same constraints of 
  
    
      
        K
      
    
    
  
. Furthermore, when those vectors are considered as a tuple of clocks, both vectors have the same  set of possible futures. Intuitively, it means that any timed propositional temporal logic-formula, or timed automaton or signal automaton using only the constraints of 
  
    
      
        K
      
    
    
  
 can not distinguish both vectors.
The set of region allows to create the region automaton, which is a directed graph in which each node is a region, and each edge 
  
    
      
        r
        →
        
          r
          ′
        
      
    
    
  
 ensure that 
  
    
      
        
          r
          ′
        
      
    
    
  
 is a possible future of 
  
    
      
        r
      
    
    
  
. Taking a product of this region automaton and of a timed automaton 
  
    
      
        
          
            A
          
        
      
    
    
  
 which accepts a language 
  
    
      
        L
      
    
    
  
 creates a finite automaton or a Büchi automaton which accepts untimed 
  
    
      
        L
      
    
    
  
. In particular, it allows to reduce the emptiness problem for 
  
    
      
        
          
            A
          
        
      
    
    
  
 to the emptiness problem for a finite or Büchi automaton. This technique is used for example by the software UPPAAL.

## Related

- [[Absolutely convex set]]
- [[Algorithmic problems on convex sets]]
- [[Antimatroid]]
- [[Asymptotic geometry]]
- [[Convex cone]]
- [[Graph of a polytope]]
- [[Klee–Minty cube]]
- [[Normal cone (convex analysis)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Region_(model_checking)