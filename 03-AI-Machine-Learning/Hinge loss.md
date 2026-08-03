---
title: "Hinge loss"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Hinge_loss"
wikipedia_categories: ["Loss functions", "Support vector machines"]
related: ["[[Huber loss]]", "[[Loss function]]", "[[Margin (machine learning)]]", "[[Mean squared error]]", "[[Mean squared prediction error]]", "[[Radial basis function kernel]]", "[[Ranking SVM]]", "[[Regularization perspectives on support vector machines]]", "[[Sequential minimal optimization]]", "[[Structured support vector machine]]"]
---

# Hinge loss

In machine learning, hinge loss is a loss function used for training classifiers. Hinge loss is used for "maximum-margin" classification, most notably for support vector machines (SVMs).
For an intended output t = ±1 and a classifier score y, the hinge loss of the prediction y is defined as:

  
    
      
        ℓ
        y
        =
        max
        0
        ,
        1
        t
        ⋅
        y
      
    
    
  

Note that 
  
    
      
        y
      
    
    
  
 should be the "raw" output of the classifier's decision function, not the predicted class label. For instance, in linear SVMs, 
  
    
      
        y
        
          w
        
        ⋅
        
          x
        
        b
      
    
    
  
, where 
  
    
      
        
          w
        
        ,
        b
      
    
    
  
 are the parameters of the hyperplane and 
  
    
      
        
          x
        
      
    
    
  
 is the input variable(s).
When t and y have the same sign (meaning y predicts the correct class) and 
  
    
      
        
          |
        
        y
        
          |
        
        ≥
        1
      
    
    
  
, the hinge loss 
  
    
      
        ℓ
        y
        =
        0
      
    
    
  
. When they have opposite signs, 
  
    
      
        ℓ
        y
      
    
    
  
 increases linearly with y, and similarly if 
  
    
      
        
          |
        
        y
        
          |
        
        1
      
    
    
  
, even if it has the same sign (correct prediction, but not by enough margin).
Hinge loss is not a proper scoring rule.

## Related

- [[Huber loss]]
- [[Loss function]]
- [[Margin (machine learning)]]
- [[Mean squared error]]
- [[Mean squared prediction error]]
- [[Radial basis function kernel]]
- [[Ranking SVM]]
- [[Regularization perspectives on support vector machines]]
- [[Sequential minimal optimization]]
- [[Structured support vector machine]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Hinge_loss