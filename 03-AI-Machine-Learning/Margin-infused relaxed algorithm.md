---
title: "Margin-infused relaxed algorithm"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Margin-infused_relaxed_algorithm"
wikipedia_categories: ["Classification algorithms"]
related: ["[[(1+ε)-approximate nearest neighbor search]]", "[[AdaBoost]]", "[[ALOPEX]]", "[[Alternating decision tree]]", "[[Analogical modeling]]", "[[Boosting (machine learning)]]", "[[BrownBoost]]", "[[Calibration (statistics)]]", "[[Cascading classifiers]]", "[[Case-based reasoning]]"]
---

# Margin-infused relaxed algorithm

Margin-infused relaxed algorithm (MIRA) is a machine learning and online algorithm for multiclass classification problems. It is designed to learn a set of parameters (vector or matrix) by processing all the given training examples one-by-one and updating the parameters according to each training example, so that the current training example is classified correctly with a margin against incorrect classifications at least as large as their loss. The change of the parameters is kept as small as possible.
A two-class version called binary MIRA simplifies the algorithm by not requiring the solution of a quadratic programming problem (see below). When used in a one-vs-all configuration, binary MIRA can be extended to a multiclass learner that approximates full MIRA, but may be faster to train.
The flow of the algorithm looks as follows:

The update step is then formalized as a quadratic programming problem: Find 
  
    
      
        m
        i
        n
        ‖
        
          w
          
            i
            1
          
        
        
          w
          
            i
          
        
        ‖
      
    
    
  
, so that 
  
    
      
        s
        c
        o
        r
        e
        
          x
          
            t
          
        
        ,
        
          y
          
            t
          
        
        −
        s
        c
        o
        r
        e
        
          x
          
            t
          
        
        ,
        
          y
          ′
        
        ≥
        L
        
          y
          
            t
          
        
        ,
        
          y
          ′
        
         
        ∀
        
          y
          ′
        
      
    
    
  
, i.e. the score of the current correct training 
  
    
      
        y
      
    
    
  
 must be greater than the score of any other possible 
  
    
      
        
          y
          ′
        
      
    
    
  
 by at least the loss (number of errors) of that 
  
    
      
        
          y
          ′
        
      
    
    
  
 in comparison to 
  
    
      
        y
      
    
    
  
.

## Related

- [[(1+ε)-approximate nearest neighbor search]]
- [[AdaBoost]]
- [[ALOPEX]]
- [[Alternating decision tree]]
- [[Analogical modeling]]
- [[Boosting (machine learning)]]
- [[BrownBoost]]
- [[Calibration (statistics)]]
- [[Cascading classifiers]]
- [[Case-based reasoning]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Margin-infused_relaxed_algorithm