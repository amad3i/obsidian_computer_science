---
title: "Cotriple homology"
tags: ["cs", "foundations-math", "advanced"]
domain: Foundations & Math
level: advanced
source: "https://en.wikipedia.org/wiki/Cotriple_homology"
wikipedia_categories: ["Adjoint functors", "Category theory", "Category theory stubs", "Homotopy theory"]
related: ["[[Isbell duality]]", "[[Pseudoalgebra]]", "[[3-category]]", "[[AB5 category]]", "[[Accessible quasi-category]]", "[[Adhesive category]]", "[[Applied category theory]]", "[[Associativity isomorphism]]", "[[Balanced category]]", "[[Beck's monadicity theorem]]"]
---

# Cotriple homology

In algebra, given a category C with a cotriple, the n-th cotriple homology of an object X in C with coefficients in a functor E is the n-th homotopy group of the E of the augmented simplicial object induced from X by the cotriple. The term "homology" is because in the abelian case, by the Dold–Kan correspondence, the homotopy groups are the homology of the corresponding chain complex.
Example: Let N be a left module over a ring R and let 
  
    
      
        E
        −
        
          ⊗
          
            R
          
        
        N
      
    
    
  
. Let F be the left adjoint of the forgetful functor from the category of rings to Set; i.e., free module functor. Then 
  
    
      
        F
        U
      
    
    
  
 defines a cotriple and the n-th cotriple homology of 
  
    
      
        E
        F
        
          U
          
          
        
        M
      
    
    
  
 is the n-th left derived functor of E evaluated at M; i.e., 
  
    
      
        
          Tor
          
            n
          
          
            R
          
        
         
        M
        ,
        N
      
    
    
  
.
Example (algebraic K-theory): Let us write GL for the functor 
  
    
      
        R
        ↦
        
          
            
              →
            
          
          
            n
          
        
         
        G
        
          L
          
            n
          
        
        R
      
    
    
  
. As before, 
  
    
      
        F
        U
      
    
    
  
 defines a cotriple on the category of rings with F free ring functor and U forgetful. For a ring R, one has:

  
    
      
        
          K
          
            n
          
        
        R
        =
        
          π
          
            n
            2
          
        
        G
        L
        F
        
          U
          
          
        
        R
        ,
        
        n
        ≥
        3
      
    
    
  
 
where on the left is the n-th K-group of R. This example is an instance of nonabelian homological algebra.

## Related

- [[Isbell duality]]
- [[Pseudoalgebra]]
- [[3-category]]
- [[AB5 category]]
- [[Accessible quasi-category]]
- [[Adhesive category]]
- [[Applied category theory]]
- [[Associativity isomorphism]]
- [[Balanced category]]
- [[Beck's monadicity theorem]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Cotriple_homology