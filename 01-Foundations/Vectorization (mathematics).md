---
title: "Vectorization (mathematics)"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Vectorization_(mathematics)"
wikipedia_categories: ["Linear algebra", "Matrices (mathematics)"]
related: ["[[Centrosymmetric matrix]]", "[[Commutation matrix]]", "[[Conformable matrix]]", "[[Conjugate transpose]]", "[[Defective matrix]]", "[[Idempotent matrix]]", "[[Invertible matrix]]", "[[Kernel (linear algebra)]]", "[[Matrix analysis]]", "[[Matrix congruence]]"]
---

# Vectorization (mathematics)

In mathematics, especially in linear algebra and matrix theory, the vectorization of a matrix is a linear transformation which converts the matrix into a vector. Specifically, the vectorization of a m × n matrix A, denoted vec(A), is the mn × 1 column vector obtained by stacking the columns of the matrix A on top of one another:

  
    
      
        vec
         
        A
        =
        
          a
          
            1
            ,
            1
          
        
        ,
        …
        ,
        
          a
          
            m
            ,
            1
          
        
        ,
        
          a
          
            1
            ,
            2
          
        
        ,
        …
        ,
        
          a
          
            m
            ,
            2
          
        
        ,
        …
        ,
        
          a
          
            1
            ,
            n
          
        
        ,
        …
        ,
        
          a
          
            m
            ,
            n
          
        
        
          
            
              ⊤
            
          
        
      
    
    
  

Here, 
  
    
      
        
          a
          
            i
            ,
            j
          
        
      
    
    
  
 represents the element in the i-th row and j-th column of A, and the superscript 
  
    
      
        
          

          
          
            
              ⊤
            
          
        
      
    
    
  
 denotes the transpose. In other words, vec(A) is a vector containing the entries of A in column-major order.
Vectorization expresses, through coordinates, the isomorphism 
  
    
      
        
          
            R
          
          
            m
            n
          
        
        ≅
        
          
            R
          
          
            m
            n
          
        
      
    
    
  
 between these (i.e., of matrices and vectors) as vector spaces.
For example, for the 2×2 matrix 
  
    
      
        A
        
          
            
              
                
                  a
                
                
                  b
                
              
              
                
                  c
                
                
                  d
                
              
            
          
        
      
    
    
  
, the vectorization is 
  
    
      
        vec
         
        A
        =
        
          
            
              
                
                  a
                
              
              
                
                  c
                
              
              
                
                  b
                
              
              
                
                  d
                
              
            
          
        
      
    
    
  
.
The connection between the vectorization of A and the vectorization of its transpose is given by the commutation matrix.

## Related

- [[Centrosymmetric matrix]]
- [[Commutation matrix]]
- [[Conformable matrix]]
- [[Conjugate transpose]]
- [[Defective matrix]]
- [[Idempotent matrix]]
- [[Invertible matrix]]
- [[Kernel (linear algebra)]]
- [[Matrix analysis]]
- [[Matrix congruence]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Vectorization_(mathematics)