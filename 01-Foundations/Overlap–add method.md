---
title: "Overlap–add method"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Overlap–add_method"
wikipedia_categories: ["Fourier analysis", "Numerical analysis", "Signal processing", "Transforms"]
related: ["[[Overlap–save method]]", "[[Short-time Fourier transform]]", "[[Analytic signal]]", "[[Basis function]]", "[[Chirplet transform]]", "[[Discrete Fourier transform]]", "[[Discrete-time Fourier transform]]", "[[Instantaneous phase and frequency]]", "[[Least-squares spectral analysis]]", "[[Linear canonical transformation]]"]
---

# Overlap–add method

In signal processing, the overlap–add method is an efficient way to evaluate the discrete convolution of a very long signal 
  
    
      
        x
        n
      
    
    
  
 with a finite impulse response (FIR) filter 
  
    
      
        h
        n
      
    
    
  
:

where 
  
    
      
        h
        m
        =
        0
      
    
    
  
 for 
  
    
      
        m
      
    
    
  
 outside the region 
  
    
      
        1
        ,
        M
        .
      
    
    
  
  
This article uses common abstract notations, such as 
  
    
      
        y
        t
        =
        x
        t
        ∗
        h
        t
        ,
      
    
    {\textstyle y(t)=x(t)*h(t),}
  
 or 
  
    
      
        y
        t
        =
        
          
            H
          
        
        x
        t
        }
        ,
      
    
    {\textstyle y(t)={\mathcal {H}}\{x(t)\},}
  
 in which it is understood that the functions should be thought of in their totality, rather than at specific instants 
  
    
      
        t
      
    
    {\textstyle t}
  
 (see Convolution#Notation).

## Related

- [[Overlap–save method]]
- [[Short-time Fourier transform]]
- [[Analytic signal]]
- [[Basis function]]
- [[Chirplet transform]]
- [[Discrete Fourier transform]]
- [[Discrete-time Fourier transform]]
- [[Instantaneous phase and frequency]]
- [[Least-squares spectral analysis]]
- [[Linear canonical transformation]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Overlap–add_method