---
title: "Skew-Hamiltonian matrix"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Skew-Hamiltonian_matrix"
wikipedia_categories: ["Linear algebra", "Matrices (mathematics)", "Matrix stubs"]
related: ["[[Conformable matrix]]", "[[Reducing subspace]]", "[[Bidiagonal matrix]]", "[[Brandt matrix]]", "[[Centrosymmetric matrix]]", "[[Column groups and row groups]]", "[[Commutation matrix]]", "[[Conjugate transpose]]", "[[Cross Gramian]]", "[[Defective matrix]]"]
---

# Skew-Hamiltonian matrix

== Skew-Hamiltonian Matrices in Linear Algebra ==
In linear algebra, a skew-Hamiltonian matrix is a specific type of matrix that corresponds to a skew-symmetric bilinear form on a symplectic vector space. Let 
  
    
      
        V
      
    
    
  
 be a vector space equipped with a symplectic form, denoted by Ω. A symplectic vector space must necessarily be of even dimension.
A linear map 
  
    
      
        A
        :
        
        V
        ↦
        V
      
    
    
  
 is defined as a skew-Hamiltonian operator with respect to the symplectic form Ω if the bilinear form defined by 
  
    
      
        x
        ,
        y
        ↦
        Ω
        A
        x
        ,
        y
      
    
    
  
 is skew-symmetric.
Given a basis  
  
    
      
        
          e
          
            1
          
        
        ,
        …
        ,
        
          e
          
            2
            n
          
        
      
    
    
  
  in  
  
    
      
        V
      
    
    
  
 , the symplectic form  Ω  can be expressed as  
  
    
      
        
          ∑
          
            i
          
        
        
          e
          
            i
          
        
        ∧
        
          e
          
            n
            i
          
        
      
    
    {\textstyle \sum _{i}e_{i}\wedge e_{n+i}}
  
 . In this context, a linear operator 
  
    
      
        A
      
    
    
  
 is skew-Hamiltonian with respect to Ω if and only if its corresponding matrix satisfies the condition  
  
    
      
        
          A
          
            T
          
        
        J
        J
        A
      
    
    
  
, where  
  
    
      
        J
      
    
    
  
  is the skew-symmetric matrix defined as:

  
    
      
        J
        
          
            
              
                
                  0
                
                
                  
                    I
                    
                      n
                    
                  
                
              
              
                
                  
                    I
                    
                      n
                    
                  
                
                
                  0
                
              
            
          
        
      
    
    
  

With  
  
    
      
        
          I
          
            n
          
        
      
    
    
  
  representing the  
  
    
      
        n
        n
      
    
    
  
  identity matrix.
Matrices that meet this criterion are classified as skew-Hamiltonian matrices. Notably, the square of any Hamiltonian matrix is skew-Hamiltonian. Conversely, any skew-Hamiltonian matrix can be expressed as the square of a Hamiltonian matrix.

== Notes ==

## Related

- [[Conformable matrix]]
- [[Reducing subspace]]
- [[Bidiagonal matrix]]
- [[Brandt matrix]]
- [[Centrosymmetric matrix]]
- [[Column groups and row groups]]
- [[Commutation matrix]]
- [[Conjugate transpose]]
- [[Cross Gramian]]
- [[Defective matrix]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Skew-Hamiltonian_matrix