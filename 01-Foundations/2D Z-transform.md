---
title: "2D Z-transform"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/2D_Z-transform"
wikipedia_categories: ["Digital signal processing", "Multidimensional signal processing"]
related: ["[[Fast Algorithms for Multidimensional Signals]]", "[[Multidimensional sampling]]", "[[Multidimensional spectral estimation]]", "[[Two-dimensional filter]]", "[[2D adaptive filters]]", "[[Adaptive beamformer]]", "[[Adaptive equalizer]]", "[[Adaptive filter]]", "[[Adaptive predictive coding]]", "[[Adaptive-additive algorithm]]"]
---

# 2D Z-transform

The 2D Z-transform, similar to the Z-transform, is used in multidimensional signal processing to relate a two-dimensional discrete-time signal to the complex frequency domain in which the 2D surface in 4D space that the Fourier transform lies on is known as the unit surface or unit bicircle. The 2D Z-transform is defined by

  
    
      
        
          X
          
            z
          
        
        
          z
          
            1
          
        
        ,
        
          z
          
            2
          
        
        =
        
          ∑
          
            
              n
              
                1
              
            
            0
          
          
            ∞
          
        
        
          ∑
          
            
              n
              
                2
              
            
            0
          
          
            ∞
          
        
        x
        
          n
          
            1
          
        
        ,
        
          n
          
            2
          
        
        
          z
          
            1
          
          
            
              n
              
                1
              
            
          
        
        
          z
          
            2
          
          
            
              n
              
                2
              
            
          
        
      
    
    
  

where 
  
    
      
        
          n
          
            1
          
        
        ,
        
          n
          
            2
          
        
      
    
    
  
 are integers and 
  
    
      
        
          z
          
            1
          
        
        ,
        
          z
          
            2
          
        
      
    
    
  
 are represented by the complex numbers:

  
    
      
        
          z
          
            1
          
        
        A
        
          e
          
            j
            
              ϕ
              
                1
              
            
          
        
        A
        cos
         
        
          
            ϕ
            
              1
            
          
        
        j
         
        
          
            ϕ
            
              1
            
          
        
        
      
    
    
  

  
    
      
        
          z
          
            2
          
        
        B
        
          e
          
            j
            
              ϕ
              
                2
              
            
          
        
        B
        cos
         
        
          
            ϕ
            
              2
            
          
        
        j
         
        
          
            ϕ
            
              2
            
          
        
        
      
    
    
  

The 2D Z-transform is a generalized version of the 2D Fourier transform. It converges for a much wider class of sequences, and is a helpful tool in allowing one to draw conclusions on system characteristics such as BIBO stability. It is also used to determine the connection between the input and output of a linear shift-invariant system, such as manipulating a difference equation to determine the system's transfer function.

## Related

- [[Fast Algorithms for Multidimensional Signals]]
- [[Multidimensional sampling]]
- [[Multidimensional spectral estimation]]
- [[Two-dimensional filter]]
- [[2D adaptive filters]]
- [[Adaptive beamformer]]
- [[Adaptive equalizer]]
- [[Adaptive filter]]
- [[Adaptive predictive coding]]
- [[Adaptive-additive algorithm]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/2D_Z-transform