---
title: "Leibniz formula for determinants"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Leibniz_formula_for_determinants"
wikipedia_categories: ["Determinants", "Gottfried Wilhelm Leibniz", "Linear algebra"]
related: ["[[Determinant]]", "[[Dieudonné determinant]]", "[[Faddeev–LeVerrier algorithm]]", "[[Hurwitz determinant]]", "[[Invertible matrix]]", "[[Rule of Sarrus]]", "[[3D projection]]", "[[Absolutely convex set]]", "[[Adjugate matrix]]", "[[Affine space]]"]
---

# Leibniz formula for determinants

In algebra, the Leibniz formula, named in honor of Gottfried Leibniz, expresses the determinant of a square matrix in terms of permutations of the matrix elements. If 
  
    
      
        A
      
    
    
  
 is an 
  
    
      
        n
        n
      
    
    
  
 matrix, where 
  
    
      
        
          a
          
            i
            j
          
        
      
    
    
  
 is the entry in the 
  
    
      
        i
      
    
    
  
-th row and 
  
    
      
        j
      
    
    
  
-th column of 
  
    
      
        A
      
    
    
  
, the formula is

  
    
      
        det
        A
        =
        
          ∑
          
            τ
            ∈
            
              S
              
                n
              
            
          
        
        sgn
         
        τ
        
          ∏
          
            i
            1
          
          
            n
          
        
        
          a
          
            i
            τ
            i
          
        
        
          ∑
          
            σ
            ∈
            
              S
              
                n
              
            
          
        
        sgn
         
        σ
        
          ∏
          
            i
            1
          
          
            n
          
        
        
          a
          
            σ
            i
            i
          
        
      
    
    
  

where 
  
    
      
        sgn
      
    
    
  
 is the sign function of permutations in the permutation group 
  
    
      
        
          S
          
            n
          
        
      
    
    
  
, which returns 
  
    
      
        1
      
    
    
  
 and 
  
    
      
        1
      
    
    
  
 for even and odd permutations, respectively.
Another common notation used for the formula is in terms of the Levi-Civita symbol and makes use of the Einstein summation notation, where it becomes

  
    
      
        det
        A
        =
        
          ϵ
          
            
              i
              
                1
              
            
            ⋯
            
              i
              
                n
              
            
          
        
        
          
            a
          
          
            1
            
              i
              
                1
              
            
          
        
        ⋯
        
          
            a
          
          
            n
            
              i
              
                n
              
            
          
        
        ,
      
    
    
  

which may be more familiar to physicists.
Directly evaluating the Leibniz formula from the definition requires 
  
    
      
        Ω
        n
        !
        ⋅
        n
      
    
    
  
  operations in general—that is, a number of operations asymptotically proportional to 
  
    
      
        n
      
    
    
  
 factorial—because 
  
    
      
        n
        !
      
    
    
  
 is the number of order-
  
    
      
        n
      
    
    
  
 permutations.  This is impractically difficult for even relatively small 
  
    
      
        n
      
    
    
  
.  Instead, the determinant can be evaluated in 
  
    
      
        O
        
          n
          
            3
          
        
      
    
    
  
 operations by forming the LU decomposition 
  
    
      
        A
        L
        U
      
    
    
  
 (typically via Gaussian elimination or similar methods), in which case 
  
    
      
        det
        A
        det
        L
        ⋅
        det
        U
      
    
    
  
 and the determinants of the triangular matrices 
  
    
      
        L
      
    
    
  
 and 
  
    
      
        U
      
    
    
  
 are simply the products of their diagonal entries.  (In practical applications of numerical linear algebra, however, explicit computation of the determinant is rarely required.)  See, for example, Trefethen & Bau (1997). The determinant can also be evaluated in fewer than 
  
    
      
        O
        
          n
          
            3
          
        
      
    
    
  
 operations by reducing the problem to matrix multiplication, but most such algorithms are not practical.

## Related

- [[Determinant]]
- [[Dieudonné determinant]]
- [[Faddeev–LeVerrier algorithm]]
- [[Hurwitz determinant]]
- [[Invertible matrix]]
- [[Rule of Sarrus]]
- [[3D projection]]
- [[Absolutely convex set]]
- [[Adjugate matrix]]
- [[Affine space]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Leibniz_formula_for_determinants