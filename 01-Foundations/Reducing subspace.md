---
title: "Reducing subspace"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Reducing_subspace"
wikipedia_categories: ["Linear algebra", "Matrices (mathematics)", "Matrix stubs"]
related: ["[[Conformable matrix]]", "[[Skew-Hamiltonian matrix]]", "[[Bidiagonal matrix]]", "[[Brandt matrix]]", "[[Centrosymmetric matrix]]", "[[Column groups and row groups]]", "[[Commutation matrix]]", "[[Conjugate transpose]]", "[[Cross Gramian]]", "[[Defective matrix]]"]
---

# Reducing subspace

In linear algebra, a reducing subspace 
  
    
      
        W
      
    
    
  
 of a linear map 
  
    
      
        T
        :
        V
        →
        V
      
    
    
  
 from a Hilbert space 
  
    
      
        V
      
    
    
  
 to itself is an invariant subspace of 
  
    
      
        T
      
    
    
  
 whose orthogonal complement 
  
    
      
        
          W
          
            ⊥
          
        
      
    
    
  
 is also an invariant subspace of 
  
    
      
        T
        .
      
    
    
  
 That is, 
  
    
      
        T
        W
        ⊆
        W
      
    
    
  
 and 
  
    
      
        T
        
          W
          
            ⊥
          
        
        ⊆
        
          W
          
            ⊥
          
        
        .
      
    
    
  
 One says that the subspace 
  
    
      
        W
      
    
    
  
 reduces the map 
  
    
      
        T
        .
      
    
    
  

One says that a linear map is reducible if it has a nontrivial reducing subspace. Otherwise one says it is irreducible.
If 
  
    
      
        V
      
    
    
  
 is of finite dimension 
  
    
      
        r
      
    
    
  
 and 
  
    
      
        W
      
    
    
  
 is a reducing subspace of the map 
  
    
      
        T
        :
        V
        →
        V
      
    
    
  
 represented under basis 
  
    
      
        B
      
    
    
  
 by matrix 
  
    
      
        M
        ∈
        
          
            R
          
          
            r
            r
          
        
      
    
    
  
 then 
  
    
      
        M
      
    
    
  
 can be expressed as the sum

  
    
      
        M
        
          P
          
            W
          
        
        M
        
          P
          
            W
          
        
        
          P
          
            
              W
              
                ⊥
              
            
          
        
        M
        
          P
          
            
              W
              
                ⊥
              
            
          
        
      
    
    
  

where 
  
    
      
        
          P
          
            W
          
        
        ∈
        
          
            R
          
          
            r
            r
          
        
      
    
    
  
 is the matrix of the orthogonal projection from 
  
    
      
        V
      
    
    
  
 to 
  
    
      
        W
      
    
    
  
 and 
  
    
      
        
          P
          
            
              W
              
                ⊥
              
            
          
        
        I
        
          P
          
            W
          
        
      
    
    
  
 is the matrix of the projection onto 
  
    
      
        
          W
          
            ⊥
          
        
        .
      
    
    
  
  (Here 
  
    
      
        I
        ∈
        
          
            R
          
          
            r
            r
          
        
      
    
    
  
 is the identity matrix.)
Furthermore, 
  
    
      
        V
      
    
    
  
 has an orthonormal basis 
  
    
      
        
          B
          ′
        
      
    
    
  
 with a subset that is an orthonormal basis of 
  
    
      
        W
      
    
    
  
. If 
  
    
      
        Q
        ∈
        
          
            R
          
          
            r
            r
          
        
      
    
    
  
 is the transition matrix from 
  
    
      
        B
      
    
    
  
 to 
  
    
      
        
          B
          ′
        
      
    
    
  
 then with respect to 
  
    
      
        
          B
          ′
        
      
    
    
  
 the matrix 
  
    
      
        
          Q
          
            1
          
        
        M
        Q
      
    
    
  
 representing 
  
    
      
        T
      
    
    
  
 is a block-diagonal matrix

  
    
      
        
          Q
          
            1
          
        
        M
        Q
        
          
            
              
                
                  A
                
                
                  0
                
              
              
                
                  0
                
                
                  B
                
              
            
          
        
      
    
    
  

with 
  
    
      
        A
        ∈
        
          
            R
          
          
            d
            d
          
        
        ,
      
    
    
  
 where 
  
    
      
        d
        dim
         
        W
      
    
    
  
, and 
  
    
      
        B
        ∈
        
          
            R
          
          
            r
            d
            ×
            r
            d
          
        
        .
      
    
    

## Related

- [[Conformable matrix]]
- [[Skew-Hamiltonian matrix]]
- [[Bidiagonal matrix]]
- [[Brandt matrix]]
- [[Centrosymmetric matrix]]
- [[Column groups and row groups]]
- [[Commutation matrix]]
- [[Conjugate transpose]]
- [[Cross Gramian]]
- [[Defective matrix]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Reducing_subspace