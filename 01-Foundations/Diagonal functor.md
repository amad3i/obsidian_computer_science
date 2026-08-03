---
title: "Diagonal functor"
tags: ["cs", "foundations-math", "advanced"]
domain: Foundations & Math
level: advanced
source: "https://en.wikipedia.org/wiki/Diagonal_functor"
wikipedia_categories: ["Category theory", "Category theory stubs"]
related: ["[[3-category]]", "[[AB5 category]]", "[[Accessible quasi-category]]", "[[Adhesive category]]", "[[Applied category theory]]", "[[Associativity isomorphism]]", "[[Balanced category]]", "[[Categorical probability]]", "[[Categorical set theory]]", "[[Conservative functor]]"]
---

# Diagonal functor

In category theory, a branch of mathematics, the diagonal functor 
  
    
      
        
          
            C
          
        
        →
        
          
            C
          
        
        
          
            C
          
        
      
    
    
  
 is given by 
  
    
      
        Δ
        a
        =
        ⟨
        a
        ,
        a
        ⟩
      
    
    
  
, which maps objects as well as morphisms.  This functor can be employed to give a succinct alternate description of the product of objects within the category 
  
    
      
        
          
            C
          
        
      
    
    
  
: a product 
  
    
      
        a
        b
      
    
    
  
 is a universal arrow from 
  
    
      
        Δ
      
    
    
  
 to 
  
    
      
        ⟨
        a
        ,
        b
        ⟩
      
    
    
  
.  The arrow comprises the projection maps.
More generally, given a  small index category 
  
    
      
        
          
            J
          
        
      
    
    
  
, one may construct the functor category 
  
    
      
        
          
            
              C
            
          
          
            
              J
            
          
        
      
    
    
  
, the objects of which are called diagrams. For each object 
  
    
      
        a
      
    
    
  
 in 
  
    
      
        
          
            C
          
        
      
    
    
  
, there is a constant diagram 
  
    
      
        
          Δ
          
            a
          
        
        :
        
          
            J
          
        
        →
        
          
            C
          
        
      
    
    
  
 that maps every object in 
  
    
      
        
          
            J
          
        
      
    
    
  
 to 
  
    
      
        a
      
    
    
  
 and every morphism in 
  
    
      
        
          
            J
          
        
      
    
    
  
 to 
  
    
      
        
          1
          
            a
          
        
      
    
    
  
. The diagonal functor 
  
    
      
        Δ
        :
        
          
            C
          
        
        →
        
          
            
              C
            
          
          
            
              J
            
          
        
      
    
    
  
 assigns to each object 
  
    
      
        a
      
    
    
  
 of 
  
    
      
        
          
            C
          
        
      
    
    
  
 the diagram 
  
    
      
        
          Δ
          
            a
          
        
      
    
    
  
, and to each morphism 
  
    
      
        f
        :
        a
        →
        b
      
    
    
  
 in 
  
    
      
        
          
            C
          
        
      
    
    
  
 the natural transformation 
  
    
      
        η
      
    
    
  
 in 
  
    
      
        
          
            
              C
            
          
          
            
              J
            
          
        
      
    
    
  
 (given for every object 
  
    
      
        j
      
    
    
  
 of 
  
    
      
        
          
            J
          
        
      
    
    
  
 by 
  
    
      
        
          η
          
            j
          
        
        f
      
    
    
  
).  Thus, for example, in the case that 
  
    
      
        
          
            J
          
        
      
    
    
  
 is a discrete category with two objects, the diagonal functor 
  
    
      
        
          
            C
          
        
        →
        
          
            C
          
        
        
          
            C
          
        
      
    
    
  
 is recovered.
Diagonal functors provide a way to define limits and colimits of diagrams. Given a diagram 
  
    
      
        
          
            F
          
        
        :
        
          
            J
          
        
        →
        
          
            C
          
        
      
    
    
  
, a natural transformation 
  
    
      
        
          Δ
          
            a
          
        
        →
        
          
            F
          
        
      
    
    
  
 (for some object 
  
    
      
        a
      
    
    
  
 of 
  
    
      
        
          
            C
          
        
      
    
    
  
) is called a cone for 
  
    
      
        
          
            F
          
        
      
    
    
  
. These cones and their factorizations correspond precisely to the objects and morphisms of the comma category 
  
    
      
        Δ
        ↓
        
          
            F
          
        
      
    
    
  
, and a limit of 
  
    
      
        
          
            F
          
        
      
    
    
  
 is a terminal object in 
  
    
      
        Δ
        ↓
        
          
            F
          
        
      
    
    
  
, i.e., a universal arrow 
  
    
      
        Δ
        →
        
          
            F
          
        
      
    
    
  
. Dually, a colimit of 
  
    
      
        
          
            F
          
        
      
    
    
  
 is an initial object in the comma category 
  
    
      
        
          
            F
          
        
        ↓
        Δ
      
    
    
  
, i.e., a universal arrow 
  
    
      
        
          
            F
          
        
        →
        Δ
      
    
    
  
.
If every functor from 
  
    
      
        
          
            J
          
        
      
    
    
  
 to 
  
    
      
        
          
            C
          
        
      
    
    
  
 has a limit (which will be the case if 
  
    
      
        
          
            C
          
        
      
    
    
  
 is complete), then the operation of taking limits is itself a functor from 
  
    
      
        
          
            
              C
            
          
          
            
              J
            
          
        
      
    
    
  
 to 
  
    
      
        
          
            C
          
        
      
    
    
  
.  The limit functor is the right-adjoint of the diagonal functor.  Similarly, the colimit functor (which exists if the category is cocomplete) is the left-adjoint of the diagonal functor. For example, the diagonal functor 
  
    
      
        
          
            C
          
        
        →
        
          
            C
          
        
        
          
            C
          
        
      
    
    
  
 described above is the left-adjoint of the binary product functor and the right-adjoint of the binary coproduct functor.

## Related

- [[3-category]]
- [[AB5 category]]
- [[Accessible quasi-category]]
- [[Adhesive category]]
- [[Applied category theory]]
- [[Associativity isomorphism]]
- [[Balanced category]]
- [[Categorical probability]]
- [[Categorical set theory]]
- [[Conservative functor]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Diagonal_functor