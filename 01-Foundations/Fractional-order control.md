---
title: "Fractional-order control"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Fractional-order_control"
wikipedia_categories: ["Applied mathematics stubs", "Control theory", "Cybernetics"]
related: ["[[Advanced process control]]", "[[Affect control theory]]", "[[Artstein's theorem]]", "[[Control reconfiguration]]", "[[Input shaping]]", "[[Integral sliding mode]]", "[[Intermittent control]]", "[[Machine learning control]]", "[[Minimal realization]]", "[[Negative feedback]]"]
---

# Fractional-order control

Fractional-order control (FOC) is a field of control theory that uses the fractional-order integrator as part of the control system design toolkit. Using fractional calculus can improve and generalize well-established control methods and strategies.
The fundamental advantage of FOC is that the fractional-order integrator weights history using a function that decays with a power-law tail. The effect is that the effects of all time are computed for each iteration of the control algorithm, creating a "distribution of time constants," the upshot of which is that there is no particular time constant, or resonance frequency for the system.
In fact, the fractional integral operator 
  
    
      
        
          
            1
            
              s
              
                λ
              
            
          
        
      
    
    
  
 is different from any integer-order rational transfer function 
  
    
      
        
          
            G
            
              I
            
          
        
        s
      
    
    
  
. It is a non-local operator that possesses an infinite memory and considers the whole history of its input signal.
Fractional-order control shows promise in many controlled environments that suffer from the classical problems of overshoot, resonance and time-diffuse applications such as thermal dissipation and chemical mixing. Fractional-order control has also been demonstrated to suppress chaotic behaviors in mathematical models of, for example, muscular blood vessels and robotics.
Initiated in the 1980s by the Pr. Oustaloup's group, the CRONE approach, is one of the most developed control-system design methodologies that uses fractional-order operator properties.

## Related

- [[Advanced process control]]
- [[Affect control theory]]
- [[Artstein's theorem]]
- [[Control reconfiguration]]
- [[Input shaping]]
- [[Integral sliding mode]]
- [[Intermittent control]]
- [[Machine learning control]]
- [[Minimal realization]]
- [[Negative feedback]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Fractional-order_control