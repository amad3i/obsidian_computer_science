---
title: "Fourier analysis"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Fourier_analysis"
wikipedia_categories: ["Acoustics", "Digital signal processing", "Fourier analysis", "Integral transforms", "Joseph Fourier", "Mathematical physics", "Mathematics of computing", "Time series"]
related: ["[[Fourier transform]]", "[[Least-squares spectral analysis]]", "[[Almost periodic function]]", "[[Dereverberation]]", "[[DFT matrix]]", "[[Dirac delta function]]", "[[Discrete cosine transform]]", "[[Discrete Fourier transform]]", "[[Discrete-time Fourier transform]]", "[[Instantaneous phase and frequency]]"]
---

# Fourier analysis

In mathematics, the sciences, and engineering, Fourier analysis () is the study of the way general functions on the real line, circle, integers, finite cyclic group or general locally compact Abelian group may be represented or approximated by sums of  trigonometric functions or more conveniently, complex exponentials. Fourier analysis grew from the study of Fourier series, and is named after Joseph Fourier, who showed that representing a function as a sum of trigonometric functions greatly simplifies the study of heat transfer.
Fourier analysis has applications in many areas of  pure and applied mathematics, in the sciences and in engineering.  The process of decomposing a function into oscillatory components is often called Fourier analysis, while the operation of rebuilding the function from these pieces is known as Fourier synthesis. For example, determining what component frequencies are present in a musical note would involve computing the Fourier transform of a sampled musical note. One can then re-synthesize the same sound by mixing purely harmonic sounds with frequency components as revealed in the Fourier analysis. In mathematics, the term Fourier analysis often refers to the study of both operations.
The decomposition process itself is called a Fourier transformation. Its output, the Fourier transform, is often given a more specific name, which depends on the domain and other properties of the function being transformed. Moreover, the original concept of Fourier analysis has been extended over time to apply to more and more abstract and general situations as group representation theory,  and the general field is often known as harmonic analysis. Each transform used for analysis (see list of Fourier-related transforms) has a corresponding inverse transform that can be used for synthesis.
In applications, Fourier analysis is usually applied to a "signal" depending on "time" sampled at equal time intervals of length 
  
    
      
        T
      
    
    
  
. The Fourier transform converts this sequence in an equally long sequence of amplitudes for sines and cosines (or more conveniently, complex exponentials) with frequency multiples of 
  
    
      
        1
        
          /
        
        T
      
    
    
  
. This is particularly useful to detect strong periodic components in the signal. The fast Fourier transform is an efficient algorithm to compute these amplitudes. Different approaches have been developed for analyzing unequally spaced data, notably the least-squares spectral analysis (LSSA) methods that use a least squares fit of sinusoids to data samples, similar to Fourier analysis. Fourier analysis, the most used spectral method in science, generally boosts long-periodic noise in long gapped records; LSSA mitigates such problems.

## Related

- [[Fourier transform]]
- [[Least-squares spectral analysis]]
- [[Almost periodic function]]
- [[Dereverberation]]
- [[DFT matrix]]
- [[Dirac delta function]]
- [[Discrete cosine transform]]
- [[Discrete Fourier transform]]
- [[Discrete-time Fourier transform]]
- [[Instantaneous phase and frequency]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Fourier_analysis