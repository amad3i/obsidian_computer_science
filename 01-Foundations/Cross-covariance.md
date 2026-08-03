---
title: "Cross-covariance"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Cross-covariance"
wikipedia_categories: ["Covariance and correlation", "Signal processing", "Time domain analysis"]
related: ["[[Cross-correlation]]", "[[Autocorrelation]]", "[[Cross-correlation matrix]]", "[[Linear time-invariant system]]", "[[Triple correlation]]", "[[Adaptive beamformer]]", "[[Adjacent channel power ratio]]", "[[Algebraic signal processing]]", "[[Aliasing]]", "[[Ambiguity function]]"]
---

# Cross-covariance

In probability and statistics, given two stochastic processes 
  
    
      
        
          
            X
            
              t
            
          
        
      
    
    
  
 and 
  
    
      
        
          
            Y
            
              t
            
          
        
      
    
    
  
, the cross-covariance is a function that gives the covariance of one process with the other at pairs of time points. With the usual notation 
  
    
      
        E
      
    
    
  
 for the expectation operator, if the processes have the mean functions 
  
    
      
        
          μ
          
            X
          
        
        t
        =
        
          E
        
         
        
          X
          
            t
          
        
      
    
    
  
 and 
  
    
      
        
          μ
          
            Y
          
        
        t
        =
        E
         
        
          Y
          
            t
          
        
      
    
    
  
, then the cross-covariance is given by

  
    
      
        
          K
          
            X
            Y
          
        
         
        
          t
          
            1
          
        
        ,
        
          t
          
            2
          
        
        =
        cov
         
        
          X
          
            
              t
              
                1
              
            
          
        
        ,
        
          Y
          
            
              t
              
                2
              
            
          
        
        =
        E
         
        (
        
          X
          
            
              t
              
                1
              
            
          
        
        
          μ
          
            X
          
        
        
          t
          
            1
          
        
        )
        
          Y
          
            
              t
              
                2
              
            
          
        
        
          μ
          
            Y
          
        
        
          t
          
            2
          
        
        )
        =
        E
         
        
          X
          
            
              t
              
                1
              
            
          
        
        
          Y
          
            
              t
              
                2
              
            
          
        
        −
        
          μ
          
            X
          
        
        
          t
          
            1
          
        
        
          μ
          
            Y
          
        
        
          t
          
            2
          
        
        .
        
      
    
    
  

Cross-covariance is related to the more commonly used cross-correlation of the processes in question.
In the case of two random vectors 
  
    
      
        
          X
        
        (
        
          X
          
            1
          
        
        ,
        
          X
          
            2
          
        
        ,
        …
        ,
        
          X
          
            p
          
        
        
          
            
              T
            
          
        
      
    
    
  
 and 
  
    
      
        
          Y
        
        (
        
          Y
          
            1
          
        
        ,
        
          Y
          
            2
          
        
        ,
        …
        ,
        
          Y
          
            q
          
        
        
          
            
              T
            
          
        
      
    
    
  
, the cross-covariance would be a 
  
    
      
        p
        q
      
    
    
  
 matrix 
  
    
      
        
          K
          
            X
            Y
          
        
      
    
    
  
 (often denoted 
  
    
      
        cov
         
        X
        ,
        Y
      
    
    
  
) with entries 
  
    
      
        
          K
          
            X
            Y
          
        
         
        j
        ,
        k
        =
        cov
         
        
          X
          
            j
          
        
        ,
        
          Y
          
            k
          
        
        .
        
      
    
    
  
 Thus the term cross-covariance is used in order to distinguish this concept from the covariance of a random vector 
  
    
      
        
          X
        
      
    
    
  
, which is understood to be the matrix of covariances between the scalar components of 
  
    
      
        
          X
        
      
    
    
  
 itself.
In signal processing, the cross-covariance is often called cross-correlation and is a measure of similarity of two signals, commonly used to find features in an unknown signal by comparing it to a known one. It is a function of the relative time between the signals, is sometimes called the sliding dot product, and has applications in pattern recognition and cryptanalysis.

## Related

- [[Cross-correlation]]
- [[Autocorrelation]]
- [[Cross-correlation matrix]]
- [[Linear time-invariant system]]
- [[Triple correlation]]
- [[Adaptive beamformer]]
- [[Adjacent channel power ratio]]
- [[Algebraic signal processing]]
- [[Aliasing]]
- [[Ambiguity function]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Cross-covariance