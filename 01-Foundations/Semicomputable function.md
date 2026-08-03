---
title: "Semicomputable function"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Semicomputable_function"
wikipedia_categories: ["Mathematical logic", "Mathematical logic stubs"]
related: ["[[Abstract logic]]", "[[Abstract model theory]]", "[[Algebraic semantics (mathematical logic)]]", "[[Barwise compactness theorem]]", "[[Beth definability]]", "[[Cyclic negation]]", "[[Diagram (mathematical logic)]]", "[[Double turnstile]]", "[[Elementary definition]]", "[[Elementary theory]]"]
---

# Semicomputable function

In computability theory, a semicomputable function is a partial function 
  
    
      
        f
        :
        
          Q
        
        →
        
          R
        
      
    
    
  
 that can be approximated either from above or from below by a computable function.
More precisely a partial function 
  
    
      
        f
        :
        
          Q
        
        →
        
          R
        
      
    
    
  
 is upper semicomputable, meaning it can be approximated from above, if there exists a computable function 
  
    
      
        ϕ
        x
        ,
        k
        :
        
          Q
        
        
          N
        
        →
        
          Q
        
      
    
    
  
, where 
  
    
      
        x
      
    
    
  
 is the desired parameter for 
  
    
      
        f
        x
      
    
    
  
 and 
  
    
      
        k
      
    
    
  
 is the level of approximation, such that:

  
    
      
        
          
            k
            →
            ∞
          
        
        ϕ
        x
        ,
        k
        =
        f
        x
      
    
    
  

  
    
      
        ∀
        k
        ∈
        
          N
        
        :
        ϕ
        x
        ,
        k
        1
        ≤
        ϕ
        x
        ,
        k
      
    
    
  

Completely analogous a partial function 
  
    
      
        f
        :
        
          Q
        
        →
        
          R
        
      
    
    
  
 is lower semicomputable if and only if 
  
    
      
        f
        x
      
    
    
  
 is upper semicomputable or equivalently if there exists a  computable function 
  
    
      
        ϕ
        x
        ,
        k
      
    
    
  
 such that:

  
    
      
        
          
            k
            →
            ∞
          
        
        ϕ
        x
        ,
        k
        =
        f
        x
      
    
    
  

  
    
      
        ∀
        k
        ∈
        
          N
        
        :
        ϕ
        x
        ,
        k
        1
        ≥
        ϕ
        x
        ,
        k
      
    
    
  

If a partial function is both upper and lower semicomputable it is called computable.

## Related

- [[Abstract logic]]
- [[Abstract model theory]]
- [[Algebraic semantics (mathematical logic)]]
- [[Barwise compactness theorem]]
- [[Beth definability]]
- [[Cyclic negation]]
- [[Diagram (mathematical logic)]]
- [[Double turnstile]]
- [[Elementary definition]]
- [[Elementary theory]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Semicomputable_function