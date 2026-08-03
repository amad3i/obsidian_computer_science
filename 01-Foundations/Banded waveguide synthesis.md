---
title: "Banded waveguide synthesis"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Banded_waveguide_synthesis"
wikipedia_categories: ["Digital signal processing", "Sound production technology", "Sound synthesis types"]
related: ["[[Outboard gear]]", "[[2D adaptive filters]]", "[[2D Z-transform]]", "[[Adaptive equalizer]]", "[[Adaptive filter]]", "[[Adaptive predictive coding]]", "[[Adaptive-additive algorithm]]", "[[Adjoint filter]]", "[[Advanced process control]]", "[[Aliasing]]"]
---

# Banded waveguide synthesis

Banded waveguides synthesis is a physical modeling synthesis method to simulate sounds of dispersive sounding objects, or objects with strongly inharmonic resonant frequencies efficiently. It can be used to model the sound of musical instruments based on elastic solids such as vibraphone and marimba bars, singing bowls and bells. It can also be used for other instruments with inharmonic partials, such as membranes or plates. For example, simulations of tabla drums and cymbals have been implemented using this method. Because banded waveguides retain the dynamics of the system, complex non-linear excitations can be implemented. The method was originally invented in 1999 by Georg Essl and Perry Cook to synthesize the sound of bowed vibraphone bars.
In the case of the standard one-dimensional wave equation 
  
    
      
        
          y
          
            t
            t
          
        
        
          c
          
            2
          
        
        
          y
          
            x
            x
          
        
      
    
    
  
 disturbances of all frequencies travel with the same constant speed 
  
    
      
        c
      
    
    
  
. In dispersive media, the traveling speed of disturbances depends on their frequency, and we get 
  
    
      
        c
        ω
      
    
    
  
, where 
  
    
      
        ω
      
    
    
  
 is the frequency of the disturbance. Many physical systems are dispersive, for example, the elastic beams described by the Euler–Bernoulli beam equation 
  
    
      
        
          y
          
            t
            t
          
        
        k
        
          y
          
            x
            x
            x
            x
          
        
      
    
    
  
, where 
  
    
      
        k
      
    
    
  
 is a material constant.
Banded waveguides model dispersive behavior by splitting the propagation of disturbances into frequency bands. Each frequency band is modeled using a band-limited version of the standard digital waveguide method. Each frequency band is tuned to the resonant frequencies of the sounding object to be modeled to avoid any discretization error at the dominant and audible frequencies.
Banded waveguide synthesis is implemented in most available sound-synthesis libraries and programs such as:

STK
ChucK
pd and Max/MSP via PerCoLate
RTCMix
SuperCollider
CSound
Common Lisp Music

## Related

- [[Outboard gear]]
- [[2D adaptive filters]]
- [[2D Z-transform]]
- [[Adaptive equalizer]]
- [[Adaptive filter]]
- [[Adaptive predictive coding]]
- [[Adaptive-additive algorithm]]
- [[Adjoint filter]]
- [[Advanced process control]]
- [[Aliasing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Banded_waveguide_synthesis