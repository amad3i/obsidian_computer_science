---
title: "Martingale difference sequence"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Martingale_difference_sequence"
wikipedia_categories: ["Martingale theory", "Probability stubs", "Signal processing"]
related: ["[[Adaptive beamformer]]", "[[Adjacent channel power ratio]]", "[[Adversarial queueing network]]", "[[Algebraic signal processing]]", "[[Aliasing]]", "[[Ambiguity function]]", "[[Analog signal processing]]", "[[Analytic signal]]", "[[Angle of arrival]]", "[[Apodization]]"]
---

# Martingale difference sequence

In probability theory, a martingale difference sequence (MDS) is related to the concept of the martingale.  A stochastic series X is an MDS if its expectation with respect to the past is zero. Formally, consider an adapted sequence 
  
    
      
        
          X
          
            t
          
        
        ,
        
          
            
              F
            
          
          
            t
          
        
        
          
            ∞
          
          
            ∞
          
        
      
    
    
  
 on a probability space 
  
    
      
        Ω
        ,
        
          
            F
          
        
        ,
        
          P
        
      
    
    
  
. 
  
    
      
        
          X
          
            t
          
        
      
    
    
  
 is an MDS if it satisfies the following two conditions:

  
    
      
        
          E
        
        
          |
          
            X
            
              t
            
          
          |
        
        ∞
      
    
    
  
, and

  
    
      
        
          E
        
        
          
            
              X
              
                t
              
            
            
              |
            
            
              
                
                  F
                
              
              
                t
                1
              
            
          
        
        0
        ,
        a
        .
        s
        .
      
    
    
  
,
for all 
  
    
      
        t
      
    
    
  
. By construction, this implies that if 
  
    
      
        
          Y
          
            t
          
        
      
    
    
  
 is a martingale, then 
  
    
      
        
          X
          
            t
          
        
        
          Y
          
            t
          
        
        
          Y
          
            t
            1
          
        
      
    
    
  
 will be an MDS—hence the name.
The MDS is an extremely useful construct in modern probability theory because it implies much milder restrictions on the memory of the sequence than independence, yet most limit theorems that hold for an independent sequence will also hold for an MDS.

A special case of MDS, denoted as {Xt,
  
    
      
        
          
            F
          
        
      
    
    
  
t}0
  
    
      
        
          ∞
        
      
    
    
  
 is known as innovative sequence of Sn; where Sn and 
  
    
      
        
          
            
              F
            
          
          
            t
          
        
      
    
    
  
 are corresponding to random walk and filtration of the random processes 
  
    
      
        
          X
          
            t
          
        
        
          
            0
          
          
            ∞
          
        
      
    
    
  
. 
In probability theory innovation series is used to emphasize the generality of Doob representation. In signal processing the innovation series is used to introduce Kalman filter. The main differences of innovation
terminologies are in the applications. The later application aims to introduce the nuance of samples to the model by random sampling.

## Related

- [[Adaptive beamformer]]
- [[Adjacent channel power ratio]]
- [[Adversarial queueing network]]
- [[Algebraic signal processing]]
- [[Aliasing]]
- [[Ambiguity function]]
- [[Analog signal processing]]
- [[Analytic signal]]
- [[Angle of arrival]]
- [[Apodization]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Martingale_difference_sequence