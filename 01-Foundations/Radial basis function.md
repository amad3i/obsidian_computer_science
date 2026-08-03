---
title: "Radial basis function"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Radial_basis_function"
wikipedia_categories: ["1988 in artificial intelligence", "Artificial neural networks", "Interpolation", "Numerical analysis"]
related: ["[[De Boor's algorithm]]", "[[Gal's accurate tables]]", "[[Identifiability analysis]]", "[[Radial basis function interpolation]]", "[[Unisolvent functions]]", "[[2Sum]]", "[[A Logical Calculus of the Ideas Immanent in Nervous Activity]]", "[[Abramowitz and Stegun]]", "[[Activation function]]", "[[ADALINE]]"]
---

# Radial basis function

In mathematics a radial basis function (RBF) is a real-valued function 
  
    
      
        φ
      
    
    {\textstyle \varphi }
  
 whose value depends only on the distance between the input and some fixed point, either the origin, so that 
  
    
      
        φ
        
          x
        
        =
        
          
            
              φ
              ^
            
          
        
        
          ‖
          
            x
          
          ‖
        
      
    
    {\textstyle \varphi (\mathbf {x} )={\hat {\varphi }}(\left\|\mathbf {x} \right\|)}
  
, or some other fixed point 
  
    
      
        
          c
        
      
    
    {\textstyle \mathbf {c} }
  
, called a center, so that 
  
    
      
        φ
        
          x
        
        =
        
          
            
              φ
              ^
            
          
        
        
          ‖
          
            
              x
            
            
              c
            
          
          ‖
        
      
    
    {\textstyle \varphi (\mathbf {x} )={\hat {\varphi }}(\left\|\mathbf {x} -\mathbf {c} \right\|)}
  
. Any function 
  
    
      
        φ
      
    
    {\textstyle \varphi }
  
 that satisfies the property 
  
    
      
        φ
        
          x
        
        =
        
          
            
              φ
              ^
            
          
        
        
          ‖
          
            x
          
          ‖
        
      
    
    {\textstyle \varphi (\mathbf {x} )={\hat {\varphi }}(\left\|\mathbf {x} \right\|)}
  
 is a radial function. The distance is usually Euclidean distance, although other metrics are sometimes used. They are often used as a collection 
  
    
      
        
          φ
          
            k
          
        
        
          
            k
          
        
      
    
    
  
 which forms a basis for some function space of interest, hence the name.
Sums of radial basis functions are typically used to approximate given functions. This approximation process can also be interpreted as a simple kind of neural network; this was the context in which they were originally applied to machine learning, in work by David Broomhead and David Lowe in 1988, which stemmed from Michael J. D. Powell's seminal research from 1977.
RBFs are also used as a kernel in support vector classification. The technique has proven effective and flexible enough that radial basis functions are now applied in a variety of engineering applications.

## Related

- [[De Boor's algorithm]]
- [[Gal's accurate tables]]
- [[Identifiability analysis]]
- [[Radial basis function interpolation]]
- [[Unisolvent functions]]
- [[2Sum]]
- [[A Logical Calculus of the Ideas Immanent in Nervous Activity]]
- [[Abramowitz and Stegun]]
- [[Activation function]]
- [[ADALINE]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Radial_basis_function