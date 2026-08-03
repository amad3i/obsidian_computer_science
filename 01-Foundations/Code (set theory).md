---
title: "Code (set theory)"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Code_(set_theory)"
wikipedia_categories: ["Inner model theory", "Set theory", "Set theory stubs"]
related: ["[[Admissible set]]", "[[Almost]]", "[[Cabal (set theory)]]", "[[Categorical set theory]]", "[[Computable ordinal]]", "[[Extender (set theory)]]", "[[Game-theoretic rough sets]]", "[[Hereditarily countable set]]", "[[Hierarchy (mathematics)]]", "[[Information diagram]]"]
---

# Code (set theory)

In set theory, a code for a hereditarily countable set

  
    
      
        x
        ∈
        
          H
          
            
              ℵ
              
                1
              
            
          
        
        
      
    
    
  

is a set

  
    
      
        E
        ⊂
        ω
        ω
      
    
    
  

such that there is an isomorphism between 
  
    
      
        ω
        ,
        E
      
    
    
  
 and 
  
    
      
        X
        ,
        ∈
      
    
    
  
 where 
  
    
      
        X
      
    
    
  
 is the transitive closure of 
  
    
      
        x
      
    
    
  
.  If 
  
    
      
        X
      
    
    
  
 is finite (with cardinality 
  
    
      
        n
      
    
    
  
), then use 
  
    
      
        n
        n
      
    
    
  
 instead of 
  
    
      
        ω
        ω
      
    
    
  
 and 
  
    
      
        n
        ,
        E
      
    
    
  
 instead of 
  
    
      
        ω
        ,
        E
      
    
    
  
.
According to the axiom of extensionality, the identity of a set is determined by its elements. And since those elements are also sets, their identities are determined by their elements, etc.. So if one knows the element relation restricted to 
  
    
      
        X
      
    
    
  
, then one knows what 
  
    
      
        x
      
    
    
  
 is. (We use the transitive closure of 
  
    
      
        x
      
    
    
  
 rather than of 
  
    
      
        x
      
    
    
  
 itself to avoid confusing the elements of 
  
    
      
        x
      
    
    
  
 with elements of its elements or whatever.) A code includes that information identifying 
  
    
      
        x
      
    
    
  
 and also information about the particular injection from 
  
    
      
        X
      
    
    
  
 into 
  
    
      
        ω
      
    
    
  
 which was used to create 
  
    
      
        E
      
    
    
  
. The extra information about the injection is non-essential, so there are many codes for the same set which are equally useful.
So codes are a way of mapping 
  
    
      
        
          H
          
            
              ℵ
              
                1
              
            
          
        
      
    
    
  
 into the powerset of 
  
    
      
        ω
        ω
      
    
    
  
. Using a pairing function on 
  
    
      
        ω
      
    
    
  
 such as 
  
    
      
        n
        ,
        k
        ↦
        
          n
          
            2
          
        
        2
        n
        k
        
          k
          
            2
          
        
        n
        3
        k
        
          /
        
        2
      
    
    
  
, we can map the powerset of 
  
    
      
        ω
        ω
      
    
    
  
 into the powerset of 
  
    
      
        ω
      
    
    
  
. And we can map the powerset of 
  
    
      
        ω
      
    
    
  
 into the Cantor set, a subset of the real numbers. So statements about 
  
    
      
        
          H
          
            
              ℵ
              
                1
              
            
          
        
      
    
    
  
 can be converted into statements about the reals. Therefore, 
  
    
      
        
          H
          
            
              ℵ
              
                1
              
            
          
        
        ⊂
        L
        R
      
    
    
  
, where L(R) is the smallest transitive inner model of ZF containing all the ordinals and all the reals. 
Codes are useful in constructing mice.

## Related

- [[Admissible set]]
- [[Almost]]
- [[Cabal (set theory)]]
- [[Categorical set theory]]
- [[Computable ordinal]]
- [[Extender (set theory)]]
- [[Game-theoretic rough sets]]
- [[Hereditarily countable set]]
- [[Hierarchy (mathematics)]]
- [[Information diagram]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Code_(set_theory)