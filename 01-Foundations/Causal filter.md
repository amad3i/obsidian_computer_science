---
title: "Causal filter"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Causal_filter"
wikipedia_categories: ["Filter theory", "Signal processing"]
related: ["[[Comb filter]]", "[[Filter (signal processing)]]", "[[Sinc filter]]", "[[Washout filter]]", "[[Adaptive beamformer]]", "[[Adjacent channel power ratio]]", "[[Algebraic signal processing]]", "[[Aliasing]]", "[[Alpha beta filter]]", "[[Ambiguity function]]"]
---

# Causal filter

In signal processing, a causal filter is a linear time-invariant (LTI) causal system. The word causal indicates that the filter output depends only on past and present inputs. A filter whose output depends partly or fully on future inputs is non-causal (also, acausal), whereas a filter whose output depends only on future inputs is anti-causal. Systems (including filters) that are realizable (i.e., that operate in real time) must be causal because such systems cannot act on a future input.  In effect that means the output sample that best represents the input at time 
  
    
      
        t
        ,
      
    
    
  
 comes out slightly later.
A common design practice for digital filters is to create a realizable filter by shortening and/or time-shifting a non-causal impulse response.  If shortening is necessary, it is often accomplished by defining the shortened impulse response as the product of the non-causal impulse-response with a window function.
An example of an anti-causal filter is a maximum phase filter, which can be defined as a stable, anti-causal filter whose inverse is also stable and anti-causal.

## Related

- [[Comb filter]]
- [[Filter (signal processing)]]
- [[Sinc filter]]
- [[Washout filter]]
- [[Adaptive beamformer]]
- [[Adjacent channel power ratio]]
- [[Algebraic signal processing]]
- [[Aliasing]]
- [[Alpha beta filter]]
- [[Ambiguity function]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Causal_filter