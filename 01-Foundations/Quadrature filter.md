---
title: "Quadrature filter"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Quadrature_filter"
wikipedia_categories: ["Signal processing"]
related: ["[[Adaptive beamformer]]", "[[Adjacent channel power ratio]]", "[[Algebraic signal processing]]", "[[Aliasing]]", "[[Ambiguity function]]", "[[Analog signal processing]]", "[[Analytic signal]]", "[[Angle of arrival]]", "[[Apodization]]", "[[Argument (complex analysis)]]"]
---

# Quadrature filter

In signal processing, a quadrature filter 
  
    
      
        q
        t
      
    
    
  
 is the analytic representation of the impulse response 
  
    
      
        f
        t
      
    
    
  
 of a real-valued filter:

  
    
      
        q
        t
        =
        
          f
          
            a
          
        
        t
        =
        
          
            δ
            t
            +
            j
            δ
            j
            t
          
        
        f
        t
      
    
    
  

If the quadrature filter 
  
    
      
        q
        t
      
    
    
  
 is applied to a signal 
  
    
      
        s
        t
      
    
    
  
, the result is

  
    
      
        h
        t
        =
        q
        s
        (
        t
        =
        
          
            δ
            t
            +
            j
            δ
            j
            t
          
        
        f
        t
        ∗
        s
        t
      
    
    
  

which implies that 
  
    
      
        h
        t
      
    
    
  
 is the analytic representation of 
  
    
      
        f
        s
        (
        t
      
    
    
  
.
Since 
  
    
      
        q
      
    
    
  
 is an analytic signal, it is either zero or complex-valued.  In practice, therefore, 
  
    
      
        q
      
    
    
  
 is often implemented as two real-valued filters, which correspond to the real and imaginary parts of the filter, respectively.
An ideal quadrature filter cannot have a finite support. It has single sided support, but by choosing the (analog) function 
  
    
      
        f
        t
      
    
    
  
 carefully, it is possible to design quadrature filters which are localized such that they can be approximated by means of functions of finite support. A digital realization without feedback (FIR) has finite support.

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

- Wikipedia: https://en.wikipedia.org/wiki/Quadrature_filter