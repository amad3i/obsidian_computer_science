---
title: "Dual basis in a field extension"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Dual_basis_in_a_field_extension"
wikipedia_categories: ["Field extensions", "Linear algebra", "Theory of cryptography"]
related: ["[[Lattice reduction]]", "[[3D projection]]", "[[Absolutely convex set]]", "[[Adjugate matrix]]", "[[Affine space]]", "[[Amitsur–Levitzki theorem]]", "[[Angles between flats]]", "[[Annihilating polynomial]]", "[[Antilinear map]]", "[[Antiunitary operator]]"]
---

# Dual basis in a field extension

In mathematics, the linear algebra concept of dual basis can be applied in the context of a finite field extension L/K, by using the field trace. This requires the property that the field trace TrL/K  provides a non-degenerate quadratic form over K. This is true if L is separable over K; it is always true if K is a perfect field, including when K is finite or of characteristic zero.
A dual basis is not a specific basis like the polynomial basis or the normal basis; rather for any given basis, it is another associated basis which is useful for computations.
We say that two bases of a finite field 
  
    
      
        L
        
          GF
        
        
          p
          
            n
          
        
      
    
    
  
 over 
  
    
      
        K
        
          GF
        
        p
        =
        
          Z
        
        
          /
        
        p
        
          Z
        
      
    
    
  
,

  
    
      
        
          B
          
            1
          
        
        {
        
          α
          
            0
          
        
        ,
        
          α
          
            1
          
        
        ,
        …
        ,
        
          α
          
            n
            1
          
        
        ,
        
        
          B
          
            2
          
        
        {
        
          β
          
            0
          
        
        ,
        
          β
          
            1
          
        
        ,
        …
        ,
        
          β
          
            n
            1
          
        
        ,
      
    
    
  

are dual to each other provided

  
    
      
        Tr
         
        
          α
          
            i
          
        
        ⋅
        
          β
          
            j
          
        
        =
        
          
            
              
                
                  1
                
                
                  
                    if 
                  
                   
                  i
                  j
                
              
              
                
                  0
                
                
                  
                    if 
                  
                   
                  i
                  ≠
                  j
                  .
                
              
            
            
          
        
      
    
    
  

Here the trace of a value in GF(pm) can be calculated as follows:

  
    
      
        Tr
         
        γ
        =
        
          ∑
          
            i
            0
          
          
            n
            1
          
        
        
          γ
          
            
              p
              
                i
              
            
          
        
      
    
    
  

Using a dual basis can provide a way to easily communicate between devices that use different bases, rather than having to explicitly convert between bases using the change of bases formula.  Furthermore, if a dual basis is implemented then conversion from an element in the original basis to the dual basis can be accomplished with multiplication by the multiplicative identity (usually 1).

## Related

- [[Lattice reduction]]
- [[3D projection]]
- [[Absolutely convex set]]
- [[Adjugate matrix]]
- [[Affine space]]
- [[Amitsur–Levitzki theorem]]
- [[Angles between flats]]
- [[Annihilating polynomial]]
- [[Antilinear map]]
- [[Antiunitary operator]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Dual_basis_in_a_field_extension