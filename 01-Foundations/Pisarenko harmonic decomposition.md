---
title: "Pisarenko harmonic decomposition"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Pisarenko_harmonic_decomposition"
wikipedia_categories: ["Digital signal processing"]
related: ["[[2D adaptive filters]]", "[[2D Z-transform]]", "[[Adaptive equalizer]]", "[[Adaptive filter]]", "[[Adaptive predictive coding]]", "[[Adaptive-additive algorithm]]", "[[Adjoint filter]]", "[[Advanced process control]]", "[[Aliasing]]", "[[All-pass filter]]"]
---

# Pisarenko harmonic decomposition

Pisarenko harmonic decomposition, also referred to as Pisarenko's method, is a method of frequency estimation. This method assumes that a signal, 
  
    
      
        x
        n
      
    
    
  
, consists of 
  
    
      
        p
      
    
    
  
 complex exponentials in the presence of white noise. Because the number of complex exponentials must be known a priori, it is somewhat limited in its usefulness.
Pisarenko's method also assumes that 
  
    
      
        p
        1
      
    
    
  
 values of the 
  
    
      
        M
        M
      
    
    
  
 autocorrelation matrix are either known or estimated. Hence, given the 
  
    
      
        p
        1
        ×
        p
        1
      
    
    
  
 autocorrelation matrix, the dimension of the noise subspace is equal to one and is spanned by the eigenvector corresponding to the minimum eigenvalue. This eigenvector is orthogonal to each of the signal vectors.
The frequency estimates may be determined by setting the frequencies equal to the angles of the roots of the polynomial

  
    
      
        
          V
          
            
              m
              i
              n
            
          
        
        z
        =
        
          ∑
          
            k
            0
          
          
            p
          
        
        
          v
          
            
              m
              i
              n
            
          
        
        k
        
          z
          
            k
          
        
      
    
    
  

or the location of the peaks in the frequency estimation function (or the pseudo-spectrum)

  
    
      
        
          
            
              
                P
                ^
              
            
          
          
            
              P
              H
              D
            
          
        
        
          e
          
            j
            ω
          
        
        =
        
          
            1
            
              
                |
              
              
                
                  e
                
                
                  H
                
              
              
                
                  v
                
                
                  
                    m
                    i
                    n
                  
                
              
              
                
                  |
                
                
                  2
                
              
            
          
        
      
    
    
  
,
where 
  
    
      
        
          
            v
          
          
            
              m
              i
              n
            
          
        
      
    
    
  
 is the noise eigenvector and

  
    
      
        e
        
          
            
              
                
                  
                    1
                  
                  
                    
                      e
                      
                        j
                        ω
                      
                    
                  
                  
                    
                      e
                      
                        j
                        2
                        ω
                      
                    
                  
                  
                    ⋯
                  
                  
                    
                      e
                      
                        j
                        M
                        1
                        ω
                      
                    
                  
                
              
            
          
          
            T
          
        
      
    
    
  
.

## Related

- [[2D adaptive filters]]
- [[2D Z-transform]]
- [[Adaptive equalizer]]
- [[Adaptive filter]]
- [[Adaptive predictive coding]]
- [[Adaptive-additive algorithm]]
- [[Adjoint filter]]
- [[Advanced process control]]
- [[Aliasing]]
- [[All-pass filter]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Pisarenko_harmonic_decomposition