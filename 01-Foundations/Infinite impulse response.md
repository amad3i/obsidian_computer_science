---
title: "Infinite impulse response"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Infinite_impulse_response"
wikipedia_categories: ["Digital signal processing", "Filter theory"]
related: ["[[Filter design]]", "[[Finite impulse response]]", "[[FIR transfer function]]", "[[Impulse invariance]]", "[[Least mean squares filter]]", "[[Matched Z-transform method]]", "[[Parks–McClellan filter design algorithm]]", "[[Quadrature mirror filter]]", "[[Recursive least squares filter]]", "[[Similarities between Wiener and LMS]]"]
---

# Infinite impulse response

Infinite impulse response (IIR) is a fundamental property applying to many linear time-invariant systems that are distinguished by having an impulse response 
  
    
      
        h
        t
      
    
    
  
 that does not become exactly zero past a certain point but continues indefinitely. This is in contrast to a finite impulse response (FIR) system, in which the impulse response  does become exactly zero at times 
  
    
      
        t
        T
      
    
    
  
 for some finite 
  
    
      
        T
      
    
    
  
, thus being of finite duration. Common examples of linear time-invariant systems are most electronic and digital filters. Systems with this property are known as IIR systems or IIR filters.
In practice, the impulse response, even of IIR systems, usually approaches zero and can be neglected past a certain point. However the physical systems which give rise to IIR or FIR responses are dissimilar, and therein lies the importance of the distinction. For instance, analog electronic filters composed of resistors, capacitors, and/or inductors (and perhaps linear amplifiers) are generally IIR filters. On the other hand, discrete-time filters (usually digital filters) based on a tapped delay line employing no feedback are necessarily FIR filters. The capacitors (or inductors) in the analog filter have a "memory" and their internal state never completely relaxes following an impulse (assuming the classical model of capacitors and inductors where quantum effects are ignored). But in the latter case, after an impulse has reached the end of the tapped delay line, the system has no further memory of that impulse and has returned to its initial state; its impulse response beyond that point is exactly zero.

## Related

- [[Filter design]]
- [[Finite impulse response]]
- [[FIR transfer function]]
- [[Impulse invariance]]
- [[Least mean squares filter]]
- [[Matched Z-transform method]]
- [[Parks–McClellan filter design algorithm]]
- [[Quadrature mirror filter]]
- [[Recursive least squares filter]]
- [[Similarities between Wiener and LMS]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Infinite_impulse_response