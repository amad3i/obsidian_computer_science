---
title: "Hilbert spectral analysis"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Hilbert_spectral_analysis"
wikipedia_categories: ["Signal processing"]
related: ["[[Adaptive beamformer]]", "[[Adjacent channel power ratio]]", "[[Algebraic signal processing]]", "[[Aliasing]]", "[[Ambiguity function]]", "[[Analog signal processing]]", "[[Analytic signal]]", "[[Angle of arrival]]", "[[Apodization]]", "[[Argument (complex analysis)]]"]
---

# Hilbert spectral analysis

Hilbert spectral analysis is a signal analysis method applying the Hilbert transform to compute the instantaneous frequency of signals according to

  
    
      
        ω
        
          
            
              d
              θ
              t
            
            
              d
              t
            
          
        
        .
        
      
    
    
  

After performing the Hilbert transform on each signal, we can express the data in the following form:

  
    
      
        X
        t
        =
        
          ∑
          
            j
            1
          
          
            n
          
        
        
          a
          
            j
          
        
        t
        exp
         
        
          
            i
            ∫
            
              ω
              
                j
              
            
            t
            d
            t
          
        
        .
        
      
    
    
  

This equation gives both the amplitude and the frequency of each component as functions of time. It also enables us to represent the amplitude and the instantaneous frequency as functions of time in a three-dimensional plot, in which the amplitude can be contoured on the frequency-time plane. This frequency-time distribution of the amplitude is designated as the Hilbert amplitude spectrum, or simply Hilbert spectrum.
Hilbert spectral analysis method is an important part of the Hilbert–Huang transform.

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

- Wikipedia: https://en.wikipedia.org/wiki/Hilbert_spectral_analysis