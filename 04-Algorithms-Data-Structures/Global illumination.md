---
title: "Global illumination"
tags: ["cs", "algorithms-data-structures", "core"]
domain: Algorithms & Data Structures
level: core
source: "https://en.wikipedia.org/wiki/Global_illumination"
wikipedia_categories: ["Global illumination algorithms"]
related: ["[[Cone tracing]]", "[[Distributed ray tracing]]", "[[Path tracing]]", "[[Per-pixel lighting]]", "[[Photon mapping]]", "[[Radiosity (computer graphics)]]", "[[Ray tracing (graphics)]]", "[[Screen space directional occlusion]]", "[[Spatiotemporal reservoir resampling]]"]
---

# Global illumination

Global illumination (GI), or indirect illumination, refers to a group of algorithms used in 3D computer graphics meant to add more realistic lighting to 3D scenes. Such algorithms take into account not only the light that comes directly from a light source (direct illumination), but also subsequent "bounces" where light rays are reflected by other surfaces in the scene (indirect illumination).
The term "global illumination" was first used by Turner Whitted in his paper "An improved illumination model for shaded display", to differentiate between illumination calculations at a local scale (using geometric information directly, such as in Phong shading), a microscopic scale (extending local geometry with microfacet detail), and a global scale, including not only the geometry itself but also the visibility of every other object in the scene. Theoretically, reflections, refractions, transparency, and shadows are all examples of global illumination, because when simulating them, one object affects the rendering of another (as opposed to an object being affected only by a direct source of light). In practice, however, only the simulation of diffuse inter-reflection or caustics is called global illumination, especially in real-time settings.

== Algorithms ==
Global illumination is a key aspect to the realism of a 3D scene. Naive 3D lighting will only take into account direct light, meaning any light which radiates off a light source and bounces directly into the virtual camera. Shadows will appear completely dark, due to light not interacting with any other surface before it reaches the camera. As this is not what occurs in real life, we perceive the resulting image as incomplete. Applying full global illumination allows for the missing effects that makes an image feel more natural. However, global illumination is computationally more expensive and consequently much slower to generate.Most algorithms, especially those focusing on real-time solutions, model diffuse inter-reflection exclusively, which is a very important part of global illumination; however, some also model indirect specular reflections, refraction, and indirect shadowing, which allows for a closer approximation of the reality and produces more appealing images. The algorithms used to calculate the distribution of light energy between surfaces of a scene are closely related to heat transfer simulations performed using finite-element methods in engineering design.
Radiosity, ray tracing, beam tracing, cone tracing, path tracing, Metropolis light transport and photon mapping are all examples of algorithms used for global illumination in offline settings, some of which may be used together to yield results that trade between accuracy and speed, depending on the implementation.

== Real-time applications ==

Achieving accurate computation of global illumination in real-time remains difficult. On one end, the diffuse inter-reflection component of global illumination is sometimes approximated by an "ambient" term in the lighting equation, which is also called "ambient lighting" or "ambient color" in 3D software. Though this method is one of the cheapest ways to simulate indirect lighting, when used alone it does not provide an adequately realistic effect. Ambient lighting is known to "flatten" shadows in 3D scenes, making the overall visual effect more bland. Beyond ambient lighting, techniques which trace the path of light accurately have historically been either too slow for consumer hardware or limited to static and precomputed environments. A classic real-time approach is precomputed radiance transfer, which precomputes light transport so that low-frequency lighting can be changed in real time while preserving effects such as soft shadows and interreflections, but its original form generally assumed fixed geometry and could not vary lighting and view simultaneously in real time. This proves problematic, as most applications allow for input from a user that can affect their surroundings, and the precalculation steps may introduce constraints upon the artists. Consequently, research has been dedicated to finding a balance between adequate performance, accurate visual results, and interactivity.
Starting with Nvidia's RTX 20 series, consumer graphics hardware has been extended to allow for ray tracing computations to be performed in real time through hardware acceleration. This has allowed for further improvements, as applications can now harness the power of this acceleration to provide not only precise lighting results, but the ability to affect said lighting dynamically. Some content that has taken advantage of this capability includes Cyberpunk 2077, Indiana Jones and the Great Circle, and Alan Wake 2, among others.
For an overview of the current state of real-time global illumination, see  or.

== Procedure ==
Algorithms which attempt to simulate global illumination are numerical approximations of the rendering equation. Well-known algorithms for computing global illumination include path tracing, photon mapping and radiosity. The following approaches can be distinguished here:

Inversion: 
  
    
      
        L
        (
        1
        T
        
          
            1
          
        
        
          L
          
            e
          
        
        
      
    
    
  

Not applied in practice
Expansion: 
  
    
      
        L
        
          ∑
          
            i
            0
          
          
            ∞
          
        
        
          T
          
            i
          
        
        
          L
          
            e
          
        
      
    
    
  

Bi-directional approach: Photon mapping + Distributed ray tracing, Bi-directional path tracing, Metropolis light transport
Iteration: 
  
    
      
        
          L
          
            n
          
        
        t
        
          l
          
            e
          
        
        =
        
          L
          
            n
            1
          
        
      
    
    
  

Radiosity
A full overview can be found in.

== List of methods ==

== See also ==
Rendering equation
Bias of an estimator
Bidirectional scattering distribution function
Consistent estimator
Unbiased rendering
Category:Global illumination software

== References ==

== External links ==
Video demonstrating global illumination and the ambient color effect
Collection of real-time GI techniques
Real-time GI demos – survey of practical real-time GI techniques as a list of executable demos
kuleuven - This page contains the Global Illumination Compendium, an effort to bring together most of the useful formulas and equations for global illumination algorithms in computer graphics.
Theory and practical implementation of Global Illumination using Monte Carlo Path Tracing.

## Related

- [[Cone tracing]]
- [[Distributed ray tracing]]
- [[Path tracing]]
- [[Per-pixel lighting]]
- [[Photon mapping]]
- [[Radiosity (computer graphics)]]
- [[Ray tracing (graphics)]]
- [[Screen space directional occlusion]]
- [[Spatiotemporal reservoir resampling]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Global_illumination