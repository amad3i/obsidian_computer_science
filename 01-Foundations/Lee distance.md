---
title: "Lee distance"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Lee_distance"
wikipedia_categories: ["Coding theory", "String metrics"]
related: ["[[Hamming ball]]", "[[Hamming distance]]", "[[Algebraic geometry code]]", "[[Alternant code]]", "[[Arbitrarily varying channel]]", "[[Bar product]]", "[[Barker code]]", "[[BCH code]]", "[[Belief propagation]]", "[[Berger code]]"]
---

# Lee distance

In coding theory, the Lee distance is a distance between two strings 
  
    
      
        
          x
          
            1
          
        
        
          x
          
            2
          
        
        …
        
          x
          
            n
          
        
      
    
    
  
 and 
  
    
      
        
          y
          
            1
          
        
        
          y
          
            2
          
        
        …
        
          y
          
            n
          
        
      
    
    
  
 of equal length n over the q-ary alphabet {0, 1, …, q − 1} of size q ≥ 2.  It is a metric defined as

  
    
      
        
          ∑
          
            i
            1
          
          
            n
          
        
        min
        
          |
        
        
          x
          
            i
          
        
        
          y
          
            i
          
        
        
          |
        
        ,
        
        q
        
          |
        
        
          x
          
            i
          
        
        
          y
          
            i
          
        
        
          |
        
        .
      
    
    
  

If q = 2 or q = 3  the Lee distance coincides with the Hamming distance, because both distances are 0 for two single equal symbols and 1 for two single non-equal symbols. For q > 3 this is not the case anymore; the Lee distance between single letters can become bigger than 1.  However, there exists a Gray isometry (weight-preserving bijection) between 
  
    
      
        
          
            Z
          
          
            4
          
        
      
    
    
  
 with the Lee weight and 
  
    
      
        
          
            Z
          
          
            2
          
          
            2
          
        
      
    
    
  
 with the Hamming weight.
Considering the alphabet as the additive group Zq, the Lee distance between two single letters 
  
    
      
        x
      
    
    
  
 and 
  
    
      
        y
      
    
    
  
 is the length of shortest path in the Cayley graph (which is circular since the group is cyclic) between them.  More generally, the Lee distance between two strings of length n is the length of the shortest path between them in the Cayley graph of 
  
    
      
        
          
            Z
          
          
            q
          
          
            n
          
        
      
    
    
  
.  This can also be thought of as the quotient metric resulting from reducing Zn with the Manhattan distance modulo the lattice qZn.  The analogous quotient metric on a quotient of Zn modulo an arbitrary lattice is known as a Mannheim metric or Mannheim distance.
The metric space induced by the Lee distance is a discrete analog of the elliptic space.

## Related

- [[Hamming ball]]
- [[Hamming distance]]
- [[Algebraic geometry code]]
- [[Alternant code]]
- [[Arbitrarily varying channel]]
- [[Bar product]]
- [[Barker code]]
- [[BCH code]]
- [[Belief propagation]]
- [[Berger code]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Lee_distance