---
title: "Minimum polynomial extrapolation"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Minimum_polynomial_extrapolation"
wikipedia_categories: ["Mathematical analysis stubs", "Numerical analysis"]
related: ["[[Bi-directional delay line]]", "[[Blossom (functional)]]", "[[Equioscillation theorem]]", "[[Guard digit]]", "[[Local convergence]]", "[[Sigma approximation]]", "[[Sparse grid]]", "[[2Sum]]", "[[Abramowitz and Stegun]]", "[[Adaptive step size]]"]
---

# Minimum polynomial extrapolation

In mathematics, minimum polynomial extrapolation is a sequence transformation used for convergence acceleration of vector sequences, due to Cabay and Jackson.
While Aitken's method is the most famous, it often fails for vector sequences. An effective method for vector sequences is the minimum polynomial extrapolation. It is usually phrased in terms of the fixed point iteration:

  
    
      
        
          x
          
            k
            1
          
        
        f
        
          x
          
            k
          
        
        .
      
    
    
  

Given iterates 
  
    
      
        
          x
          
            1
          
        
        ,
        
          x
          
            2
          
        
        ,
        .
        .
        .
        ,
        
          x
          
            k
          
        
      
    
    
  
 in 
  
    
      
        
          
            R
          
          
            n
          
        
      
    
    
  
, one constructs the 
  
    
      
        n
        (
        k
        1
      
    
    
  
 matrix 
  
    
      
        U
        (
        
          x
          
            2
          
        
        
          x
          
            1
          
        
        ,
        
          x
          
            3
          
        
        
          x
          
            2
          
        
        ,
        .
        .
        .
        ,
        
          x
          
            k
          
        
        
          x
          
            k
            1
          
        
      
    
    
  
 whose columns are the 
  
    
      
        k
        1
      
    
    
  
 differences. Then, one computes the vector 
  
    
      
        c
        −
        
          U
          
          
        
        
          x
          
            k
            1
          
        
        
          x
          
            k
          
        
      
    
    
  
 where 
  
    
      
        
          U
          
          
        
      
    
    
  
 denotes the Moore–Penrose pseudoinverse of 
  
    
      
        U
      
    
    
  
. The number 1 is then appended to the end of 
  
    
      
        c
      
    
    
  
, and the extrapolated limit is

  
    
      
        s
        
          
            
              X
              c
            
            
              
                ∑
                
                  i
                  1
                
                
                  k
                
              
              
                c
                
                  i
                
              
            
          
        
        ,
      
    
    
  

where 
  
    
      
        X
        (
        
          x
          
            2
          
        
        ,
        
          x
          
            3
          
        
        ,
        .
        .
        .
        ,
        
          x
          
            k
            1
          
        
      
    
    
  
 is the matrix whose columns are the 
  
    
      
        k
      
    
    
  
 iterates starting at 2.
The following 4 line MATLAB code segment implements the MPE algorithm:

## Related

- [[Bi-directional delay line]]
- [[Blossom (functional)]]
- [[Equioscillation theorem]]
- [[Guard digit]]
- [[Local convergence]]
- [[Sigma approximation]]
- [[Sparse grid]]
- [[2Sum]]
- [[Abramowitz and Stegun]]
- [[Adaptive step size]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Minimum_polynomial_extrapolation