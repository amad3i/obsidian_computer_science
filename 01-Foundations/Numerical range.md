---
title: "Numerical range"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Numerical_range"
wikipedia_categories: ["Linear algebra", "Matrix theory", "Operator theory", "Spectral theory"]
related: ["[[Spectral theorem]]", "[[Adjugate matrix]]", "[[Amitsur–Levitzki theorem]]", "[[Annihilating polynomial]]", "[[Bendixson's inequality]]", "[[Cauchy–Schwarz inequality]]", "[[Change of basis]]", "[[Choi's theorem on completely positive maps]]", "[[Computing the permanent]]", "[[Controlled invariant subspace]]"]
---

# Numerical range

In the mathematical field of linear algebra and convex analysis, the numerical range or field of values or Wertvorrat or Wertevorrat of a complex 
  
    
      
        n
        n
      
    
    
  
 matrix A is the set

  
    
      
        W
        A
        =
        
          
            
              
                
                  
                    
                      x
                    
                    
                    
                  
                  A
                  
                    x
                  
                
                
                  
                    
                      x
                    
                    
                    
                  
                  
                    x
                  
                
              
            
            ∣
            
              x
            
            ∈
            
              
                C
              
              
                n
              
            
            ,
             
            
              x
            
            ≠
            0
          
        
        
          
            ⟨
            
              x
            
            ,
            A
            
              x
            
            ⟩
            ∣
            
              x
            
            ∈
            
              
                C
              
              
                n
              
            
            ,
             
            ‖
            
              x
            
            
              ‖
              
                2
              
            
            1
          
        
      
    
    
  

where 
  
    
      
        
          
            x
          
          
          
        
      
    
    
  
 denotes the conjugate transpose of the vector 
  
    
      
        
          x
        
      
    
    
  
. The numerical range includes, in particular, the diagonal entries of the matrix (obtained by choosing x equal to the unit vectors along the coordinate axes) and the eigenvalues of the matrix (obtained by choosing x equal to the eigenvectors).
Equivalently, the elements of 
  
    
      
        W
        A
      
    
    {\textstyle W(A)}
  
 are of the form  
  
    
      
        tr
         
        A
        P
      
    
    {\textstyle \operatorname {tr} (AP)}
  
, where 
  
    
      
        P
      
    
    {\textstyle P}
  
 is a Hermitian projection operator from  
  
    
      
        
          
            C
          
          
            n
          
        
      
    
    {\textstyle \mathbb {C} ^{n}}
  
 to a one-dimensional subspace.
In engineering, numerical ranges are used as a rough estimate of eigenvalues of A. Recently, generalizations of the numerical range are used to study quantum computing.
A related concept is the numerical radius, which is the largest absolute value of the numbers in the numerical range, i.e.

  
    
      
        r
        A
        =
        sup
        
          |
        
        λ
        
          |
        
        :
        λ
        ∈
        W
        A
        }
        
          sup
          
            ‖
            x
            
              ‖
              
                2
              
            
            1
          
        
        
          |
        
        ⟨
        
          x
        
        ,
        A
        
          x
        
        ⟩
        
          |
        
        .
      
    
    

## Related

- [[Spectral theorem]]
- [[Adjugate matrix]]
- [[Amitsur–Levitzki theorem]]
- [[Annihilating polynomial]]
- [[Bendixson's inequality]]
- [[Cauchy–Schwarz inequality]]
- [[Change of basis]]
- [[Choi's theorem on completely positive maps]]
- [[Computing the permanent]]
- [[Controlled invariant subspace]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Numerical_range