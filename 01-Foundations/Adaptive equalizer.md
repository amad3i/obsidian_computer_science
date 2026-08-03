---
title: "Adaptive equalizer"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Adaptive_equalizer"
wikipedia_categories: ["Data transmission", "Digital signal processing"]
related: ["[[XPIC]]", "[[2D adaptive filters]]", "[[2D Z-transform]]", "[[Acknowledgement (data networks)]]", "[[Adaptive filter]]", "[[Adaptive predictive coding]]", "[[Adaptive-additive algorithm]]", "[[Adjoint filter]]", "[[Advanced process control]]", "[[Aliasing]]"]
---

# Adaptive equalizer

An adaptive equalizer is an equalizer that automatically adapts to time-varying properties of the communication channel. It is frequently used with coherent modulations such as phase-shift keying, mitigating the effects of multipath propagation and Doppler spreading. 
Adaptive equalizers are a subclass of adaptive filters. The central idea is altering the filter's coefficients to optimize a filter characteristic. For example, in case of linear discrete-time filters, the following equation can be used:

  
    
      
        
          
            w
          
          
            o
            p
            t
          
        
        
          
            R
          
          
            1
          
        
        
          p
        
      
    
    
  

where 
  
    
      
        
          
            w
          
          
            o
            p
            t
          
        
      
    
    
  
 is the vector of the filter's coefficients, 
  
    
      
        
          R
        
      
    
    
  
 is the received signal covariance matrix and 
  
    
      
        
          p
        
      
    
    
  
 is the cross-correlation vector between the tap-input vector and the desired response. In practice, the last quantities are not known and, if necessary, must be estimated during the equalization procedure either explicitly or implicitly.
Many adaptation strategies exist. They include, e.g.:

Least mean squares filter (LMS) Note that the receiver does not have access to the transmitted signal 
  
    
      
        x
      
    
    
  
 when it is not in training mode. If the probability that the equalizer makes a mistake is sufficiently small, the symbol decisions 
  
    
      
        d
        n
      
    
    
  
 made by the equalizer may be substituted for 
  
    
      
        x
      
    
    
  
.
Stochastic gradient descent (SG)
Recursive least squares filter (RLS)

A well-known example is the decision feedback equalizer, a filter that uses feedback of detected symbols in addition to conventional equalization of future symbols. Some systems use predefined training sequences to provide reference points for the adaptation process.

## Related

- [[XPIC]]
- [[2D adaptive filters]]
- [[2D Z-transform]]
- [[Acknowledgement (data networks)]]
- [[Adaptive filter]]
- [[Adaptive predictive coding]]
- [[Adaptive-additive algorithm]]
- [[Adjoint filter]]
- [[Advanced process control]]
- [[Aliasing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Adaptive_equalizer