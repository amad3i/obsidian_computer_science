---
title: "Aliasing"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Aliasing"
wikipedia_categories: ["Digital signal processing", "Signal processing"]
related: ["[[Beta encoder]]", "[[BIBO stability]]", "[[Delay equalization]]", "[[Digital down converter]]", "[[Downsampling (signal processing)]]", "[[First-order hold]]", "[[Half-band filter]]", "[[Instantaneous phase and frequency]]", "[[Least-squares spectral analysis]]", "[[Linear time-invariant system]]"]
---

# Aliasing

In digital signal processing, aliasing is a phenomenon in which a reconstructed signal from samples of the original signal contains low frequency components that are not present in the original one. This is caused when, in the original signal, there are components at frequency exceeding a certain frequency called Nyquist frequency, 
  
    
      
        
          f
          
            s
          
        
        
          /
        
        2
      
    
    {\textstyle f_{s}/2}
  
, where 
  
    
      
        
          f
          
            s
          
        
      
    
    {\textstyle f_{s}}
  
 is the sampling frequency (undersampling). This is because typical reconstruction methods use low frequency components while there are a number of frequency components, called aliases, which sampling result in the identical sample. It also often refers to the distortion or artifact that results when a signal reconstructed from samples is different from the original continuous signal.
Aliasing can occur in signals sampled in time, for instance in digital audio or the stroboscopic effect, and is referred to as temporal aliasing.  Aliasing in spatially sampled signals (e.g., moiré patterns in digital images) is referred to as spatial aliasing.
Aliasing is generally avoided by applying low-pass filters or anti-aliasing filters (AAF) to the input signal before sampling and when converting a signal from a higher to a lower sampling rate. Suitable reconstruction filtering should then be used when restoring the sampled signal to the continuous domain or converting a signal from a lower to a higher sampling rate. For spatial anti-aliasing, the types of anti-aliasing include fast approximate anti-aliasing (FXAA), multisample anti-aliasing (MSAA), and supersampling. Temporal anti-aliasing is a special case of MSAA where pixel samples are collected over multiple frames.

## Related

- [[Beta encoder]]
- [[BIBO stability]]
- [[Delay equalization]]
- [[Digital down converter]]
- [[Downsampling (signal processing)]]
- [[First-order hold]]
- [[Half-band filter]]
- [[Instantaneous phase and frequency]]
- [[Least-squares spectral analysis]]
- [[Linear time-invariant system]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Aliasing