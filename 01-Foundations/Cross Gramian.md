---
title: "Cross Gramian"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Cross_Gramian"
wikipedia_categories: ["Analytic geometry", "Control theory", "Determinants", "Matrices (mathematics)", "Matrix stubs", "Systems theory", "Systems theory stubs"]
related: ["[[Rosenbrock system matrix]]", "[[Transfer function matrix]]", "[[Activity cycle diagram]]", "[[Allopoiesis]]", "[[Anticausal system]]", "[[Bartels–Stewart algorithm]]", "[[Brandt matrix]]", "[[Column groups and row groups]]", "[[Compensator (control theory)]]", "[[Conformable matrix]]"]
---

# Cross Gramian

In control theory, the cross Gramian (
  
    
      
        
          W
          
            X
          
        
      
    
    
  
, also referred to by 
  
    
      
        
          W
          
            C
            O
          
        
      
    
    
  
) is a Gramian matrix used to determine how controllable and observable a linear system is.
For the stable time-invariant linear system

  
    
      
        
          
            
              x
              ˙
            
          
        
        A
        x
        B
        u
        
      
    
    
  

  
    
      
        y
        C
        x
        
      
    
    
  

the cross Gramian is defined as:

  
    
      
        
          W
          
            X
          
        
        :=
        
          ∫
          
            0
          
          
            ∞
          
        
        
          e
          
            A
            t
          
        
        B
        C
        
          e
          
            A
            t
          
        
        d
        t
        
      
    
    
  

and thus also given by the solution to  the Sylvester equation:

  
    
      
        A
        
          W
          
            X
          
        
        
          W
          
            X
          
        
        A
        −
        B
        C
        
      
    
    
  

This means the cross Gramian is not strictly a Gramian matrix, since it is generally neither positive semi-definite nor symmetric.
The triple 
  
    
      
        A
        ,
        B
        ,
        C
      
    
    
  
 is controllable and observable, and hence minimal, if and only if the matrix 
  
    
      
        
          W
          
            X
          
        
      
    
    
  
 is nonsingular, (i.e. 
  
    
      
        
          W
          
            X
          
        
      
    
    
  
 has full rank, for any 
  
    
      
        t
        0
      
    
    
  
).
If the associated system 
  
    
      
        A
        ,
        B
        ,
        C
      
    
    
  
 is furthermore symmetric, such that there exists a transformation 
  
    
      
        J
      
    
    
  
 with

  
    
      
        A
        J
        J
        
          A
          
            T
          
        
        
      
    
    
  

  
    
      
        B
        J
        
          C
          
            T
          
        
        
      
    
    
  

then the absolute value of the eigenvalues of the cross Gramian equal Hankel singular values:

  
    
      
        
          |
        
        λ
        
          W
          
            X
          
        
        
          |
        
        
          
            λ
            
              W
              
                C
              
            
            
              W
              
                O
              
            
          
        
        .
        
      
    
    
  

Thus the direct truncation of the Eigendecomposition of the cross Gramian allows model order reduction (see ) without a balancing procedure as opposed to balanced truncation.
The cross Gramian has also applications in decentralized control, sensitivity analysis, and the inverse scattering transform.

## Related

- [[Rosenbrock system matrix]]
- [[Transfer function matrix]]
- [[Activity cycle diagram]]
- [[Allopoiesis]]
- [[Anticausal system]]
- [[Bartels–Stewart algorithm]]
- [[Brandt matrix]]
- [[Column groups and row groups]]
- [[Compensator (control theory)]]
- [[Conformable matrix]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Cross_Gramian