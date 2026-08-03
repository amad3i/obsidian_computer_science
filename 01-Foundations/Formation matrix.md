---
title: "Formation matrix"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Formation_matrix"
wikipedia_categories: ["Estimation theory", "Information theory", "Statistical inference", "Statistics stubs"]
related: ["[[Constraint (information theory)]]", "[[Fisher information]]", "[[Gambling and information theory]]", "[[Information source (mathematics)]]", "[[Kullback's inequality]]", "[[Observed information]]", "[[3G MIMO]]", "[[A Mathematical Theory of Communication]]", "[[A Symbolic Analysis of Relay and Switching Circuits]]", "[[Accuracy paradox]]"]
---

# Formation matrix

In statistics and information theory, the expected formation matrix and the observed formation matrix are concepts used to quantify the uncertainty associated with parameter estimates derived from a likelihood function 
  
    
      
        L
        θ
      
    
    
  
. They are the matrix inverses of the Fisher information matrix and the observed information matrix, respectively.
Because Fisher information measures the amount of information that an observable random variable carries about an unknown parameter 
  
    
      
        θ
      
    
    
  
, its inverse represents a measure of the dispersion or variance for an estimator of 
  
    
      
        θ
      
    
    
  
. The formation matrix is therefore related to the covariance matrix of an estimator and is central to the Cramér–Rao bound, which establishes a lower bound on the variance of unbiased estimators. These matrices appear naturally in the asymptotic expansion of the distribution of many statistics related to the likelihood ratio.
Currently, no single notation for formation matrices is universally used. In works by Ole E. Barndorff-Nielsen and Peter McCullagh, the symbol 
  
    
      
        
          j
          
            i
            j
          
        
      
    
    
  
 denotes the element in the i-th row and j-th column of the observed formation matrix. An alternative notation, 
  
    
      
        
          g
          
            i
            j
          
        
      
    
    
  
, arises from the geometric interpretation of the Fisher information matrix as a metric tensor, denoted 
  
    
      
        
          g
          
            i
            j
          
        
      
    
    
  
. Following Einstein notation, these are related by 
  
    
      
        
          g
          
            i
            k
          
        
        
          g
          
            k
            j
          
        
        
          δ
          
            i
          
          
            j
          
        
      
    
    
  
.

## Related

- [[Constraint (information theory)]]
- [[Fisher information]]
- [[Gambling and information theory]]
- [[Information source (mathematics)]]
- [[Kullback's inequality]]
- [[Observed information]]
- [[3G MIMO]]
- [[A Mathematical Theory of Communication]]
- [[A Symbolic Analysis of Relay and Switching Circuits]]
- [[Accuracy paradox]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Formation_matrix