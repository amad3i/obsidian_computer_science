---
title: "Sinc numerical methods"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Sinc_numerical_methods"
wikipedia_categories: ["Applied mathematics stubs", "Numerical analysis"]
related: ["[[Adjoint state method]]", "[[Artificial precision]]", "[[Generalized Gauss–Newton method]]", "[[Numerical error]]", "[[Order of accuracy]]", "[[Semi-infinite programming]]", "[[Superconvergence]]", "[[2Sum]]", "[[Abramowitz and Stegun]]", "[[Adaptive step size]]"]
---

# Sinc numerical methods

In numerical analysis and applied mathematics, sinc numerical methods are numerical techniques for finding approximate solutions of partial differential equations and integral equations based on the translates of sinc function and Cardinal function C(f,h) which is an expansion of f defined by

  
    
      
        C
        f
        ,
        h
        (
        x
        =
        
          ∑
          
            k
            −
            ∞
          
          
            ∞
          
        
        f
        k
        h
        
        
          
            sinc
          
        
        
          
            
              
                
                  x
                  h
                
              
            
            k
          
        
      
    
    
  

where the step size h>0 and where the sinc function is defined by

  
    
      
        
          
            sinc
          
        
        x
        =
        
          
            
               
              π
              x
            
            
              π
              x
            
          
        
      
    
    
  

Sinc approximation methods excel for problems whose solutions may have singularities, or infinite domains, or boundary layers.
The truncated Sinc expansion of f is defined by the following series:

  
    
      
        
          C
          
            M
            ,
            N
          
        
        f
        ,
        h
        (
        x
        =
        
          
            ∑
            
              k
              −
              M
            
            
              N
            
          
          f
          k
          h
          
          
            
              sinc
            
          
          
            
              
                
                  
                    x
                    h
                  
                
              
              k
            
          
        
      
    
    
  
 .

## Related

- [[Adjoint state method]]
- [[Artificial precision]]
- [[Generalized Gauss–Newton method]]
- [[Numerical error]]
- [[Order of accuracy]]
- [[Semi-infinite programming]]
- [[Superconvergence]]
- [[2Sum]]
- [[Abramowitz and Stegun]]
- [[Adaptive step size]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Sinc_numerical_methods