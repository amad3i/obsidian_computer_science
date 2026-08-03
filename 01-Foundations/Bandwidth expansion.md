---
title: "Bandwidth expansion"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Bandwidth_expansion"
wikipedia_categories: ["Signal processing", "Signal processing stubs"]
related: ["[[Adjacent channel power ratio]]", "[[Audio leveler]]", "[[Constant amplitude zero autocorrelation waveform]]", "[[Cross-recurrence quantification]]", "[[Decorrelation]]", "[[Delay equalization]]", "[[Direction of arrival]]", "[[Echo removal]]", "[[Fast folding algorithm]]", "[[Half time (electronics)]]"]
---

# Bandwidth expansion

Bandwidth expansion is a technique for widening the bandwidth or the resonances in an LPC filter. This is done by moving all the poles towards the origin by a constant factor 
  
    
      
        γ
      
    
    
  
. The bandwidth-expanded filter 
  
    
      
        
          A
          ′
        
        z
      
    
    
  
 can be easily derived from the original filter 
  
    
      
        A
        z
      
    
    
  
 by:

  
    
      
        
          A
          ′
        
        z
        =
        A
        z
        
          /
        
        γ
      
    
    
  

Let 
  
    
      
        A
        z
      
    
    
  
 be expressed as:

  
    
      
        A
        z
        =
        
          ∑
          
            k
            0
          
          
            N
          
        
        
          a
          
            k
          
        
        
          z
          
            k
          
        
      
    
    
  

The bandwidth-expanded filter can be expressed as:

  
    
      
        
          A
          ′
        
        z
        =
        
          ∑
          
            k
            0
          
          
            N
          
        
        
          a
          
            k
          
        
        
          γ
          
            k
          
        
        
          z
          
            k
          
        
      
    
    
  

In other words, each coefficient 
  
    
      
        
          a
          
            k
          
        
      
    
    
  
 in the original filter is simply multiplied by 
  
    
      
        
          γ
          
            k
          
        
      
    
    
  
 in the bandwidth-expanded filter. The simplicity of this transformation makes it attractive, especially in CELP coding of speech, where it is often used for the perceptual noise weighting and/or to stabilize the LPC analysis. However, when it comes to stabilizing the LPC analysis, lag windowing is often preferred to bandwidth expansion.

## Related

- [[Adjacent channel power ratio]]
- [[Audio leveler]]
- [[Constant amplitude zero autocorrelation waveform]]
- [[Cross-recurrence quantification]]
- [[Decorrelation]]
- [[Delay equalization]]
- [[Direction of arrival]]
- [[Echo removal]]
- [[Fast folding algorithm]]
- [[Half time (electronics)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Bandwidth_expansion