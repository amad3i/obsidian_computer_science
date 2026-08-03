---
title: "Relevance vector machine"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Relevance_vector_machine"
wikipedia_categories: ["Classification algorithms", "Kernel methods for machine learning", "Nonparametric Bayesian statistics"]
related: ["[[Gaussian process]]", "[[Support vector machine]]", "[[(1+ε)-approximate nearest neighbor search]]", "[[AdaBoost]]", "[[ALOPEX]]", "[[Alternating decision tree]]", "[[Analogical modeling]]", "[[Boosting (machine learning)]]", "[[BrownBoost]]", "[[Calibration (statistics)]]"]
---

# Relevance vector machine

In mathematics, a Relevance Vector Machine (RVM) is a machine learning technique that uses Bayesian inference to obtain parsimonious solutions for regression and probabilistic classification. A greedy optimisation procedure and thus fast version were subsequently developed.
The RVM has an identical functional form to the support vector machine, but provides probabilistic classification.
It is actually equivalent to a Gaussian process model with covariance function:

  
    
      
        k
        
          x
        
        ,
        
          
            x
            ′
          
        
        =
        
          ∑
          
            j
            1
          
          
            N
          
        
        
          
            1
            
              α
              
                j
              
            
          
        
        φ
        
          x
        
        ,
        
          
            x
          
          
            j
          
        
        φ
        
          
            x
          
          ′
        
        ,
        
          
            x
          
          
            j
          
        
      
    
    
  

where 
  
    
      
        φ
      
    
    
  
 is the kernel function (usually Gaussian), 
  
    
      
        
          α
          
            j
          
        
      
    
    
  
 are the variances of the prior on the weight vector

  
    
      
        w
        ∼
        N
        0
        ,
        
          α
          
            1
          
        
        I
      
    
    
  
, and 
  
    
      
        
          
            x
          
          
            1
          
        
        ,
        …
        ,
        
          
            x
          
          
            N
          
        
      
    
    
  
 are the input vectors of the training set.
Compared to that of support vector machines (SVM), the Bayesian formulation of the RVM avoids the set of free parameters of the SVM (that usually require cross-validation-based post-optimizations). However RVMs use an expectation maximization (EM)-like learning method and are therefore at risk of local minima. This is unlike the standard sequential minimal optimization (SMO)-based algorithms employed by SVMs, which are guaranteed to find a global optimum (of the convex problem).
The relevance vector machine was patented in the United States by Microsoft (patent expired September 4, 2019).

## Related

- [[Gaussian process]]
- [[Support vector machine]]
- [[(1+ε)-approximate nearest neighbor search]]
- [[AdaBoost]]
- [[ALOPEX]]
- [[Alternating decision tree]]
- [[Analogical modeling]]
- [[Boosting (machine learning)]]
- [[BrownBoost]]
- [[Calibration (statistics)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Relevance_vector_machine