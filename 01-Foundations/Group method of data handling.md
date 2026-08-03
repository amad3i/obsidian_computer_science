---
title: "Group method of data handling"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Group_method_of_data_handling"
wikipedia_categories: ["Artificial neural networks", "Classification algorithms", "Computational statistics", "Regression variable selection", "Soviet inventions", "Ukrainian inventions"]
related: ["[[Address programming language]]", "[[ALOPEX]]", "[[Hyper basis function network]]", "[[Perceptron]]", "[[(1+ε)-approximate nearest neighbor search]]", "[[A Logical Calculus of the Ideas Immanent in Nervous Activity]]", "[[Activation function]]", "[[AdaBoost]]", "[[ADALINE]]", "[[Adaptive neuro fuzzy inference system]]"]
---

# Group method of data handling

Group method of data handling (GMDH) is a family of inductive, self-organizing algorithms for mathematical modelling that automatically determines the structure and parameters of models based on empirical data. GMDH iteratively generates and evaluates candidate models, often using polynomial functions, and selects the best-performing ones based on an external criterion. This process builds feedforward networks of optimal complexity, adapting to the noise level in the data and minimising overfitting, ensuring that the resulting model is accurate and generalizable.
GMDH is used in such fields as machine learning, forecasting, optimization and pattern recognition, due to its ability to handle complex, nonlinear relationships in data. Its inductive nature allows it to discover patterns and interdependencies without requiring strong a priori assumptions, making it particularly effective for highly complex systems. By balancing model complexity and accuracy through self-organization, GMDH ensures that the model reflects the underlying relationships in data. This approach has influenced modern machine learning techniques and is recognised as one of the earliest approaches to automated machine learning and deep learning.
A GMDH model with multiple inputs and one output is a subset of components of the base function (1):

  
    
      
        Y
        
          x
          
            1
          
        
        ,
        …
        ,
        
          x
          
            n
          
        
        =
        
          a
          
            0
          
        
        
          ∑
          
            i
            1
          
          
            m
          
        
        
          a
          
            i
          
        
        
          f
          
            i
          
        
      
    
    
  

where fi are elementary functions dependent on different sets of inputs, ai are coefficients and m is the number of the base function components.
In order to find the best solution, GMDH algorithms consider various component subsets of the base function (1) called partial models. Coefficients of these models are estimated by the least squares method. GMDH algorithms gradually increase the number of partial model components and find a model structure with optimal complexity indicated by the minimum value of an external criterion. This process is called self-organization of models.
As the first base function used in GMDH, was the gradually complicated Kolmogorov–Gabor polynomial (2):

  
    
      
        Y
        
          x
          
            1
          
        
        ,
        …
        ,
        
          x
          
            n
          
        
        =
        
          a
          
            0
          
        
        
          ∑
          
            i
            1
          
          
            n
          
        
        
          
            a
            
              i
            
          
        
        
          x
          
            i
          
        
        
          ∑
          
            i
            1
          
          
            n
          
        
        
          
            ∑
            
              j
              i
            
            
              n
            
          
          
            
              a
              
                i
                j
              
            
          
        
        
          x
          
            i
          
        
        
          x
          
            j
          
        
        
          ∑
          
            i
            1
          
          
            n
          
        
        
          
            ∑
            
              j
              i
            
            
              n
            
          
          
            
              ∑
              
                k
                j
              
              
                n
              
            
            
              
                a
                
                  i
                  j
                  k
                
              
            
          
        
        
          x
          
            i
          
        
        
          x
          
            j
          
        
        
          x
          
            k
          
        
        ⋯
      
    
    
  

Usually, more simple partial models with up to second degree functions are used.
Other names include "heuristic self-organization of models" or "polynomial feedforward neural network".  Jürgen Schmidhuber cites GMDH as one of the first deep learning methods, remarking that it was used to train eight-layer neural nets as early as 1971.

## Related

- [[Address programming language]]
- [[ALOPEX]]
- [[Hyper basis function network]]
- [[Perceptron]]
- [[(1+ε)-approximate nearest neighbor search]]
- [[A Logical Calculus of the Ideas Immanent in Nervous Activity]]
- [[Activation function]]
- [[AdaBoost]]
- [[ADALINE]]
- [[Adaptive neuro fuzzy inference system]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Group_method_of_data_handling