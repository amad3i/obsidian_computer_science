---
title: "Half-band filter"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Half-band_filter"
wikipedia_categories: ["Digital signal processing", "Signal processing"]
related: ["[[Aliasing]]", "[[Beta encoder]]", "[[BIBO stability]]", "[[Delay equalization]]", "[[Digital down converter]]", "[[Downsampling (signal processing)]]", "[[First-order hold]]", "[[Instantaneous phase and frequency]]", "[[Least-squares spectral analysis]]", "[[Linear time-invariant system]]"]
---

# Half-band filter

A half-band filter is a finite impulse response (FIR) low-pass filter that reduces the maximum bandwidth of sampled data by a factor of 2 (one octave).  When multiple octaves of reduction are needed, a cascade of half-band filters is common.  And when the goal is downsampling, each half-band filter needs to compute only half as many output samples as input samples. In digital signal processing, half-band filters are widely used for their efficiency in multi-rate applications.
It follows from the filter's definition that its transition region, or skirt, can be centered at frequency  
  
    
      
        
          f
          
            s
          
        
        
          /
        
        4
        ,
      
    
    
  
  where  
  
    
      
        
          f
          
            s
          
        
      
    
    
  
  is the input sample-rate.  That makes it possible to design a FIR filter whose every other coefficient is zero, and whose non-zero coefficients are symmetrical about the center of the impulse response.  (See Finite impulse response § Window design method)  Both of those properties can be used to improve efficiency of the implementation.

## Related

- [[Aliasing]]
- [[Beta encoder]]
- [[BIBO stability]]
- [[Delay equalization]]
- [[Digital down converter]]
- [[Downsampling (signal processing)]]
- [[First-order hold]]
- [[Instantaneous phase and frequency]]
- [[Least-squares spectral analysis]]
- [[Linear time-invariant system]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Half-band_filter