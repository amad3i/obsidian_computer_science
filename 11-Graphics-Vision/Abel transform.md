---
title: "Abel transform"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Abel_transform"
wikipedia_categories: ["Image processing", "Integral transforms", "Niels Henrik Abel"]
related: ["[[List of Fourier-related transforms]]", "[[Projection-slice theorem]]", "[[3D selfie]]", "[[ActionShot]]", "[[Acutance]]", "[[Adaptive histogram equalization]]", "[[Albert Bijaoui]]", "[[Alpha to coverage]]", "[[Analog image processing]]", "[[Anisotropic diffusion]]"]
---

# Abel transform

In mathematics, the Abel transform, named for Niels Henrik Abel, is an integral transform often used in the analysis of spherically symmetric or axially symmetric functions. The Abel transform of a function f(r) is given by

  
    
      
        F
        y
        =
        2
        
          ∫
          
            y
          
          
            ∞
          
        
        
          
            
              f
              r
              r
            
            
              
                r
                
                  2
                
              
              
                y
                
                  2
                
              
            
          
        
        
        d
        r
        .
      
    
    
  

Assuming that f(r) drops to zero more quickly than ⁠1/r⁠, the inverse Abel transform is given by

  
    
      
        f
        r
        =
        
          
            1
            π
          
        
        
          ∫
          
            r
          
          
            ∞
          
        
        
          
            
              d
              F
            
            
              d
              y
            
          
        
        
        
          
            
              d
              y
            
            
              
                y
                
                  2
                
              
              
                r
                
                  2
                
              
            
          
        
        .
      
    
    
  

In image analysis, the forward Abel transform is used to project an optically thin, axially symmetric emission function onto a plane, and the inverse Abel transform is used to calculate the emission function given a projection (i.e. a scan or a photograph) of that emission function.
In absorption spectroscopy of cylindrical flames or plumes, the forward Abel transform is the integrated absorbance along a ray with closest distance y from the center of the flame, while the inverse Abel transform gives the local absorption coefficient at a distance r from the center. Abel transform is limited to applications with axially symmetric geometries. For more general asymmetrical cases, more general-oriented reconstruction algorithms such as algebraic reconstruction technique (ART), maximum likelihood expectation maximization (MLEM), filtered back-projection (FBP) algorithms should be employed.
In recent years, the inverse Abel transform (and its variants) has become the cornerstone of data analysis in photofragment-ion imaging and photoelectron imaging. Among recent most notable extensions of inverse Abel transform are the "onion peeling" and "basis set expansion" (BASEX) methods of photoelectron and photoion image analysis.

## Related

- [[List of Fourier-related transforms]]
- [[Projection-slice theorem]]
- [[3D selfie]]
- [[ActionShot]]
- [[Acutance]]
- [[Adaptive histogram equalization]]
- [[Albert Bijaoui]]
- [[Alpha to coverage]]
- [[Analog image processing]]
- [[Anisotropic diffusion]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Abel_transform