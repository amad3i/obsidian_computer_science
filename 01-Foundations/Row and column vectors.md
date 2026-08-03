---
title: "Row and column vectors"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Row_and_column_vectors"
wikipedia_categories: ["Linear algebra", "Matrices (mathematics)", "Vectors (mathematics and physics)"]
related: ["[[Centrosymmetric matrix]]", "[[Commutation matrix]]", "[[Complex conjugate of a vector space]]", "[[Conformable matrix]]", "[[Conjugate transpose]]", "[[Coordinate vector]]", "[[Defective matrix]]", "[[Dimension (vector space)]]", "[[Euclidean vector]]", "[[Idempotent matrix]]"]
---

# Row and column vectors

In linear algebra, a column vector with ⁠
  
    
      
        m
      
    
    
  
⁠ elements is an 
  
    
      
        m
        1
      
    
    
  
 matrix consisting of a single column of ⁠
  
    
      
        m
      
    
    
  
⁠ entries. Similarly, a row vector is a 
  
    
      
        1
        n
      
    
    
  
 matrix, consisting of a single row of ⁠
  
    
      
        n
      
    
    
  
⁠ entries. For example, ⁠
  
    
      
        
          x
        
      
    
    
  
⁠ is a column vector and ⁠
  
    
      
        
          a
        
      
    
    
  
⁠ is a row vector:

  
    
      
        
          x
        
        
          
            
              
                
                  
                    x
                    
                      1
                    
                  
                
              
              
                
                  
                    x
                    
                      2
                    
                  
                
              
              
                
                  ⋮
                
              
              
                
                  
                    x
                    
                      m
                    
                  
                
              
            
          
        
        ,
        
        
          a
        
        
          
            
              
                
                  
                    a
                    
                      1
                    
                  
                
                
                  
                    a
                    
                      2
                    
                  
                
                
                  …
                
                
                  
                    a
                    
                      n
                    
                  
                
              
            
          
        
        .
      
    
    
  

(Throughout this article, boldface is used for both row and column vectors.)
The transpose (indicated by T) of any row vector is a column vector, and the transpose of any column vector is a row vector:

  
    
      
        
          
            
              
                
                  
                    
                      x
                      
                        1
                      
                    
                    
                    
                      x
                      
                        2
                      
                    
                    
                    …
                    
                    
                      x
                      
                        m
                      
                    
                  
                
              
            
          
          
            
              T
            
          
        
        
          
            
              
                
                  
                    x
                    
                      1
                    
                  
                
              
              
                
                  
                    x
                    
                      2
                    
                  
                
              
              
                
                  ⋮
                
              
              
                
                  
                    x
                    
                      m
                    
                  
                
              
            
          
        
        ,
        
        
          
            
              
                
                  
                    
                      x
                      
                        1
                      
                    
                  
                
                
                  
                    
                      x
                      
                        2
                      
                    
                  
                
                
                  
                    ⋮
                  
                
                
                  
                    
                      x
                      
                        m
                      
                    
                  
                
              
            
          
          
            
              T
            
          
        
        
          
            
              
                
                  
                    x
                    
                      1
                    
                  
                  
                  
                    x
                    
                      2
                    
                  
                  
                  …
                  
                  
                    x
                    
                      m
                    
                  
                
              
            
          
        
        .
      
    
    
  

Taking the transpose twice returns the original (row or column) vector: ⁠
  
    
      
        
          
            
            
          
          
            
              x
            
            
              
                T
              
            
          
          
            
            
          
          
            
              
                
                  
                  
                
              
            
            
              
                T
              
            
          
          
            x
          
        
      
    
    
  
⁠.
The set of all row vectors with n entries in a given field (such as the real numbers) forms an n-dimensional vector space; similarly, the set of all column vectors with m entries forms an m-dimensional vector space.
The space of row vectors with n entries can be regarded as the dual space of the space of column vectors with n entries, since any linear functional on the space of column vectors can be represented as the left-multiplication of a unique row vector.

## Related

- [[Centrosymmetric matrix]]
- [[Commutation matrix]]
- [[Complex conjugate of a vector space]]
- [[Conformable matrix]]
- [[Conjugate transpose]]
- [[Coordinate vector]]
- [[Defective matrix]]
- [[Dimension (vector space)]]
- [[Euclidean vector]]
- [[Idempotent matrix]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Row_and_column_vectors