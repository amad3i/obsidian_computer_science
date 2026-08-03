---
title: "Expectation propagation"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Expectation_propagation"
wikipedia_categories: ["Bayesian statistics", "Machine learning", "Machine learning stubs"]
related: ["[[Astrostatistics]]", "[[Base rate]]", "[[Bayesian interpretation of kernel regularization]]", "[[Bayesian learning mechanisms]]", "[[Bayesian regret]]", "[[Bayesian structural time series]]", "[[Cost-sensitive machine learning]]", "[[Decision list]]", "[[Eager learning]]", "[[Equalized odds]]"]
---

# Expectation propagation

Expectation propagation (EP) is a technique in Bayesian machine learning.
EP finds approximations to a probability distribution. It uses an iterative approach that uses the factorization structure of the target distribution.  It differs from other Bayesian approximation approaches such as variational Bayesian methods.
More specifically, suppose we wish to approximate an intractable probability distribution 
  
    
      
        p
        
          x
        
      
    
    
  
 with a tractable distribution 
  
    
      
        q
        
          x
        
      
    
    
  
. Expectation propagation achieves this approximation by minimizing the Kullback–Leibler divergence 
  
    
      
        
          K
          L
        
        p
        
          |
        
        
          |
        
        q
      
    
    
  
. Variational Bayesian methods minimize 
  
    
      
        
          K
          L
        
        q
        
          |
        
        
          |
        
        p
      
    
    
  
 instead.
If 
  
    
      
        q
        
          x
        
      
    
    
  
 is a Gaussian 
  
    
      
        
          
            N
          
        
        
          x
        
        
          |
        
        μ
        ,
        Σ
      
    
    
  
, then 
  
    
      
        
          K
          L
        
        p
        
          |
        
        
          |
        
        q
      
    
    
  
 is minimized with 
  
    
      
        μ
      
    
    
  
 and 
  
    
      
        Σ
      
    
    
  
 being equal to the mean of 
  
    
      
        p
        
          x
        
      
    
    
  
 and the covariance of 
  
    
      
        p
        
          x
        
      
    
    
  
, respectively; this is called moment matching.

## Related

- [[Astrostatistics]]
- [[Base rate]]
- [[Bayesian interpretation of kernel regularization]]
- [[Bayesian learning mechanisms]]
- [[Bayesian regret]]
- [[Bayesian structural time series]]
- [[Cost-sensitive machine learning]]
- [[Decision list]]
- [[Eager learning]]
- [[Equalized odds]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Expectation_propagation