---
title: "Orthogonal Procrustes problem"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Orthogonal_Procrustes_problem"
wikipedia_categories: ["Linear algebra", "Matrix theory", "Singular value decomposition"]
related: ["[[Eigenvalues and eigenvectors]]", "[[Singular value decomposition]]", "[[Spectral theorem]]", "[[Adjugate matrix]]", "[[Amitsur–Levitzki theorem]]", "[[Annihilating polynomial]]", "[[Bendixson's inequality]]", "[[Change of basis]]", "[[Computing the permanent]]", "[[Determinant]]"]
---

# Orthogonal Procrustes problem

The orthogonal Procrustes problem is a matrix approximation problem in linear algebra.  In its classical form, one is given two matrices 
  
    
      
        A
      
    
    
  
 and 
  
    
      
        B
      
    
    
  
 and asked to find an orthogonal matrix 
  
    
      
        Ω
      
    
    
  
 which most closely maps 
  
    
      
        A
      
    
    
  
 to 
  
    
      
        B
      
    
    
  
. Specifically, the orthogonal Procrustes problem is an optimization problem given by

  
    
      
        
          
            
              
                
                  
                    minimize
                    Ω
                  
                
                
              
              
                
                ‖
                Ω
                A
                B
                
                  ‖
                  
                    F
                  
                
              
            
            
              
                
                  subject to
                
                
              
              
                
                  Ω
                  
                    T
                  
                
                Ω
                I
                ,
              
            
          
        
      
    
    
  

where 
  
    
      
        ‖
        ⋅
        
          ‖
          
            F
          
        
      
    
    
  
 denotes the Frobenius norm.  This is a special case of Wahba's problem (with identical weights; instead of considering two matrices, in Wahba's problem the columns of the matrices are considered as individual vectors). Another difference is that Wahba's problem tries to find a proper rotation matrix instead of just an orthogonal one.
The name Procrustes refers to a bandit from Greek mythology who made his victims fit his bed by either stretching their limbs or cutting them off.

## Related

- [[Eigenvalues and eigenvectors]]
- [[Singular value decomposition]]
- [[Spectral theorem]]
- [[Adjugate matrix]]
- [[Amitsur–Levitzki theorem]]
- [[Annihilating polynomial]]
- [[Bendixson's inequality]]
- [[Change of basis]]
- [[Computing the permanent]]
- [[Determinant]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Orthogonal_Procrustes_problem