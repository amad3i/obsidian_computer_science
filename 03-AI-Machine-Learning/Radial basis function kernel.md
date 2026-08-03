---
title: "Radial basis function kernel"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Radial_basis_function_kernel"
wikipedia_categories: ["Kernel methods for machine learning", "Support vector machines"]
related: ["[[Support vector machine]]", "[[Fisher kernel]]", "[[Gaussian process]]", "[[Graph kernel]]", "[[Hinge loss]]", "[[Kernel adaptive filter]]", "[[Kernel eigenvoice]]", "[[Kernel methods for vector output]]", "[[Kernel perceptron]]", "[[Kernel principal component analysis]]"]
---

# Radial basis function kernel

In machine learning, the radial basis function kernel, or RBF kernel, is a popular kernel function used in various kernelized learning algorithms. In particular, it is commonly used in support vector machine classification.
The RBF kernel on two samples 
  
    
      
        
          x
        
        ,
        
          
            x
            ′
          
        
        ∈
        
          
            R
          
          
            k
          
        
      
    
    
  
, represented as feature vectors in some input space, is defined as

  
    
      
        K
        
          x
        
        ,
        
          
            x
            ′
          
        
        =
        exp
         
        
          
            
              
                
                  ‖
                  
                    x
                  
                  
                    
                      x
                      ′
                    
                  
                  
                    ‖
                    
                      2
                    
                  
                
                
                  2
                  
                    σ
                    
                      2
                    
                  
                
              
            
          
        
      
    
    
  

  
    
      
        
          ‖
          
            x
          
          
            
              x
              ′
            
          
          
            ‖
            
              2
            
          
        
      
    
    
  
 may be recognized as the squared Euclidean distance between the two feature vectors. 
  
    
      
        σ
      
    
    
  
 is a free parameter. An equivalent definition involves a parameter 
  
    
      
        
          γ
          
            
              
                1
                
                  2
                  
                    σ
                    
                      2
                    
                  
                
              
            
          
        
      
    
    
  
:

  
    
      
        K
        
          x
        
        ,
        
          
            x
            ′
          
        
        =
        exp
         
        −
        γ
        ‖
        
          x
        
        
          
            x
            ′
          
        
        
          ‖
          
            2
          
        
      
    
    
  

Since the value of the RBF kernel decreases with distance and ranges between zero (in the infinite-distance limit) and one (when x = x'), it has a ready interpretation as a similarity measure.
The feature space of the kernel has an infinite number of dimensions; for 
  
    
      
        σ
        1
      
    
    
  
, its expansion using the multinomial theorem is:

  
    
      
        
          
            
              
                exp
                 
                
                  
                    
                      
                        1
                        2
                      
                    
                    ‖
                    
                      x
                    
                    
                      
                        x
                        ′
                      
                    
                    
                      ‖
                      
                        2
                      
                    
                  
                
              
              
                
                exp
                 
                
                  
                    
                      
                        2
                        2
                      
                    
                    
                      
                        x
                      
                      
                        ⊤
                      
                    
                    
                      
                        x
                        ′
                      
                    
                    
                      
                        1
                        2
                      
                    
                    ‖
                    
                      x
                    
                    
                      ‖
                      
                        2
                      
                    
                    
                      
                        1
                        2
                      
                    
                    ‖
                    
                      
                        x
                        ′
                      
                    
                    
                      ‖
                      
                        2
                      
                    
                  
                
              
            
            
              
              
                
                exp
                 
                
                  
                    
                      
                        x
                      
                      
                        ⊤
                      
                    
                    
                      
                        x
                        ′
                      
                    
                  
                
                exp
                 
                
                  
                    
                      
                        1
                        2
                      
                    
                    ‖
                    
                      x
                    
                    
                      ‖
                      
                        2
                      
                    
                  
                
                exp
                 
                
                  
                    
                      
                        1
                        2
                      
                    
                    ‖
                    
                      
                        x
                        ′
                      
                    
                    
                      ‖
                      
                        2
                      
                    
                  
                
              
            
            
              
              
                
                
                  ∑
                  
                    j
                    0
                  
                  
                    ∞
                  
                
                
                  
                    
                      
                        
                          x
                        
                        
                          ⊤
                        
                      
                      
                        
                          x
                          ′
                        
                      
                      
                        
                          j
                        
                      
                    
                    
                      j
                      !
                    
                  
                
                exp
                 
                
                  
                    
                      
                        1
                        2
                      
                    
                    ‖
                    
                      x
                    
                    
                      ‖
                      
                        2
                      
                    
                  
                
                exp
                 
                
                  
                    
                      
                        1
                        2
                      
                    
                    ‖
                    
                      
                        x
                        ′
                      
                    
                    
                      ‖
                      
                        2
                      
                    
                  
                
              
            
            
              
              
                
                
                  ∑
                  
                    j
                    0
                  
                  
                    ∞
                  
                
                
                
                  ∑
                  
                    
                      n
                      
                        1
                      
                    
                    
                      n
                      
                        2
                      
                    
                    ⋯
                    
                      n
                      
                        k
                      
                    
                    j
                  
                
                exp
                 
                
                  
                    
                      
                        1
                        2
                      
                    
                    ‖
                    
                      x
                    
                    
                      ‖
                      
                        2
                      
                    
                  
                
                
                  
                    
                      
                        x
                        
                          1
                        
                        
                          
                            n
                            
                              1
                            
                          
                        
                      
                      ⋯
                      
                        x
                        
                          k
                        
                        
                          
                            n
                            
                              k
                            
                          
                        
                      
                    
                    
                      
                        n
                        
                          1
                        
                      
                      !
                      ⋯
                      
                        n
                        
                          k
                        
                      
                      !
                    
                  
                
                exp
                 
                
                  
                    
                      
                        1
                        2
                      
                    
                    ‖
                    
                      
                        x
                        ′
                      
                    
                    
                      ‖
                      
                        2
                      
                    
                  
                
                
                  
                    
                      
                        
                          
                            x
                            ′
                          
                        
                        
                          1
                        
                        
                          
                            n
                            
                              1
                            
                          
                        
                      
                      ⋯
                      
                        
                          
                            x
                            ′
                          
                        
                        
                          k
                        
                        
                          
                            n
                            
                              k
                            
                          
                        
                      
                    
                    
                      
                        n
                        
                          1
                        
                      
                      !
                      ⋯
                      
                        n
                        
                          k
                        
                      
                      !
                    
                  
                
              
            
            
              
              
                
                ⟨
                φ
                
                  x
                
                ,
                φ
                
                  
                    x
                    ′
                  
                
                ⟩
              
            
          
        
      
    
    
  

  
    
      
        φ
        
          x
        
        =
        exp
         
        
          
            
              
                1
                2
              
            
            ‖
            
              x
            
            
              ‖
              
                2
              
            
          
        
        
          
            
              a
              
                
                  ℓ
                  
                    0
                  
                
              
              
                0
              
            
            ,
            
              a
              
                1
              
              
                1
              
            
            ,
            …
            ,
            
              a
              
                
                  ℓ
                  
                    1
                  
                
              
              
                1
              
            
            ,
            …
            ,
            
              a
              
                1
              
              
                j
              
            
            ,
            …
            ,
            
              a
              
                
                  ℓ
                  
                    j
                  
                
              
              
                j
              
            
            ,
            …
          
        
      
    
    
  

where 
  
    
      
        
          ℓ
          
            j
          
        
        
          
            
              
              
              
                
                  k
                  j
                  1
                
                j
              
              
              
            
          
        
      
    
    
  
,

  
    
      
        
          a
          
            ℓ
          
          
            j
          
        
        
          
            
              
                x
                
                  1
                
                
                  
                    n
                    
                      1
                    
                  
                
              
              ⋯
              
                x
                
                  k
                
                
                  
                    n
                    
                      k
                    
                  
                
              
            
            
              
                n
                
                  1
                
              
              !
              ⋯
              
                n
                
                  k
                
              
              !
            
          
        
        
        
          |
        
        
        
          n
          
            1
          
        
        
          n
          
            2
          
        
        ⋯
        
          n
          
            k
          
        
        j
        ∧
        1
        ≤
        ℓ
        ≤
        
          ℓ
          
            j
          
        
      
    
    

*(note truncated for size; full article at the source link below)*

## Related

- [[Support vector machine]]
- [[Fisher kernel]]
- [[Gaussian process]]
- [[Graph kernel]]
- [[Hinge loss]]
- [[Kernel adaptive filter]]
- [[Kernel eigenvoice]]
- [[Kernel methods for vector output]]
- [[Kernel perceptron]]
- [[Kernel principal component analysis]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Radial_basis_function_kernel