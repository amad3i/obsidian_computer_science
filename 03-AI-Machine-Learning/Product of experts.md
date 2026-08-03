---
title: "Product of experts"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Product_of_experts"
wikipedia_categories: ["Machine learning", "Machine learning stubs"]
related: ["[[Astrostatistics]]", "[[Bayesian learning mechanisms]]", "[[Cost-sensitive machine learning]]", "[[Decision list]]", "[[Eager learning]]", "[[Equalized odds]]", "[[Expectation propagation]]", "[[Few-shot learning]]", "[[Hidden layer]]", "[[Inauthentic text]]"]
---

# Product of experts

Product of experts (PoE) is a machine learning technique. It models a probability distribution by combining the output from several simpler distributions.
It was proposed by Geoffrey Hinton in 1999, along with an algorithm for training the parameters of such a system.
The core idea is to combine several probability distributions ("experts") by multiplying their density functions—making the PoE classification similar to an "and" operation. This allows each expert to make decisions on the basis of a few dimensions without having to cover the full dimensionality of a problem:

  
    
      
        P
        y
        
          |
        
        
          x
          
            k
          
        
        )
        
          
            1
            Z
          
        
        
          ∏
          
            j
            1
          
          
            M
          
        
        
          f
          
            j
          
        
        y
        
          |
        
        
          x
          
            k
          
        
        )
      
    
    
  

where 
  
    
      
        
          f
          
            j
          
        
      
    
    
  
 are unnormalized expert densities and 
  
    
      
        Z
        ∫
        
          
            d
          
        
        y
        
          ∏
          
            j
            1
          
          
            M
          
        
        
          f
          
            j
          
        
        y
        
          |
        
        
          x
          
            k
          
        
        )
      
    
    
  
 is a normalization constant (see partition function (statistical mechanics)).
This is related to (but quite different from) a mixture model, where several probability distributions 
  
    
      
        
          p
          
            j
          
        
        y
        
          |
        
        
          x
          
            j
          
        
        )
      
    
    
  
 are combined via an "or" operation, which is a weighted sum of their density functions:

  
    
      
        P
        y
        
          |
        
        
          x
          
            k
          
        
        )
        
          ∑
          
            j
            1
          
          
            M
          
        
        
          α
          
            j
          
        
        
          p
          
            j
          
        
        y
        
          |
        
        
          x
          
            k
          
        
        )
        ,
      
    
    
  

with 
  
    
      
        
          ∑
          
            j
          
        
        
          α
          
            j
          
        
        1.
      
    
    
  

The experts may be understood as each being responsible for enforcing a constraint in a high-dimensional space. A data point is considered likely if and only if none of the experts say that the point violates a constraint.
To optimize it, he proposed the contrastive divergence minimization algorithm. This algorithm is most often used for learning restricted Boltzmann machines.

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

- Wikipedia: https://en.wikipedia.org/wiki/Product_of_experts