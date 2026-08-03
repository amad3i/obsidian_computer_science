---
title: "Rasta filtering"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Rasta_filtering"
wikipedia_categories: ["Signal processing"]
related: ["[[Adaptive beamformer]]", "[[Adjacent channel power ratio]]", "[[Algebraic signal processing]]", "[[Aliasing]]", "[[Ambiguity function]]", "[[Analog signal processing]]", "[[Analytic signal]]", "[[Angle of arrival]]", "[[Apodization]]", "[[Argument (complex analysis)]]"]
---

# Rasta filtering

RASTA filtering and mean subtraction was introduced to support perceptual linear prediction
(PLP) preprocessing. It uses bandpass filtering in the log spectral domain. Rasta filtering then removes slow channel variations. It has also been applied to cepstrum feature-based preprocessing with both log spectral and cepstral domain filtering. 
In general a RASTA filter is defined by

  
    
      
        T
        z
        =
        k
        ∑
        n
        (
        N
        1
        
          /
        
        2
        ∗
        
          z
          
            n
          
        
        
          /
        
        1
        ρ
        
          /
        
        x
        
        
      
    
    
  

The numerator is a regression filter with N being the order (must be odd) and the denominator is an integrator with time decay. The pole controls the lower limit of frequency and is normally around 0.9. RASTA-filtering can be changed to use mean subtraction, implementing a moving average filter. Filtering is normally performed in the cepstral domain. The mean becomes the long term cepstrum and is typically computed on the speech part for each separate utterance. A silence is necessary to detect each utterance.

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

- Wikipedia: https://en.wikipedia.org/wiki/Rasta_filtering