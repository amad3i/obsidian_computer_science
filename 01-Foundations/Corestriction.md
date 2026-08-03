---
title: "Corestriction"
tags: ["cs", "foundations-math", "advanced"]
domain: Foundations & Math
level: advanced
source: "https://en.wikipedia.org/wiki/Corestriction"
wikipedia_categories: ["Abelian group theory", "Category theory", "Functions and mappings", "Hopf algebras", "Set theory"]
related: ["[[Categorical set theory]]", "[[Embedding]]", "[[Jónsson function]]", "[[Laver function]]", "[[List of set identities and relations]]", "[[Pairing function]]", "[[2-Yoneda lemma]]", "[[3-category]]", "[[3D projection]]", "[[AB5 category]]"]
---

# Corestriction

In mathematics, a corestriction of a function is a notion analogous to the notion of a restriction of a function. The duality prefix co- here denotes that while the restriction changes the domain to a subset, the corestriction changes the codomain to a subset. However, the notions are not categorically dual.
Given any subset 
  
    
      
        S
        ⊂
        A
        ,
      
    
    
  
 we can consider the corresponding inclusion of sets 
  
    
      
        
          i
          
            S
          
        
        :
        S
        ↪
        A
      
    
    
  
 as a function. Then for any function 
  
    
      
        f
        :
        A
        →
        B
      
    
    
  
, the restriction 
  
    
      
        f
        
          
            |
          
          
            S
          
        
        :
        S
        →
        B
      
    
    
  
 of a function 
  
    
      
        f
      
    
    
  
 onto 
  
    
      
        S
      
    
    
  
 can be defined as the composition 
  
    
      
        f
        
          
            |
          
          
            S
          
        
        f
        ∘
        
          i
          
            S
          
        
      
    
    
  
.
Analogously, for an inclusion 
  
    
      
        
          i
          
            T
          
        
        :
        T
        ↪
        B
      
    
    
  
 the corestriction 
  
    
      
        f
        
          
            |
          
          
            T
          
        
        :
        A
        →
        T
      
    
    
  
 of 
  
    
      
        f
      
    
    
  
 onto 
  
    
      
        T
      
    
    
  
 is the unique
function 
  
    
      
        f
        
          
            |
          
          
            T
          
        
      
    
    
  
 such that there is a decomposition 
  
    
      
        f
        
          i
          
            T
          
        
        ∘
        f
        
          
            |
          
          
            T
          
        
      
    
    
  
. The corestriction exists if and only if 
  
    
      
        T
      
    
    
  
 contains the image of 
  
    
      
        f
      
    
    
  
. In particular, the corestriction onto the image always exists and it is sometimes simply called the corestriction of 
  
    
      
        f
      
    
    
  
. More generally, one can consider corestriction of a morphism in general categories with images. The term is well known in category theory, while rarely used in print.
Andreotti introduces the above notion under the name coastriction, while the name corestriction reserves to the notion categorically dual to the notion of a restriction. Namely, if 
  
    
      
        
          p
          
            U
          
        
        :
        B
        →
        U
      
    
    
  
 is a surjection of sets (that is a quotient map) then Andreotti considers the composition 
  
    
      
        
          p
          
            U
          
        
        ∘
        f
        :
        A
        →
        U
      
    
    
  
, which surely always exists.

## Related

- [[Categorical set theory]]
- [[Embedding]]
- [[Jónsson function]]
- [[Laver function]]
- [[List of set identities and relations]]
- [[Pairing function]]
- [[2-Yoneda lemma]]
- [[3-category]]
- [[3D projection]]
- [[AB5 category]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Corestriction