---
title: "Karoubi envelope"
tags: ["cs", "foundations-math", "advanced"]
domain: Foundations & Math
level: advanced
source: "https://en.wikipedia.org/wiki/Karoubi_envelope"
wikipedia_categories: ["Category theory"]
related: ["[[2-Yoneda lemma]]", "[[3-category]]", "[[AB5 category]]", "[[Abstract elementary class]]", "[[Abstract nonsense]]", "[[Accessible category]]", "[[Accessible quasi-category]]", "[[Adhesive category]]", "[[Allegory (mathematics)]]", "[[Anamorphism]]"]
---

# Karoubi envelope

In mathematics the Karoubi envelope (or Cauchy completion or idempotent completion) of a category C is a classification of the idempotents of C, by means of an auxiliary category. Taking the Karoubi envelope of a preadditive category gives a pseudo-abelian category, hence for additive categories, the construction is sometimes called the pseudo-abelian completion. It is named for the French mathematician Max Karoubi.
Given a category C, an idempotent of C is an endomorphism 

  
    
      
        e
        :
        A
        →
        A
      
    
    
  

with 

  
    
      
        e
        ∘
        e
        e
      
    
    
  
.
An idempotent e: A → A is said to split if there is an object B and morphisms f: A → B,
g: B → A such that e = g f and 1B = f g.
The Karoubi envelope of C, sometimes written Split(C), is the category whose objects are pairs of the form (A, e) where A is an object of C and 
  
    
      
        e
        :
        A
        →
        A
      
    
    
  
 is an idempotent of C, and whose morphisms are the triples

  
    
      
        e
        ,
        f
        ,
        
          e
          
            ′
          
        
        :
        A
        ,
        e
        →
        
          A
          
            ′
          
        
        ,
        
          e
          
            ′
          
        
      
    
    
  

where 
  
    
      
        f
        :
        A
        →
        
          A
          
            ′
          
        
      
    
    
  
 is a morphism of C satisfying 
  
    
      
        
          e
          
            ′
          
        
        ∘
        f
        f
        f
        ∘
        e
      
    
    
  
 (or equivalently 
  
    
      
        f
        
          e
          ′
        
        ∘
        f
        ∘
        e
      
    
    
  
).
Composition in Split(C) is as in C, but the identity morphism 
on 
  
    
      
        A
        ,
        e
      
    
    
  
 in Split(C) is 
  
    
      
        e
        ,
        e
        ,
        e
      
    
    
  
, rather than
the identity on 
  
    
      
        A
      
    
    
  
.
The category C embeds fully and faithfully in Split(C). In Split(C) every idempotent splits, and Split(C) is the universal category with this property.
The Karoubi envelope of a category C can therefore be considered as the "completion" of C which splits idempotents.
The Karoubi envelope of a category C can equivalently be defined as the full subcategory of 
  
    
      
        
          
            
              
                C
              
              ^
            
          
        
      
    
    
  
 (the presheaves over C) of retracts of representable functors. The category of presheaves on C is equivalent to the category of presheaves on Split(C).

## Related

- [[2-Yoneda lemma]]
- [[3-category]]
- [[AB5 category]]
- [[Abstract elementary class]]
- [[Abstract nonsense]]
- [[Accessible category]]
- [[Accessible quasi-category]]
- [[Adhesive category]]
- [[Allegory (mathematics)]]
- [[Anamorphism]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Karoubi_envelope