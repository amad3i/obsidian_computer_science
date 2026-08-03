---
title: "Projection-slice theorem"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Projection-slice_theorem"
wikipedia_categories: ["Image processing", "Integral transforms", "Theorems in Fourier analysis"]
related: ["[[Abel transform]]", "[[List of Fourier-related transforms]]", "[[3D selfie]]", "[[ActionShot]]", "[[Acutance]]", "[[Adaptive histogram equalization]]", "[[Albert Bijaoui]]", "[[Alpha to coverage]]", "[[Analog image processing]]", "[[Anisotropic diffusion]]"]
---

# Projection-slice theorem

In mathematics, the projection-slice theorem, central slice theorem or Fourier slice theorem in two dimensions states that the results of the following two calculations are equal:

Take a two-dimensional function f(r), project (e.g. using the Radon transform) it onto a (one-dimensional) line, and do a Fourier transform of that projection.
Take that same function, but do a two-dimensional Fourier transform first, and then slice the function through its origin, parallel to the projection line.
In operator terms, if

F1 and  F2 are the 1- and 2-dimensional Fourier transform operators mentioned above,
P1 is the projection operator (which projects a 2-D function onto a 1-D line),
S1 is a slice operator (which extracts a 1-D central slice from a function),
then

  
    
      
        
          F
          
            1
          
        
        
          P
          
            1
          
        
        
          S
          
            1
          
        
        
          F
          
            2
          
        
        .
      
    
    
  

This idea can be extended to higher dimensions.
This theorem is used, for example, in the analysis of medical
CT scans where a "projection" is an x-ray
image of an internal organ. The Fourier transforms of these images are
seen to be slices through the Fourier transform of the 3-dimensional
density of the internal organ, and these slices can be interpolated to build
up a complete Fourier transform of that density. The inverse Fourier transform
is then used to recover the 3-dimensional density of the object. This technique was first derived by Ronald N. Bracewell in 1956 for a radio-astronomy problem.

## Related

- [[Abel transform]]
- [[List of Fourier-related transforms]]
- [[3D selfie]]
- [[ActionShot]]
- [[Acutance]]
- [[Adaptive histogram equalization]]
- [[Albert Bijaoui]]
- [[Alpha to coverage]]
- [[Analog image processing]]
- [[Anisotropic diffusion]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Projection-slice_theorem