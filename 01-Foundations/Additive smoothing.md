---
title: "Additive smoothing"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Additive_smoothing"
wikipedia_categories: ["Categorical data", "Probability theory", "Statistical natural language processing"]
related: ["[[Additive process]]", "[[Almost surely]]", "[[Asymptotic geometry]]", "[[Big O in probability notation]]", "[[Blackwell-Girshick equation]]", "[[Blumenthal's zero–one law]]", "[[Brown clustering]]", "[[Brownian motion and Riemann zeta function]]", "[[Carleman's condition]]", "[[Carré du champ operator]]"]
---

# Additive smoothing

In statistics, additive smoothing, also called Laplace smoothing or Lidstone smoothing, is a technique used to smooth count data, eliminating issues caused by certain values having 0 occurrences. Given a set of observation counts 
  
    
      
        
          x
        
        ⟨
        
          x
          
            1
          
        
        ,
        
          x
          
            2
          
        
        ,
        …
        ,
        
          x
          
            d
          
        
        ⟩
      
    
    
  
 from a 
  
    
      
        d
      
    
    
  
-dimensional multinomial distribution with 
  
    
      
        N
      
    
    
  
 trials, a "smoothed" version of the counts gives the estimator

  
    
      
        
          
            
              
                θ
                ^
              
            
          
          
            i
          
        
        
          
            
              
                x
                
                  i
                
              
              α
            
            
              N
              α
              d
            
          
        
        
        i
        1
        ,
        …
        ,
        d
        ,
      
    
    
  

where the smoothed count 
  
    
      
        
          
            
              
                x
                ^
              
            
          
          
            i
          
        
        N
        
          
            
              
                θ
                ^
              
            
          
          
            i
          
        
      
    
    
  
, and the "pseudocount" α > 0 is a smoothing parameter, with α = 0 corresponding to no smoothing (this parameter is explained in § Pseudocount below). Additive smoothing is a type of shrinkage estimator, as the resulting estimate will be between the empirical probability (relative frequency) 
  
    
      
        
          x
          
            i
          
        
        
          /
        
        N
      
    
    
  
 and the uniform probability 
  
    
      
        1
        
          /
        
        d
        .
      
    
    
  
 Common choices for α are 0 (no smoothing), +1⁄2 (the Jeffreys prior), or 1 (Laplace's rule of succession), but the parameter may also be set empirically based on the observed data.
From a Bayesian point of view, this corresponds to the expected value of the posterior distribution, using a symmetric Dirichlet distribution with parameter α as a prior distribution. In the special case where the number of categories is 2, this is equivalent to using a beta distribution as the conjugate prior for the parameters of the binomial distribution.

## Related

- [[Additive process]]
- [[Almost surely]]
- [[Asymptotic geometry]]
- [[Big O in probability notation]]
- [[Blackwell-Girshick equation]]
- [[Blumenthal's zero–one law]]
- [[Brown clustering]]
- [[Brownian motion and Riemann zeta function]]
- [[Carleman's condition]]
- [[Carré du champ operator]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Additive_smoothing