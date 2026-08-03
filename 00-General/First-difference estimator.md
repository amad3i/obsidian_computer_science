---
title: "First-difference estimator"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/First-difference_estimator"
wikipedia_categories: ["Estimator", "Latent variable models"]
related: ["[[Common-method variance]]", "[[Doubly stochastic model]]", "[[Dynamic topic model]]", "[[Dynamic unobserved effects model]]", "[[Factor analysis]]", "[[Factor regression model]]", "[[Item response theory]]", "[[Latent class model]]", "[[Latent Dirichlet allocation]]", "[[Latent semantic analysis]]"]
---

# First-difference estimator

In statistics and econometrics, the first-difference (FD) estimator is an estimator used to address the problem of omitted variables with panel data. It is consistent under the assumptions of the fixed effects model. In certain situations it can be more efficient than the standard fixed effects (or "within") estimator, for example when the error terms follows a random walk.
The estimator requires data on a dependent variable, 
  
    
      
        
          y
          
            i
            t
          
        
      
    
    
  
, and independent variables, 
  
    
      
        
          x
          
            i
            t
          
        
      
    
    
  
, for a set of individual units 
  
    
      
        i
        1
        ,
        …
        ,
        N
      
    
    
  
 and time periods 
  
    
      
        t
        1
        ,
        …
        ,
        T
      
    
    
  
. The estimator is obtained by running a pooled ordinary least squares (OLS) estimation for a regression of 
  
    
      
        Δ
        
          y
          
            i
            t
          
        
      
    
    
  
 on 
  
    
      
        Δ
        
          x
          
            i
            t
          
        
      
    
    
  
.

## Related

- [[Common-method variance]]
- [[Doubly stochastic model]]
- [[Dynamic topic model]]
- [[Dynamic unobserved effects model]]
- [[Factor analysis]]
- [[Factor regression model]]
- [[Item response theory]]
- [[Latent class model]]
- [[Latent Dirichlet allocation]]
- [[Latent semantic analysis]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/First-difference_estimator