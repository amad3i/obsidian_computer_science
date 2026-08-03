---
title: "Rate of convergence"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Rate_of_convergence"
wikipedia_categories: ["Numerical analysis", "Rates"]
related: ["[[2Sum]]", "[[Abramowitz and Stegun]]", "[[Adaptive step size]]", "[[Adjoint state method]]", "[[Affine arithmetic]]", "[[Applied element method]]", "[[Approximation]]", "[[Approximation error]]", "[[Approximation theory]]", "[[Arc-length method]]"]
---

# Rate of convergence

In mathematical analysis, particularly numerical analysis, the rate of convergence and order of convergence of a sequence that converges to a limit are any of several characterizations of how quickly that sequence approaches its limit. These are broadly divided into rates and orders of convergence that describe how quickly a sequence further approaches its limit once it is already close to it, called asymptotic rates and orders of convergence, and those that describe how quickly sequences approach their limits from starting points that are not necessarily close to their limits, called non-asymptotic rates and orders of convergence.  
Asymptotic behavior is particularly useful for deciding when to stop a sequence of numerical computations, for instance once a target precision has been reached with an iterative root-finding algorithm, but pre-asymptotic behavior is often crucial for determining whether to begin a sequence of computations at all, since it may be impossible or impractical to ever reach a target precision with a poorly chosen approach. Asymptotic rates and orders of convergence are the focus of this article.  
In practical numerical computations, asymptotic rates and orders of convergence follow two common conventions for two types of sequences: the first for sequences of iterations of an iterative numerical method and the second for sequences of successively more accurate numerical discretizations of a target. In formal mathematics, rates of convergence and orders of convergence are often described comparatively using asymptotic notation commonly called "big O notation," which can be used to encompass both of the prior conventions; this is an application of asymptotic analysis. 
For iterative methods, a sequence 
  
    
      
        
          x
          
            k
          
        
      
    
    
  
 that converges to 
  
    
      
        L
      
    
    
  
 is said to have asymptotic order of convergence 
  
    
      
        q
        ≥
        1
      
    
    
  
 and asymptotic rate of convergence 
  
    
      
        μ
      
    
    
  
 if 

  
    
      
        
          
            k
            →
            ∞
          
        
        
          
            
              |
              
                
                  x
                  
                    k
                    1
                  
                
                L
              
              |
            
            
              
                |
                
                  
                    x
                    
                      k
                    
                  
                  L
                
                |
              
              
                q
              
            
          
        
        μ
        .
      
    
    
  

Where methodological precision is required, these rates and orders of convergence are known specifically as the rates and orders of Q-convergence, short for quotient-convergence, since the limit in question is a quotient of error terms. The rate of convergence 
  
    
      
        μ
      
    
    
  
 may also be called the asymptotic error constant, and some authors will use rate where this article uses order. Series acceleration methods are techniques for improving the rate of convergence of the sequence of partial sums of a series and possibly its order of convergence, also.  
Similar concepts are used for sequences of discretizations. For instance, ideally the solution of a differential equation discretized via a regular grid will converge to the solution of the continuous equation as the grid spacing goes to zero, and if so the asymptotic rate and order of that convergence are important properties of the gridding method. A sequence of approximate grid solutions 
  
    
      
        
          y
          
            k
          
        
      
    
    
  
 of some problem that converges to a true solution 
  
    
      
        S
      
    
    
  
 with a corresponding sequence of regular grid spacings 
  
    
      
        
          h
          
            k
          
        
      
    
    
  
 that converge to 0 is said to have asymptotic order of convergence 
  
    
      
        q
      
    
    
  
 and asymptotic rate of convergence 
  
    
      
        μ
      
    
    
  
 if

  
    
      
        
          
            k
            →
            ∞
          
        
        
          
            
              |
              
                
                  y
                  
                    k
                  
                
                S
              
              |
            
            
              h
              
                k
              
              
                q
              
            
          
        
        μ
        ,
      
    
    
  

where the absolute value symbols stand for a metric for the space of solutions such as the uniform norm. Similar definitions also apply for non-grid discretization schemes such as the polygon meshes of a finite element method or the basis sets in computational chemistry: in general, the appropriate definition of the asymptotic rate 
  
    
      
        μ
      
    
    
  
 will involve the asymptotic limit of the ratio of an approximation error term above to an asymptotic order 
  
    
      
        q
      
    
    
  
 power of a discretization scale parameter below.
In general, comparatively, one sequence 
  
    
      
        
          a
          
            k
          
        
      
    
    
  
 that converges to a limit 
  
    
      
        
          L
          
            a
          
        
      
    
    
  
 is said to asymptotically converge more quickly than another sequence 
  
    
      
        
          b
          
            k
          
        
      
    
    
  
 that converges to a limit 
  
    
      
        
          L
          
            b
          
        
      
    
    
  
 if 

  
    
      
        
          
            k
            →
            ∞
          
        
        
          
            
              |
              
                
                  a
                  
                    k
                  
                
                
                  L
                  
                    a
                  
                
              
              |
            
            
              
                |
              
              
                b
                
                  k
                
              
              
                L
                
                  b
                
              
              
                |
              
            
          
        
        0
        ,
      
    
    
  

and the two are said to asymptotically converge with the same order of convergence if the limit is any positive finite value. The two are said to be asymptotically equivalent if the limit is equal to one. These comparative definitions of rate and order of asymptotic convergence are fundamental in asymptotic analysis and find wide application in mathematical analysis as a whole, including numerical analysis, real analysis, complex analysis, and functional analysis.

## Related

- [[2Sum]]
- [[Abramowitz and Stegun]]
- [[Adaptive step size]]
- [[Adjoint state method]]
- [[Affine arithmetic]]
- [[Applied element method]]
- [[Approximation]]
- [[Approximation error]]
- [[Approximation theory]]
- [[Arc-length method]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Rate_of_convergence