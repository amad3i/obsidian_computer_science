---
title: "Tapering (mathematics)"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Tapering_(mathematics)"
wikipedia_categories: ["Functions and mappings", "Linear algebra"]
related: ["[[3D projection]]", "[[Antilinear map]]", "[[Locally finite operator]]", "[[Rotation of axes in two dimensions]]", "[[Semilinear map]]", "[[Translation of axes]]", "[[Absolutely convex set]]", "[[Adjugate matrix]]", "[[Affine space]]", "[[Amitsur–Levitzki theorem]]"]
---

# Tapering (mathematics)

In mathematics, physics, and theoretical computer graphics, tapering is a kind of shape deformation. Just as an affine transformation, such as scaling or shearing, is a first-order model of shape deformation, tapering is a higher order deformation just as twisting and bending. Tapering can be thought of as non-constant scaling by a given tapering function. The resultant deformations can be linear or nonlinear.
To create a nonlinear taper, instead of scaling in x and y for all z with constants as in:

  
    
      
        q
        
          
            
              
                
                  a
                
                
                  0
                
                
                  0
                
              
              
                
                  0
                
                
                  b
                
                
                  0
                
              
              
                
                  0
                
                
                  0
                
                
                  1
                
              
            
          
        
        p
        ,
      
    
    
  

let a and b be functions of z so that:

  
    
      
        q
        
          
            
              
                
                  a
                  
                    p
                    
                      z
                    
                  
                
                
                  0
                
                
                  0
                
              
              
                
                  0
                
                
                  b
                  
                    p
                    
                      z
                    
                  
                
                
                  0
                
              
              
                
                  0
                
                
                  0
                
                
                  1
                
              
            
          
        
        p
        .
      
    
    
  

An example of a linear taper is 
  
    
      
        a
        z
        =
        
          α
          
            0
          
        
        
          α
          
            1
          
        
        z
      
    
    
  
, and a quadratic taper 
  
    
      
        a
        z
        =
        
          
            α
          
          
            0
          
        
        
          
            α
          
          
            1
          
        
        z
        
          
            α
          
          
            2
          
        
        
          z
          
            2
          
        
      
    
    
  
.
As another example, if the parametric equation of a cube were given by ƒ(t) = (x(t), y(t), z(t)), a nonlinear taper could be applied so that the cube's volume slowly decreases (or tapers) as the function moves in the positive z direction. For the given cube, an example of a nonlinear taper along z would be if, for instance, the function T(z) = 1/(a + bt) were applied to the cube's equation such that ƒ(t) = (T(z)x(t), T(z)y(t), T(z)z(t)), for some real constants a and b.

## Related

- [[3D projection]]
- [[Antilinear map]]
- [[Locally finite operator]]
- [[Rotation of axes in two dimensions]]
- [[Semilinear map]]
- [[Translation of axes]]
- [[Absolutely convex set]]
- [[Adjugate matrix]]
- [[Affine space]]
- [[Amitsur–Levitzki theorem]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Tapering_(mathematics)