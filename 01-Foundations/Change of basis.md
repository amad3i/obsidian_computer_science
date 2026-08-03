---
title: "Change of basis"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Change_of_basis"
wikipedia_categories: ["Linear algebra", "Matrix theory"]
related: ["[[Adjugate matrix]]", "[[Amitsur–Levitzki theorem]]", "[[Annihilating polynomial]]", "[[Bendixson's inequality]]", "[[Computing the permanent]]", "[[Determinant]]", "[[Eigenoperator]]", "[[Eigenvalues and eigenvectors]]", "[[Faddeev–LeVerrier algorithm]]", "[[Generalized eigenvector]]"]
---

# Change of basis

In mathematics, an ordered basis of a vector space of finite dimension n allows representing uniquely any element of the vector space by a coordinate vector, which is a finite sequence of n scalars called coordinates. If two different bases are considered, the coordinate vector that represents a vector v on one basis is, in general, different from the coordinate vector that represents v on the other basis. A change of basis consists of converting every assertion expressed in terms of coordinates relative to one basis into an assertion expressed in terms of coordinates relative to the other basis.
Such a conversion results from the change-of-basis formula, which expresses the coordinates relative to one basis in terms of the coordinates relative to the other basis. Using matrices, this formula can be written

  
    
      
        
          
            x
          
          
            
              o
              l
              d
            
          
        
        A
         
        
          
            x
          
          
            
              n
              e
              w
            
          
        
        ,
      
    
    
  

where 
  
    
      
        
          
            x
          
          
            
              o
              l
              d
            
          
        
      
    
    
  
 and 
  
    
      
        
          
            x
          
          
            
              n
              e
              w
            
          
        
      
    
    
  
 are the column vectors of the coordinates of the same vector on the "old" (initially defined) and "new" (other) bases. 
  
    
      
        A
      
    
    
  
 is the change-of-basis matrix (also called transition matrix), which is the matrix whose columns are the coordinates of the "new" basis vectors on the "old" basis.

A change of basis is sometimes called a change of coordinates, although it excludes many coordinate transformations. For applications in physics and specially in mechanics, a change of basis often involves the transformation of an orthonormal basis, understood as a rotation in physical space, thus excluding translations.
This article deals mainly with finite-dimensional vector spaces. However, many of the presented principles are also valid for infinite-dimensional vector spaces.

## Related

- [[Adjugate matrix]]
- [[Amitsur–Levitzki theorem]]
- [[Annihilating polynomial]]
- [[Bendixson's inequality]]
- [[Computing the permanent]]
- [[Determinant]]
- [[Eigenoperator]]
- [[Eigenvalues and eigenvectors]]
- [[Faddeev–LeVerrier algorithm]]
- [[Generalized eigenvector]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Change_of_basis