---
title: "Covariance operator"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Covariance_operator"
wikipedia_categories: ["Bilinear forms", "Covariance and correlation", "Hilbert spaces", "Probability stubs", "Probability theory"]
related: ["[[Decoupling (probability)]]", "[[Dual total correlation]]", "[[Exotic probability]]", "[[Mixture (probability)]]", "[[Total correlation]]", "[[Total variation distance of probability measures]]", "[[Additive process]]", "[[Additive smoothing]]", "[[Adversarial queueing network]]", "[[Almost surely]]"]
---

# Covariance operator

In probability theory, for a probability measure P on a Hilbert space H with inner product 
  
    
      
        ⟨
        ⋅
        ,
        ⋅
        ⟩
      
    
    
  
, the covariance of P is the bilinear form Cov: H × H → R given by

  
    
      
        
          C
          o
          v
        
        x
        ,
        y
        =
        
          ∫
          
            H
          
        
        ⟨
        x
        ,
        z
        ⟩
        ⟨
        y
        ,
        z
        ⟩
        
        
          d
        
        
          P
        
        z
      
    
    
  

for all x and y in H. The covariance operator C is then defined by

  
    
      
        
          C
          o
          v
        
        x
        ,
        y
        =
        ⟨
        C
        x
        ,
        y
        ⟩
      
    
    
  

(from the Riesz representation theorem, such operator exists if Cov is bounded). Since Cov is symmetric in its arguments, the covariance operator is
self-adjoint. 
Even more generally, for a probability measure P on a Banach space B, the covariance of P is the bilinear form on the algebraic dual B#, defined by

  
    
      
        
          C
          o
          v
        
        x
        ,
        y
        =
        
          ∫
          
            B
          
        
        ⟨
        x
        ,
        z
        ⟩
        ⟨
        y
        ,
        z
        ⟩
        
        
          d
        
        
          P
        
        z
      
    
    
  

where 
  
    
      
        ⟨
        x
        ,
        z
        ⟩
      
    
    
  
 is now the value of the linear functional x on the element z.
Quite similarly, the covariance function of a function-valued random element (in special cases is called random process or random field) z is

  
    
      
        
          C
          o
          v
        
        x
        ,
        y
        =
        ∫
        z
        x
        z
        y
        
        
          d
        
        
          P
        
        z
        =
        E
        z
        x
        z
        y
        )
      
    
    
  

where z(x) is now the value of the function z at the point x, i.e., the value of the linear functional 
  
    
      
        u
        ↦
        u
        x
      
    
    
  
 evaluated at z.

## Related

- [[Decoupling (probability)]]
- [[Dual total correlation]]
- [[Exotic probability]]
- [[Mixture (probability)]]
- [[Total correlation]]
- [[Total variation distance of probability measures]]
- [[Additive process]]
- [[Additive smoothing]]
- [[Adversarial queueing network]]
- [[Almost surely]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Covariance_operator