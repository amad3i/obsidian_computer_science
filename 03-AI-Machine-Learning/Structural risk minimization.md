---
title: "Structural risk minimization"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Structural_risk_minimization"
wikipedia_categories: ["Machine learning", "Machine learning stubs"]
related: ["[[Astrostatistics]]", "[[Bayesian learning mechanisms]]", "[[Cost-sensitive machine learning]]", "[[Decision list]]", "[[Eager learning]]", "[[Equalized odds]]", "[[Expectation propagation]]", "[[Few-shot learning]]", "[[Hidden layer]]", "[[Inauthentic text]]"]
---

# Structural risk minimization

Structural risk minimization (SRM) is an inductive principle of use in machine learning. Commonly in machine learning, a generalized model must be selected from a finite data set, with the consequent problem of overfitting – the model becoming too strongly tailored to the particularities of the training set and generalizing poorly to new data. The SRM principle addresses this problem by balancing the model's complexity against its success at fitting the training data. This principle was first set out in a 1974 book by Vladimir Vapnik and Alexey Chervonenkis and uses the VC dimension.
In practical terms, Structural Risk Minimization is implemented by minimizing 
  
    
      
        
          E
          
            t
            r
            a
            i
            n
          
        
        β
        H
        W
      
    
    
  
, where 
  
    
      
        
          E
          
            t
            r
            a
            i
            n
          
        
      
    
    
  
 is the train error, the function 
  
    
      
        H
        W
      
    
    
  
 is called a regularization function, and 
  
    
      
        β
      
    
    
  
 is a constant.  
  
    
      
        H
        W
      
    
    
  
 is chosen such that it takes large values on parameters 
  
    
      
        W
      
    
    
  
 that belong to high-capacity subsets of the parameter space. Minimizing 
  
    
      
        H
        W
      
    
    
  
 in effect limits the capacity of the accessible subsets of the parameter space, thereby controlling the trade-off between minimizing the training error and minimizing the expected gap between the training error and test error.
The SRM problem can be formulated in terms of data. Given n data points consisting of data x and labels y, the objective 
  
    
      
        J
        θ
      
    
    
  
 is often expressed in the following manner:

  
    
      
        J
        θ
        =
        
          
            1
            
              2
              n
            
          
        
        
          ∑
          
            i
            1
          
          
            n
          
        
        
          h
          
            θ
          
        
        
          x
          
            i
          
        
        −
        
          y
          
            i
          
        
        
          
            2
          
        
        
          
            λ
            2
          
        
        
          ∑
          
            j
            1
          
          
            d
          
        
        
          θ
          
            j
          
          
            2
          
        
      
    
    
  

The first term is the mean squared error (MSE) term between the value of the learned model, 
  
    
      
        
          h
          
            θ
          
        
      
    
    
  
, and the given labels 
  
    
      
        y
      
    
    
  
. This term is the training error, 
  
    
      
        
          E
          
            t
            r
            a
            i
            n
          
        
      
    
    
  
, that was discussed earlier. The second term, places a prior over the weights, to favor sparsity and penalize larger weights. The trade-off coefficient, 
  
    
      
        λ
      
    
    
  
, is a hyperparameter that places more or less importance on the regularization term. Larger 
  
    
      
        λ
      
    
    
  
 encourages sparser weights at the expense of a more optimal MSE, and smaller 
  
    
      
        λ
      
    
    
  
 relaxes regularization allowing the model to fit to data. Note that as 
  
    
      
        λ
        →
        ∞
      
    
    
  
 the weights become zero, and as 
  
    
      
        λ
        →
        0
      
    
    
  
, the model typically suffers from overfitting.

## Related

- [[Astrostatistics]]
- [[Bayesian learning mechanisms]]
- [[Cost-sensitive machine learning]]
- [[Decision list]]
- [[Eager learning]]
- [[Equalized odds]]
- [[Expectation propagation]]
- [[Few-shot learning]]
- [[Hidden layer]]
- [[Inauthentic text]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Structural_risk_minimization