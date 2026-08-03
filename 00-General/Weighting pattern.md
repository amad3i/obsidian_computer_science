---
title: "Weighting pattern"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Weighting_pattern"
wikipedia_categories: ["Control theory"]
related: ["[[4D-RCS Reference Model Architecture]]", "[[Ackermann's formula]]", "[[Active disturbance rejection control]]", "[[Adaptive control]]", "[[Advanced process control]]", "[[Affect control theory]]", "[[American Automatic Control Council]]", "[[Anticausal system]]", "[[Artstein's theorem]]", "[[Asymptotic gain model]]"]
---

# Weighting pattern

A weighting pattern for a linear dynamical system describes the relationship between an input 
  
    
      
        u
      
    
    
  
 and output 
  
    
      
        y
      
    
    
  
. Given the time-variant system described by

  
    
      
        
          
            
              x
              ˙
            
          
        
        t
        =
        A
        t
        x
        t
        +
        B
        t
        u
        t
      
    
    
  

  
    
      
        y
        t
        =
        C
        t
        x
        t
      
    
    
  
,
then the output can be written as

  
    
      
        y
        t
        =
        y
        
          t
          
            0
          
        
        +
        
          ∫
          
            
              t
              
                0
              
            
          
          
            t
          
        
        T
        t
        ,
        σ
        u
        σ
        d
        σ
      
    
    
  
,
where 
  
    
      
        T
        ⋅
        ,
        ⋅
      
    
    
  
 is the weighting pattern for the system. For such a system, the weighting pattern is 
  
    
      
        T
        t
        ,
        σ
        =
        C
        t
        ϕ
        t
        ,
        σ
        B
        σ
      
    
    
  
 such that 
  
    
      
        ϕ
      
    
    
  
 is the state transition matrix.
The weighting pattern will determine a system, but if there exists a realization for this weighting pattern then there exist many that do so.

## Related

- [[4D-RCS Reference Model Architecture]]
- [[Ackermann's formula]]
- [[Active disturbance rejection control]]
- [[Adaptive control]]
- [[Advanced process control]]
- [[Affect control theory]]
- [[American Automatic Control Council]]
- [[Anticausal system]]
- [[Artstein's theorem]]
- [[Asymptotic gain model]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Weighting_pattern