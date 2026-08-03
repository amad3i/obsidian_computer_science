---
title: "Ehrenfest model"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Ehrenfest_model"
wikipedia_categories: ["Diffusion", "Queueing theory", "Stochastic models"]
related: ["[[Adversarial queueing network]]", "[[Arrival theorem]]", "[[Backpressure routing]]", "[[Balance equation]]", "[[Bartlett's theorem]]", "[[BCMP network]]", "[[Beneš method]]", "[[Birth–death process]]", "[[Burke's theorem]]", "[[Buzen's algorithm]]"]
---

# Ehrenfest model

The Ehrenfest model (or dog–flea model) of diffusion was proposed by Tatiana and Paul Ehrenfest to explain the second law of thermodynamics. The model considers N particles in two containers. Particles independently change container at a rate λ. If X(t) = i is defined to be the number of particles in one container at time t, then it is a birth–death process with transition rates

  
    
      
        
          q
          
            i
            ,
            i
            1
          
        
        i
        
        λ
      
    
    
  
 for i = 1, 2, ..., N

  
    
      
        
          q
          
            i
            ,
            i
            1
          
        
        (
        N
        i
        
        λ
      
    
    
  
 for i = 0, 1, ..., N – 1
and equilibrium distribution 
  
    
      
        
          π
          
            i
          
        
        
          2
          
            N
          
        
        
          
            
              
              
              
                N
                i
              
              
              
            
          
        
      
    
    
  
.
Mark Kac proved in 1947 that if the initial system state is not equilibrium, then the entropy, given by

  
    
      
        H
        t
        =
        
          ∑
          
            i
          
        
        P
        X
        t
        =
        i
        log
         
        
          
            
              
                P
                X
                t
                =
                i
              
              
                π
                
                  i
                
              
            
          
        
        ,
      
    
    
  

is monotonically increasing (H-theorem). This is a consequence of the convergence to the equilibrium distribution.

## Related

- [[Adversarial queueing network]]
- [[Arrival theorem]]
- [[Backpressure routing]]
- [[Balance equation]]
- [[Bartlett's theorem]]
- [[BCMP network]]
- [[Beneš method]]
- [[Birth–death process]]
- [[Burke's theorem]]
- [[Buzen's algorithm]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Ehrenfest_model