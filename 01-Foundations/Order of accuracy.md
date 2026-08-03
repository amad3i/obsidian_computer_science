---
title: "Order of accuracy"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Order_of_accuracy"
wikipedia_categories: ["Applied mathematics stubs", "Numerical analysis"]
related: ["[[Adjoint state method]]", "[[Artificial precision]]", "[[Generalized Gauss–Newton method]]", "[[Numerical error]]", "[[Semi-infinite programming]]", "[[Sinc numerical methods]]", "[[Superconvergence]]", "[[2Sum]]", "[[Abramowitz and Stegun]]", "[[Adaptive step size]]"]
---

# Order of accuracy

In numerical analysis, order of accuracy quantifies the rate of convergence of a numerical approximation of a differential equation to the exact solution.
Consider 
  
    
      
        u
      
    
    
  
, the exact solution to a differential equation in an appropriate normed space 
  
    
      
        V
        ,
        
          |
        
        
          |
        
         
        
          |
        
        
          |
        
      
    
    
  
. Consider a numerical approximation 
  
    
      
        
          u
          
            h
          
        
      
    
    
  
, where 
  
    
      
        h
      
    
    
  
 is a parameter characterizing the approximation, such as the step size in a finite difference scheme or the diameter of the cells in a finite element method.
The numerical solution 
  
    
      
        
          u
          
            h
          
        
      
    
    
  
 is said to be 
  
    
      
        
          n
        
      
    
    
  
th-order accurate if the error 
  
    
      
        E
        h
        :=
        
          |
        
        
          |
        
        u
        
          u
          
            h
          
        
        
          |
        
        
          |
        
      
    
    
  
 is proportional to the step-size 
  
    
      
        h
      
    
    
  
 to the 
  
    
      
        n
      
    
    
  
th power:

  
    
      
        E
        h
        =
        
          |
        
        
          |
        
        u
        
          u
          
            h
          
        
        
          |
        
        
          |
        
        ≤
        C
        
          h
          
            n
          
        
      
    
    
  

where the constant 
  
    
      
        C
      
    
    
  
 is independent of 
  
    
      
        h
      
    
    
  
 and usually depends on the solution 
  
    
      
        u
      
    
    
  
. Using the big O notation an 
  
    
      
        n
      
    
    
  
th-order accurate numerical method is notated as

  
    
      
        
          |
        
        
          |
        
        u
        
          u
          
            h
          
        
        
          |
        
        
          |
        
        O
        
          h
          
            n
          
        
      
    
    
  

This definition is strictly dependent on the norm used in the space; the choice of such norm is fundamental to estimate the rate of convergence and, in general, all numerical errors correctly.
The size of the error of a first-order accurate approximation is directly proportional to 
  
    
      
        h
      
    
    
  
.
Partial differential equations which vary over both time and space are said to be accurate to order 
  
    
      
        n
      
    
    
  
 in time and to order 
  
    
      
        m
      
    
    
  
 in space.

## Related

- [[Adjoint state method]]
- [[Artificial precision]]
- [[Generalized Gauss–Newton method]]
- [[Numerical error]]
- [[Semi-infinite programming]]
- [[Sinc numerical methods]]
- [[Superconvergence]]
- [[2Sum]]
- [[Abramowitz and Stegun]]
- [[Adaptive step size]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Order_of_accuracy