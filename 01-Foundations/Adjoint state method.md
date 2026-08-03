---
title: "Adjoint state method"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Adjoint_state_method"
wikipedia_categories: ["Applied mathematics stubs", "Numerical analysis"]
related: ["[[Artificial precision]]", "[[Generalized Gauss–Newton method]]", "[[Numerical error]]", "[[Order of accuracy]]", "[[Semi-infinite programming]]", "[[Sinc numerical methods]]", "[[Superconvergence]]", "[[2Sum]]", "[[Abramowitz and Stegun]]", "[[Adaptive step size]]"]
---

# Adjoint state method

The adjoint state method is a numerical method for efficiently computing the gradient of a function or operator in a numerical optimization problem.  It has applications in geophysics, seismic imaging, photonics and more recently in neural networks.
The adjoint state space is chosen to simplify the physical interpretation of equation constraints.
Adjoint state techniques allow the use of integration by parts, resulting in a form which explicitly contains the physically interesting quantity.  An adjoint state equation is introduced, including a new unknown variable.
The adjoint method formulates the gradient of a function towards its parameters in a constraint optimization form. By using the dual form of this constraint optimization problem, it can be used to calculate the gradient very fast. A nice property is that the number of computations is independent of the number of parameters for which you want the gradient.
The adjoint method is derived from the dual problem and is used e.g. in the Landweber iteration method.
The name adjoint state method refers to the dual form of the problem, where the adjoint matrix 
  
    
      
        
          A
          
          
        
        
          
            
              A
              ¯
            
          
          
            T
          
        
      
    
    
  
 is used.
When the initial problem consists of calculating the product 
  
    
      
        
          s
          
            T
          
        
        x
      
    
    
  
 and 
  
    
      
        x
      
    
    
  
 must satisfy 
  
    
      
        A
        x
        b
      
    
    
  
, the dual problem can be realized as calculating the product 
  
    
      
        
          r
          
            T
          
        
        b
      
    
    
  
  
    
      
        
          s
          
            T
          
        
        x
      
    
    
  
), where 
  
    
      
        r
      
    
    
  
 must satisfy 
  
    
      
        
          A
          
          
        
        r
        s
      
    
    
  
. 
And 

  
    
      
        r
      
    
    
  
 is called the adjoint state vector.

## Related

- [[Artificial precision]]
- [[Generalized Gauss–Newton method]]
- [[Numerical error]]
- [[Order of accuracy]]
- [[Semi-infinite programming]]
- [[Sinc numerical methods]]
- [[Superconvergence]]
- [[2Sum]]
- [[Abramowitz and Stegun]]
- [[Adaptive step size]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Adjoint_state_method