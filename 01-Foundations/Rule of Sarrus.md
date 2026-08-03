---
title: "Rule of Sarrus"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Rule_of_Sarrus"
wikipedia_categories: ["Determinants", "Linear algebra", "Mnemonics"]
related: ["[[Determinant]]", "[[Dieudonné determinant]]", "[[Faddeev–LeVerrier algorithm]]", "[[Hurwitz determinant]]", "[[Invertible matrix]]", "[[Leibniz formula for determinants]]", "[[3D projection]]", "[[Absolutely convex set]]", "[[Adjugate matrix]]", "[[Affine space]]"]
---

# Rule of Sarrus

In matrix theory, the rule of Sarrus is a mnemonic device for computing the determinant of a 
  
    
      
        3
        3
      
    
    
  
 matrix named after the French mathematician Pierre Frédéric Sarrus.
Consider a 
  
    
      
        3
        3
      
    
    
  
 matrix

  
    
      
        M
        
          
            
              
                
                  a
                
                
                  b
                
                
                  c
                
              
              
                
                  d
                
                
                  e
                
                
                  f
                
              
              
                
                  g
                
                
                  h
                
                
                  i
                
              
            
          
        
      
    
    
  

then its determinant can be computed by the following scheme.
Write out the first two columns of the matrix to the right of the third column, giving five columns in a row. Then add the products of the diagonals going from top to bottom (solid) and subtract the products of the diagonals going from bottom to top (dashed). This yields

  
    
      
        
          
            
              
                det
                M
                =
                
                  
                    |
                    
                      
                        
                          a
                        
                        
                          b
                        
                        
                          c
                        
                      
                      
                        
                          d
                        
                        
                          e
                        
                        
                          f
                        
                      
                      
                        
                          g
                        
                        
                          h
                        
                        
                          i
                        
                      
                    
                    |
                  
                
                a
                e
                i
                b
                f
                g
                c
                d
                h
                g
                e
                c
                h
                f
                a
                i
                d
                b
                .
              
            
          
        
      
    
    
  

A similar scheme based on diagonals works for 
  
    
      
        2
        2
      
    
    
  
 matrices:

  
    
      
        
          
            |
            
              
                
                  a
                
                
                  b
                
              
              
                
                  c
                
                
                  d
                
              
            
            |
          
        
        a
        d
        b
        c
      
    
    
  

Both are special cases of the Leibniz formula, which however does not yield similar memorization schemes for larger matrices. The determinants of 4x4 matrices can be found by expanding the most convenient row or column by cofactors and then applying the rule to each of the resulting determinants. (especially if there are elements in the matrix that are zero). For matrices beyond 4x4 it becomes impractical except for specific cases where there are many zero elements). Sarrus' rule can also be derived using the Laplace expansion of a 
  
    
      
        3
        3
      
    
    
  
 matrix.
Another way of thinking of Sarrus' rule is to imagine that the matrix is wrapped around a cylinder, such that the right and left edges are joined.

## Related

- [[Determinant]]
- [[Dieudonné determinant]]
- [[Faddeev–LeVerrier algorithm]]
- [[Hurwitz determinant]]
- [[Invertible matrix]]
- [[Leibniz formula for determinants]]
- [[3D projection]]
- [[Absolutely convex set]]
- [[Adjugate matrix]]
- [[Affine space]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Rule_of_Sarrus