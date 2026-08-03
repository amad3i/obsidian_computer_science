---
title: "Sombrero function"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Sombrero_function"
wikipedia_categories: ["Signal processing"]
related: ["[[Adaptive beamformer]]", "[[Adjacent channel power ratio]]", "[[Algebraic signal processing]]", "[[Aliasing]]", "[[Ambiguity function]]", "[[Analog signal processing]]", "[[Analytic signal]]", "[[Angle of arrival]]", "[[Apodization]]", "[[Argument (complex analysis)]]"]
---

# Sombrero function

A sombrero function (sometimes called besinc function or jinc function) is the 2-dimensional polar coordinate analog of the sinc function, and is so-called because it is shaped like a sombrero hat.  This function is frequently used in image processing. It can be defined through the Bessel function of the first kind (
  
    
      
        
          J
          
            1
          
        
      
    
    
  
) where ρ2 = x2 + y2.

  
    
      
        somb
         
        ρ
        =
        
          
            
              2
              
                J
                
                  1
                
              
              π
              ρ
            
            
              π
              ρ
            
          
        
        .
      
    
    
  

The normalization factor 2 makes somb(0) = 1. Sometimes the π factor is omitted, giving the following alternative definition:

  
    
      
        somb
         
        ρ
        =
        
          
            
              2
              
                J
                
                  1
                
              
              ρ
            
            ρ
          
        
        .
      
    
    
  

The factor of 2 is also often omitted, giving yet another definition and causing the function maximum to be 0.5:

  
    
      
        somb
         
        ρ
        =
        
          
            
              
                J
                
                  1
                
              
              ρ
            
            ρ
          
        
        .
      
    
    
  

The Fourier transform of the 2D circle function (
  
    
      
        circ
         
        ρ
      
    
    
  
) is a sombrero function. Thus a sombrero function also appears in the intensity profile of far-field diffraction through a circular aperture, known as an Airy disk.

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

- Wikipedia: https://en.wikipedia.org/wiki/Sombrero_function