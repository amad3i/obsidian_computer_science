---
title: "Hexagonal sampling"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Hexagonal_sampling"
wikipedia_categories: ["Computer graphics"]
related: ["[[2D computer graphics]]", "[[3D computer graphics]]", "[[3D lookup table]]", "[[4D reconstruction]]", "[[9-slice scaling]]", "[[A-buffer]]", "[[ACM Transactions on Graphics]]", "[[Adaptive tile refresh]]", "[[Bitmap textures]]", "[[Blanking (video)]]"]
---

# Hexagonal sampling

A multidimensional signal is a function of M independent variables where 
  
    
      
        M
        ≥
        2
      
    
    
  
. Real world signals, which are generally continuous time signals, have to be discretized (sampled) in order to ensure that digital systems can be used to process the signals. It is during this process of discretization where sampling comes into picture. Although there are many ways of obtaining a discrete representation of a continuous time signal, periodic sampling is by far the simplest scheme. Theoretically, sampling can be performed with respect to any set of points. But practically, sampling is carried out with respect to a set of points that have a certain algebraic structure. Such structures are called lattices. Mathematically, the process of sampling an 
  
    
      
        N
      
    
    
  
-dimensional signal can be written as:

  
    
      
        w
        
          
            
              t
              ^
            
          
        
        =
        w
        V
        .
        
          
            
              n
              ^
            
          
        
      
    
    
  

where 
  
    
      
        
          
            
              t
              ^
            
          
        
      
    
    
  
 is continuous domain M-dimensional vector (M-D) that is being sampled, 
  
    
      
        
          
            
              n
              ^
            
          
        
      
    
    
  
 is an M-dimensional integer vector corresponding to indices of a sample, and V is an 
  
    
      
        N
        N
      
    
    
  
 sampling matrix.

## Related

- [[2D computer graphics]]
- [[3D computer graphics]]
- [[3D lookup table]]
- [[4D reconstruction]]
- [[9-slice scaling]]
- [[A-buffer]]
- [[ACM Transactions on Graphics]]
- [[Adaptive tile refresh]]
- [[Bitmap textures]]
- [[Blanking (video)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Hexagonal_sampling