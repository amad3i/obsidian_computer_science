---
title: "Number theoretic Hilbert transform"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Number_theoretic_Hilbert_transform"
wikipedia_categories: ["Signal processing"]
related: ["[[Adaptive beamformer]]", "[[Adjacent channel power ratio]]", "[[Algebraic signal processing]]", "[[Aliasing]]", "[[Ambiguity function]]", "[[Analog signal processing]]", "[[Analytic signal]]", "[[Angle of arrival]]", "[[Apodization]]", "[[Argument (complex analysis)]]"]
---

# Number theoretic Hilbert transform

The number theoretic Hilbert transform is an extension of the discrete Hilbert transform to integers modulo a prime 
  
    
      
        p
      
    
    
  
.  The transformation operator is a circulant matrix.
The number theoretic transform is meaningful in the ring 
  
    
      
        
          
            Z
          
          
            m
          
        
      
    
    
  
, when the modulus 
  
    
      
        m
      
    
    
  
 is  not prime, provided a principal root of order n exists. 
The 
  
    
      
        n
        n
      
    
    
  
 NHT matrix, where 
  
    
      
        n
        2
        m
      
    
    
  
, has the form

  
    
      
        N
        H
        T
        
          
            
              
                
                  0
                
                
                  
                    a
                    
                      m
                    
                  
                
                
                  …
                
                
                  0
                
                
                  
                    a
                    
                      1
                    
                  
                
              
              
                
                  
                    a
                    
                      1
                    
                  
                
                
                  0
                
                
                  
                    a
                    
                      m
                    
                  
                
                
                
                  0
                
              
              
                
                  ⋮
                
                
                  
                    a
                    
                      1
                    
                  
                
                
                  0
                
                
                  ⋱
                
                
                  ⋮
                
              
              
                
                  0
                
                
                
                  ⋱
                
                
                  ⋱
                
                
                  
                    a
                    
                      m
                    
                  
                
              
              
                
                  
                    a
                    
                      m
                    
                  
                
                
                  0
                
                
                  …
                
                
                  
                    a
                    
                      1
                    
                  
                
                
                  0
                
              
            
          
        
        .
      
    
    
  

The rows are the cyclic permutations of the first row, or the columns may be seen as the cyclic permutations of the first column. The NHT is its own inverse:
  
    
      
        N
        H
        
          T
          
            
              T
            
          
        
        N
        H
        T
        N
        H
        T
        N
        H
        
          T
          
            
              T
            
          
        
        I
        
          mod
          
             
          
        
        p
        ,
        
      
    
    
  
 where I is the identity matrix.
The number theoretic Hilbert transform can be used to generate sets of orthogonal discrete sequences that have applications in signal processing, wireless systems, and cryptography. Other ways to generate constrained orthogonal sequences also exist.

## Related

- [[Adaptive beamformer]]
- [[Adjacent channel power ratio]]
- [[Algebraic signal processing]]
- [[Aliasing]]
- [[Ambiguity function]]
- [[Analog signal processing]]
- [[Analytic signal]]
- [[Angle of arrival]]
- [[Apodization]]
- [[Argument (complex analysis)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Number_theoretic_Hilbert_transform