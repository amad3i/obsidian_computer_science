---
title: "Matrix regularization"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Matrix_regularization"
wikipedia_categories: ["Estimation theory", "Machine learning", "Matrices (mathematics)"]
related: ["[[Statistical learning theory]]", "[[80 Million Tiny Images]]", "[[A Logical Calculus of the Ideas Immanent in Nervous Activity]]", "[[Accelerated Linear Algebra]]", "[[Active learning (machine learning)]]", "[[Adversarial machine learning]]", "[[AI data center]]", "[[AI observability]]", "[[AIOps]]", "[[AIXI]]"]
---

# Matrix regularization

In the field of statistical learning theory, matrix regularization generalizes notions of vector regularization to cases where the object to be learned is a matrix. The purpose of regularization is to enforce conditions, for example sparsity or smoothness, that can produce stable predictive functions. For example, in the more common vector framework, Tikhonov regularization optimizes over

  
    
      
        
          min
          
            x
          
        
        
          
            ‖
            
              A
              x
              y
            
            ‖
          
          
            2
          
        
        λ
        
          
            ‖
            x
            ‖
          
          
            2
          
        
      
    
    
  

to find a vector 
  
    
      
        x
      
    
    
  
 that is a stable solution to the regression problem. When the system is described by a matrix rather than a vector, this problem  can be written as

  
    
      
        
          min
          
            X
          
        
        
          
            ‖
            
              A
              X
              Y
            
            ‖
          
          
            2
          
        
        λ
        
          
            ‖
            X
            ‖
          
          
            2
          
        
        ,
      
    
    
  

where the vector norm enforcing a regularization penalty on 
  
    
      
        x
      
    
    
  
 has been extended to a matrix norm on 
  
    
      
        X
      
    
    
  
.
Matrix regularization has applications in matrix completion, multivariate regression, and multi-task learning. Ideas of feature and group selection can also be extended to matrices, and these can be generalized to the nonparametric case of multiple kernel learning.

## Related

- [[Statistical learning theory]]
- [[80 Million Tiny Images]]
- [[A Logical Calculus of the Ideas Immanent in Nervous Activity]]
- [[Accelerated Linear Algebra]]
- [[Active learning (machine learning)]]
- [[Adversarial machine learning]]
- [[AI data center]]
- [[AI observability]]
- [[AIOps]]
- [[AIXI]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Matrix_regularization