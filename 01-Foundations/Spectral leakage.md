---
title: "Spectral leakage"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Spectral_leakage"
wikipedia_categories: ["Digital signal processing", "Fourier analysis", "Spectrum (physical sciences)"]
related: ["[[Slepian function]]", "[[Almost periodic function]]", "[[DFT matrix]]", "[[Dirac delta function]]", "[[Discrete cosine transform]]", "[[Discrete Fourier transform]]", "[[Discrete-time Fourier transform]]", "[[Fourier analysis]]", "[[Instantaneous phase and frequency]]", "[[Non-uniform discrete Fourier transform]]"]
---

# Spectral leakage

The Fourier transform of a function of time, 
  
    
      
        s
        t
      
    
    
  
, is a complex-valued function of frequency, 
  
    
      
        S
        f
      
    
    
  
, often referred to as a frequency spectrum.  Any linear time-invariant operation on 
  
    
      
        s
        t
      
    
    
  
 produces a new spectrum of the form 
  
    
      
        H
        f
        ∗
        S
        f
      
    
    
  
, which changes the relative magnitudes and/or angles (phase) of the non-zero values of 
  
    
      
        S
        f
      
    
    
  
.  Any other type of operation creates new frequency components that may be referred to as spectral leakage in the broadest sense.  Sampling, for instance, produces leakage, which we call aliases of the original spectral component.  For Fourier transform purposes, sampling is modeled as a product between 
  
    
      
        s
        t
      
    
    
  
 and a Dirac comb function.  The spectrum of a product is the convolution between 
  
    
      
        S
        f
      
    
    
  
 and another function, which inevitably creates the new frequency components.  But the term 'leakage' usually refers to the effect of windowing, which is the product of 
  
    
      
        s
        t
      
    
    
  
 with a different kind of function, the window function.  Window functions happen to have finite duration, but that is not necessary to create leakage.  Multiplication by a time-variant function is sufficient.

## Related

- [[Slepian function]]
- [[Almost periodic function]]
- [[DFT matrix]]
- [[Dirac delta function]]
- [[Discrete cosine transform]]
- [[Discrete Fourier transform]]
- [[Discrete-time Fourier transform]]
- [[Fourier analysis]]
- [[Instantaneous phase and frequency]]
- [[Non-uniform discrete Fourier transform]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Spectral_leakage