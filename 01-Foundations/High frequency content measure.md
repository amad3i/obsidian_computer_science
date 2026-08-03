---
title: "High frequency content measure"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/High_frequency_content_measure"
wikipedia_categories: ["Digital signal processing", "Signal processing stubs"]
related: ["[[Adjoint filter]]", "[[Delay equalization]]", "[[Encoding law]]", "[[Fast Walsh–Hadamard transform]]", "[[Polyphase quadrature filter]]", "[[Spectral flux]]", "[[Time-domain harmonic scaling]]", "[[Unity amplitude]]", "[[V-by-One US]]", "[[Warped linear predictive coding]]"]
---

# High frequency content measure

In signal processing, the high frequency content measure is a simple measure, taken across a signal spectrum (usually a STFT spectrum), that can be used to characterize the amount of high-frequency content in the signal. The magnitudes of the spectral bins are added together, but multiplying each magnitude by the bin "position" (proportional to the frequency).  Thus if X(k) is a discrete spectrum with N unique points, its high frequency content measure is:

  
    
      
        
          H
          F
          C
        
        
          ∑
          
            i
            0
          
          
            N
            1
          
        
        i
        
          |
        
        X
        i
        
          |
        
      
    
    
  

In contrast to perceptual measures, this is not based on any evidence about its relevance to human hearing. Despite that, it can be useful for some applications, such as onset detection.
The measure has close similarities to the spectral centroid measure, being essentially the same calculation but without normalization according to overall magnitude.

## Related

- [[Adjoint filter]]
- [[Delay equalization]]
- [[Encoding law]]
- [[Fast Walsh–Hadamard transform]]
- [[Polyphase quadrature filter]]
- [[Spectral flux]]
- [[Time-domain harmonic scaling]]
- [[Unity amplitude]]
- [[V-by-One US]]
- [[Warped linear predictive coding]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/High_frequency_content_measure