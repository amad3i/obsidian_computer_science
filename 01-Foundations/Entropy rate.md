---
title: "Entropy rate"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Entropy_rate"
wikipedia_categories: ["Entropy", "Information theory", "Markov models", "Temporal rates"]
related: ["[[Maximum entropy spectral estimation]]", "[[Measure-preserving dynamical system]]", "[[Network throughput]]", "[[3G MIMO]]", "[[A Mathematical Theory of Communication]]", "[[A Symbolic Analysis of Relay and Switching Circuits]]", "[[Adjusted mutual information]]", "[[Algorithmic information theory]]", "[[Ascendency]]", "[[Asymptotic equipartition property]]"]
---

# Entropy rate

In the mathematical theory of probability, the entropy rate or source information rate of a stochastic process is, informally, the time density of the average information in a stochastic process. For stochastic processes with a countable index, the entropy rate 
  
    
      
        H
        X
      
    
    
  
 is the limit of the joint entropy of 
  
    
      
        n
      
    
    
  
 members of the process 
  
    
      
        
          X
          
            k
          
        
      
    
    
  
 divided by 
  
    
      
        n
      
    
    
  
, as 
  
    
      
        n
      
    
    
  
 tends to infinity:

  
    
      
        H
        X
        =
        
          
            n
            →
            ∞
          
        
        
          
            1
            n
          
        
        H
        
          X
          
            1
          
        
        ,
        
          X
          
            2
          
        
        ,
        …
        
          X
          
            n
          
        
      
    
    
  

when the limit exists. An alternative, related quantity is:

  
    
      
        
          H
          ′
        
        X
        =
        
          
            n
            →
            ∞
          
        
        H
        
          X
          
            n
          
        
        
          |
        
        
          X
          
            n
            1
          
        
        ,
        
          X
          
            n
            2
          
        
        ,
        …
        
          X
          
            1
          
        
      
    
    
  

For strongly stationary stochastic processes, 
  
    
      
        H
        X
        =
        
          H
          ′
        
        X
      
    
    
  
.  The entropy rate can be thought of as a general property of stochastic sources; this is the asymptotic equipartition property.
The entropy rate may be used to estimate the complexity of stochastic processes. It is used in diverse applications ranging from characterizing the complexity of languages, blind source separation, through to optimizing quantizers and data compression algorithms. For example, a maximum entropy rate criterion may be used for feature selection in machine learning.

## Related

- [[Maximum entropy spectral estimation]]
- [[Measure-preserving dynamical system]]
- [[Network throughput]]
- [[3G MIMO]]
- [[A Mathematical Theory of Communication]]
- [[A Symbolic Analysis of Relay and Switching Circuits]]
- [[Adjusted mutual information]]
- [[Algorithmic information theory]]
- [[Ascendency]]
- [[Asymptotic equipartition property]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Entropy_rate