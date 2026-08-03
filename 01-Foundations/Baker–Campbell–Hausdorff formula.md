---
title: "Baker–Campbell–Hausdorff formula"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Baker–Campbell–Hausdorff_formula"
wikipedia_categories: ["Combinatorics", "Exponentials", "Lie groups", "Mathematical physics"]
related: ["[[Combinatorics and physics]]", "[[Tau function (integrable systems)]]", "[[3-dimensional matching]]", "[[Aanderaa–Karp–Rosenberg conjecture]]", "[[Addition principle]]", "[[Algorithmic Lovász local lemma]]", "[[Algorithms and Combinatorics]]", "[[Alignments of random points]]", "[[All-pairs testing]]", "[[Arrangement of hyperplanes]]"]
---

# Baker–Campbell–Hausdorff formula

In mathematics, the Baker–Campbell–Hausdorff formula gives the value of 
  
    
      
        Z
      
    
    
  
 that solves the equation

  
    
      
        
          e
          
            X
          
        
        
          e
          
            Y
          
        
        
          e
          
            Z
          
        
      
    
    
  

for possibly noncommutative X and Y in the Lie algebra of a Lie group. There are various ways of writing the formula, but all ultimately yield an expression for 
  
    
      
        Z
      
    
    
  
 in Lie algebraic terms, that is, as a formal series (not necessarily convergent) in 
  
    
      
        X
      
    
    
  
 and 
  
    
      
        Y
      
    
    
  
 and iterated commutators thereof. The first few terms of this series are:

  
    
      
        Z
        X
        Y
        
          
            1
            2
          
        
        X
        ,
        Y
        +
        
          
            1
            12
          
        
        X
        ,
        X
        ,
        Y
        ]
        
          
            1
            12
          
        
        Y
        ,
        Y
        ,
        X
        ]
        ⋯
        
        ,
      
    
    
  

where "
  
    
      
        ⋯
      
    
    
  
" indicates terms involving higher commutators of 
  
    
      
        X
      
    
    
  
 and 
  
    
      
        Y
      
    
    
  
. If 
  
    
      
        X
      
    
    
  
 and 
  
    
      
        Y
      
    
    
  
 are sufficiently small elements of the Lie algebra 
  
    
      
        
          
            g
          
        
      
    
    
  
 of a Lie group 
  
    
      
        G
      
    
    
  
, the series is convergent. Meanwhile, every element 
  
    
      
        g
      
    
    
  
 sufficiently close to the identity in 
  
    
      
        G
      
    
    
  
 can be expressed as 
  
    
      
        g
        
          e
          
            X
          
        
      
    
    
  
 for a small 
  
    
      
        X
      
    
    
  
 in 
  
    
      
        
          
            g
          
        
      
    
    
  
. Thus, we can say that near the identity the group multiplication in 
  
    
      
        G
      
    
    
  
—written as 
  
    
      
        
          e
          
            X
          
        
        
          e
          
            Y
          
        
        
          e
          
            Z
          
        
      
    
    
  
—can be expressed in purely Lie algebraic terms. The Baker–Campbell–Hausdorff formula can be used to give comparatively simple proofs of deep results in the Lie group–Lie algebra correspondence.
If 
  
    
      
        X
      
    
    
  
 and 
  
    
      
        Y
      
    
    
  
 are sufficiently small 
  
    
      
        n
        n
      
    
    
  
 matrices, then 
  
    
      
        Z
      
    
    
  
 can be computed as the logarithm of 
  
    
      
        
          e
          
            X
          
        
        
          e
          
            Y
          
        
      
    
    
  
, where the exponentials and the logarithm can be computed as power series. The point of the Baker–Campbell–Hausdorff formula is then the highly nonobvious claim that 
  
    
      
        Z
        :=
         
        
          
            
              e
              
                X
              
            
            
              e
              
                Y
              
            
          
        
      
    
    
  
 can be expressed as a series in repeated commutators of 
  
    
      
        X
      
    
    
  
 and 
  
    
      
        Y
      
    
    
  
.
Modern expositions of the formula can be found in, among other places, the books of Rossmann and Hall.

## Related

- [[Combinatorics and physics]]
- [[Tau function (integrable systems)]]
- [[3-dimensional matching]]
- [[Aanderaa–Karp–Rosenberg conjecture]]
- [[Addition principle]]
- [[Algorithmic Lovász local lemma]]
- [[Algorithms and Combinatorics]]
- [[Alignments of random points]]
- [[All-pairs testing]]
- [[Arrangement of hyperplanes]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Baker–Campbell–Hausdorff_formula