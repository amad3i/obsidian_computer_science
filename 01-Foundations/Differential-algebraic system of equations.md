---
title: "Differential-algebraic system of equations"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Differential-algebraic_system_of_equations"
wikipedia_categories: ["Differential calculus", "Numerical analysis"]
related: ["[[Difference quotient]]", "[[Linear approximation]]", "[[Numerical differentiation]]", "[[2Sum]]", "[[Abramowitz and Stegun]]", "[[Adaptive step size]]", "[[Adjoint state method]]", "[[Affine arithmetic]]", "[[Applied element method]]", "[[Approximation]]"]
---

# Differential-algebraic system of equations

In mathematics, a differential-algebraic system of equations (DAE) is a system of equations that either contains differential equations and algebraic equations, or is equivalent to such a system.
The set of the solutions of such a system is a differential algebraic variety, and corresponds to an ideal in a differential algebra of differential polynomials.
In the univariate case, a DAE in the  variable t can be written as a single equation of the form

  
    
      
        F
        
          
            
              x
              ˙
            
          
        
        ,
        x
        ,
        t
        =
        0
        ,
      
    
    
  

where 
  
    
      
        x
        t
      
    
    
  
 is a vector of unknown functions and the overdot denotes the time derivative, i.e., 
  
    
      
        
          
            
              x
              ˙
            
          
        
        
          
            
              d
              x
            
            
              d
              t
            
          
        
      
    
    
  
.
They are distinct from ordinary differential equation (ODE) in that a DAE is not completely solvable for the derivatives of all components of the function x because these may not all appear (i.e. some equations are algebraic); technically the distinction between an implicit ODE system [that may be rendered explicit] and a DAE system is that the Jacobian matrix 
  
    
      
        
          
            
              ∂
              F
              
                
                  
                    x
                    ˙
                  
                
              
              ,
              x
              ,
              t
            
            
              ∂
              
                
                  
                    x
                    ˙
                  
                
              
            
          
        
      
    
    
  
 is a singular matrix for a DAE system. This distinction between ODEs and DAEs is made because DAEs have different characteristics and are generally more difficult to solve.
In practical terms, the distinction between DAEs and ODEs is often that the solution of a DAE system depends on the derivatives of the input signal and not just the signal itself as in the case of ODEs; this issue is commonly encountered in nonlinear systems with hysteresis, such as the Schmitt trigger.
This difference is more clearly visible if the system may be rewritten so that instead of x we consider a pair 
  
    
      
        x
        ,
        y
      
    
    
  
 of vectors of dependent variables and the DAE has the form

  
    
      
        
          
            
              
                
                  
                    
                      x
                      ˙
                    
                  
                
                t
              
              
                
                f
                x
                t
                ,
                y
                t
                ,
                t
                ,
              
            
            
              
                0
              
              
                
                g
                x
                t
                ,
                y
                t
                ,
                t
                .
              
            
          
        
      
    
    
  

where 
  
    
      
        x
        t
        ∈
        
          
            R
          
          
            n
          
        
      
    
    
  
, 
  
    
      
        y
        t
        ∈
        
          
            R
          
          
            m
          
        
      
    
    
  
, 
  
    
      
        f
        :
        
          
            R
          
          
            n
            m
            1
          
        
        →
        
          
            R
          
          
            n
          
        
      
    
    
  
 and 
  
    
      
        g
        :
        
          
            R
          
          
            n
            m
            1
          
        
        →
        
          
            R
          
          
            m
          
        
        .
      
    
    
  

A DAE system of this form is called semi-explicit. Every solution of the second half g of the equation defines a unique direction for x via the first half f of the equations, while the direction for y is arbitrary. But not every point (x,y,t) is a solution of g. The variables in x and the first half f of the equations get the attribute differential. The components of y and the second half g of the equations are called the algebraic variables or equations of the system. [The term algebraic in the context of DAEs only means free of derivatives and is not related to (abstract) algebra.]
The solution of a DAE consists of two parts, first the search for consistent initial values and second the computation of a trajectory. To find consistent initial values it is often necessary to consider the derivatives of some of the component functions of the DAE. The highest order of a derivative that is necessary for this process is called the differentiation index. The equations derived in computing the index and consistent initial values may also be of use in the computation of the trajectory. A semi-explicit DAE system can be converted to an implicit one by decreasing the differentiation index by one, and vice versa.

## Related

- [[Difference quotient]]
- [[Linear approximation]]
- [[Numerical differentiation]]
- [[2Sum]]
- [[Abramowitz and Stegun]]
- [[Adaptive step size]]
- [[Adjoint state method]]
- [[Affine arithmetic]]
- [[Applied element method]]
- [[Approximation]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Differential-algebraic_system_of_equations