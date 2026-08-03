---
title: "Schlick's approximation"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Schlick's_approximation"
wikipedia_categories: ["3D computer graphics", "Computer graphics stubs"]
related: ["[[Geometry Engine]]", "[[Geometry instancing]]", "[[Image plane]]", "[[Mesh parameterization]]", "[[Micropolygon]]", "[[Newell's algorithm]]", "[[Polygon soup]]", "[[Relief mapping (computer graphics)]]", "[[Retopology]]", "[[Specularity]]"]
---

# Schlick's approximation

In 3D computer graphics, Schlick’s approximation, named after Christophe Schlick, is a formula for approximating the contribution of the Fresnel factor in the specular reflection of light from a non-conducting interface (surface) between two media.
According to Schlick’s model, the specular reflection coefficient R can be approximated by:

  
    
      
        R
        θ
        =
        
          R
          
            0
          
        
        (
        1
        
          R
          
            0
          
        
        (
        1
        cos
         
        θ
        
          
            5
          
        
      
    
    
  
 where 
  
    
      
        
          R
          
            0
          
        
        
          
            
              
                
                  
                    n
                    
                      1
                    
                  
                  
                    n
                    
                      2
                    
                  
                
                
                  
                    n
                    
                      1
                    
                  
                  
                    n
                    
                      2
                    
                  
                
              
            
          
          
            2
          
        
      
    
    
  

where 
  
    
      
        θ
      
    
    
  
 is, depending on usage, either half of the angle between the incoming and outgoing light vectors, or the angle between the surface normal and the light or view vector. And 
  
    
      
        
          n
          
            1
          
        
        ,
        
        
          n
          
            2
          
        
      
    
    
  
 are the indices of refraction of the two media at the interface and 
  
    
      
        
          R
          
            0
          
        
      
    
    
  
 is the reflection coefficient for light incoming parallel to the normal (i.e., the value of the Fresnel term when 
  
    
      
        θ
        0
      
    
    
  
 or minimal reflection). In computer graphics, one medium is usually air, meaning that 
  
    
      
        
          n
          
            1
          
        
      
    
    
  
 can be approximated very well as 1.
In microfacet models it is assumed that there is always a perfect reflection, but that the normal changes according to a certain distribution, resulting in a non-perfect overall reflection. When using Schlick’s approximation as an energy conservation weighting term, the normal in the above computation is replaced by the halfway vector. Either the viewing or light direction can be used as the second vector.

## Related

- [[Geometry Engine]]
- [[Geometry instancing]]
- [[Image plane]]
- [[Mesh parameterization]]
- [[Micropolygon]]
- [[Newell's algorithm]]
- [[Polygon soup]]
- [[Relief mapping (computer graphics)]]
- [[Retopology]]
- [[Specularity]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Schlick's_approximation