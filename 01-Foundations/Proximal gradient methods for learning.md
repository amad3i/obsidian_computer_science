---
title: "Proximal gradient methods for learning"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Proximal_gradient_methods_for_learning"
wikipedia_categories: ["Convex optimization", "First order methods", "Machine learning"]
related: ["[[Structured sparsity regularization]]", "[[80 Million Tiny Images]]", "[[A Logical Calculus of the Ideas Immanent in Nervous Activity]]", "[[Accelerated Linear Algebra]]", "[[Active learning (machine learning)]]", "[[Adversarial machine learning]]", "[[AI data center]]", "[[AI observability]]", "[[AIOps]]", "[[AIXI]]"]
---

# Proximal gradient methods for learning

Proximal gradient (forward backward splitting) methods for learning is an area of research in optimization and statistical learning theory which studies algorithms for a general class of convex regularization problems where the regularization penalty may not be differentiable. One such example is 
  
    
      
        
          ℓ
          
            1
          
        
      
    
    
  
 regularization (also known as Lasso) of the form

  
    
      
        
          min
          
            w
            ∈
            
              
                R
              
              
                d
              
            
          
        
        
          
            1
            n
          
        
        
          ∑
          
            i
            1
          
          
            n
          
        
        
          y
          
            i
          
        
        ⟨
        w
        ,
        
          x
          
            i
          
        
        ⟩
        
          
            2
          
        
        λ
        ‖
        w
        
          ‖
          
            1
          
        
        ,
        
        
           where 
        
        
          x
          
            i
          
        
        ∈
        
          
            R
          
          
            d
          
        
        
           and 
        
        
          y
          
            i
          
        
        ∈
        
          R
        
        .
      
    
    
  

Proximal gradient methods offer a general framework for solving regularization problems from statistical learning theory with penalties that are tailored to a specific problem application. Such customized penalties can help to induce certain structure in problem solutions, such as sparsity (in the case of lasso) or group structure (in the case of  group lasso).

## Related

- [[Structured sparsity regularization]]
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

- Wikipedia: https://en.wikipedia.org/wiki/Proximal_gradient_methods_for_learning