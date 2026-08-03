---
title: "Transfer matrix"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Transfer_matrix"
wikipedia_categories: ["Numerical analysis", "Wavelets"]
related: ["[[Discrete wavelet transform]]", "[[Multigrid method]]", "[[Scale co-occurrence matrix]]", "[[2Sum]]", "[[Abramowitz and Stegun]]", "[[Adaptive step size]]", "[[Adjoint state method]]", "[[Affine arithmetic]]", "[[Applied element method]]", "[[Approximation]]"]
---

# Transfer matrix

In applied mathematics, the transfer matrix is a formulation in terms of a block-Toeplitz matrix of the two-scale equation, which characterizes refinable functions. Refinable functions play an important role in wavelet theory and finite element theory.
For the mask 
  
    
      
        h
      
    
    
  
, which is a vector with component indexes from 
  
    
      
        a
      
    
    
  
 to 
  
    
      
        b
      
    
    
  
,
the transfer matrix of 
  
    
      
        h
      
    
    
  
, we call it 
  
    
      
        
          T
          
            h
          
        
      
    
    
  
 here, is defined as

  
    
      
        
          T
          
            h
          
        
        
          
            j
            ,
            k
          
        
        
          h
          
            2
            ⋅
            j
            k
          
        
        .
      
    
    
  

More verbosely

  
    
      
        
          T
          
            h
          
        
        
          
            
              
                
                  
                    h
                    
                      a
                    
                  
                
                
                
                
                
                
              
              
                
                  
                    h
                    
                      a
                      2
                    
                  
                
                
                  
                    h
                    
                      a
                      1
                    
                  
                
                
                  
                    h
                    
                      a
                    
                  
                
                
                
                
              
              
                
                  
                    h
                    
                      a
                      4
                    
                  
                
                
                  
                    h
                    
                      a
                      3
                    
                  
                
                
                  
                    h
                    
                      a
                      2
                    
                  
                
                
                  
                    h
                    
                      a
                      1
                    
                  
                
                
                  
                    h
                    
                      a
                    
                  
                
                
              
              
                
                  ⋱
                
                
                  ⋱
                
                
                  ⋱
                
                
                  ⋱
                
                
                  ⋱
                
                
                  ⋱
                
              
              
                
                
                  
                    h
                    
                      b
                    
                  
                
                
                  
                    h
                    
                      b
                      1
                    
                  
                
                
                  
                    h
                    
                      b
                      2
                    
                  
                
                
                  
                    h
                    
                      b
                      3
                    
                  
                
                
                  
                    h
                    
                      b
                      4
                    
                  
                
              
              
                
                
                
                
                  
                    h
                    
                      b
                    
                  
                
                
                  
                    h
                    
                      b
                      1
                    
                  
                
                
                  
                    h
                    
                      b
                      2
                    
                  
                
              
              
                
                
                
                
                
                
                  
                    h
                    
                      b
                    
                  
                
              
            
          
        
        .
      
    
    
  

The effect of 
  
    
      
        
          T
          
            h
          
        
      
    
    
  
 can be expressed in terms of the downsampling operator "
  
    
      
        ↓
      
    
    
  
":

  
    
      
        
          T
          
            h
          
        
        ⋅
        x
        (
        h
        x
        ↓
        2.
      
    
    

## Related

- [[Discrete wavelet transform]]
- [[Multigrid method]]
- [[Scale co-occurrence matrix]]
- [[2Sum]]
- [[Abramowitz and Stegun]]
- [[Adaptive step size]]
- [[Adjoint state method]]
- [[Affine arithmetic]]
- [[Applied element method]]
- [[Approximation]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Transfer_matrix