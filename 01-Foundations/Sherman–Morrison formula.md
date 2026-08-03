---
title: "Sherman–Morrison formula"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Sherman–Morrison_formula"
wikipedia_categories: ["Linear algebra", "Matrix theory"]
related: ["[[Adjugate matrix]]", "[[Amitsur–Levitzki theorem]]", "[[Annihilating polynomial]]", "[[Bendixson's inequality]]", "[[Change of basis]]", "[[Computing the permanent]]", "[[Determinant]]", "[[Eigenoperator]]", "[[Eigenvalues and eigenvectors]]", "[[Faddeev–LeVerrier algorithm]]"]
---

# Sherman–Morrison formula

In linear algebra, the Sherman–Morrison formula, named after Jack Sherman and Winifred J. Morrison, computes the inverse of a "rank-1 update" to a matrix whose inverse has previously been computed. That is, given an invertible matrix 
  
    
      
        A
      
    
    
  
 and the outer product 
  
    
      
        u
        
          v
          
            
              T
            
          
        
      
    
    
  
 of vectors 
  
    
      
        u
      
    
    
  
 and 
  
    
      
        v
        ,
      
    
    
  
 the formula cheaply computes an updated matrix inverse 
  
    
      
        
          
            A
            u
            
              v
              
                
                  T
                
              
            
          
        
        
          
            
              
                
                
              
            
          
          
            
            1
          
        
        .
      
    
    {\textstyle \left(A+uv^{\textsf {T}}\right){\vphantom {)}}^{\!-1}.}
  

The Sherman–Morrison formula is a special case of the Woodbury formula. Though named after Sherman and Morrison, it appeared already in earlier publications.

## Related

- [[Adjugate matrix]]
- [[Amitsur–Levitzki theorem]]
- [[Annihilating polynomial]]
- [[Bendixson's inequality]]
- [[Change of basis]]
- [[Computing the permanent]]
- [[Determinant]]
- [[Eigenoperator]]
- [[Eigenvalues and eigenvectors]]
- [[Faddeev–LeVerrier algorithm]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Sherman–Morrison_formula