---
title: "Modified Wigner distribution function"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Modified_Wigner_distribution_function"
wikipedia_categories: ["Signal processing", "Transforms"]
related: ["[[Overlap–add method]]", "[[Overlap–save method]]", "[[Short-time Fourier transform]]", "[[Wigner distribution function]]", "[[Adaptive beamformer]]", "[[Adjacent channel power ratio]]", "[[Algebraic signal processing]]", "[[Aliasing]]", "[[Ambiguity function]]", "[[Analog signal processing]]"]
---

# Modified Wigner distribution function

Note: the Wigner distribution function is abbreviated here as WD rather than WDF as used at Wigner distribution function
A Modified Wigner distribution function is a variation of the Wigner distribution function (WD) with reduced or removed cross-terms.
The Wigner distribution (WD) was first proposed for corrections to classical statistical mechanics in 1932 by Eugene Wigner. The Wigner distribution function, or Wigner–Ville distribution (WVD) for analytic signals, also has applications in time frequency analysis. The Wigner distribution gives better auto term localisation compared to the smeared out spectrogram (SP). However, when applied to a signal with multi frequency components, cross terms appear due to its quadratic nature. Several methods have been proposed to reduce the cross terms. For example, in 1994 Ljubiša Stanković proposed a novel technique, now mostly referred to as S-method, resulting in the reduction or removal of cross terms. The concept of the S-method is a combination between the spectrogram and the Pseudo Wigner Distribution (PWD), the windowed version of the WD.
The original WD, the spectrogram, and the modified WDs all belong to the Cohen's class of bilinear time-frequency representations :

  
    
      
        
          C
          
            x
          
        
        t
        ,
        f
        =
        
          ∫
          
            ∞
          
          
            ∞
          
        
        
          ∫
          
            ∞
          
          
            ∞
          
        
        
          W
          
            x
          
        
        θ
        ,
        ν
        Π
        t
        θ
        ,
        f
        ν
        
        d
        θ
        
        d
        ν
        
        [
        
          W
          
            x
          
        
        
        
        Π
        (
        t
        ,
        f
      
    
    
  

where 
  
    
      
        Π
        
          
            t
            ,
            f
          
        
      
    
    
  
 is Cohen's  kernel function, which is often a low-pass function, and normally serves to mask out the interference in the original Wigner representation.

## Related

- [[Overlap–add method]]
- [[Overlap–save method]]
- [[Short-time Fourier transform]]
- [[Wigner distribution function]]
- [[Adaptive beamformer]]
- [[Adjacent channel power ratio]]
- [[Algebraic signal processing]]
- [[Aliasing]]
- [[Ambiguity function]]
- [[Analog signal processing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Modified_Wigner_distribution_function