---
title: "Size functor"
tags: ["cs", "foundations-math", "advanced"]
domain: Foundations & Math
level: advanced
source: "https://en.wikipedia.org/wiki/Size_functor"
wikipedia_categories: ["Algebraic topology", "Category theory"]
related: ["[[Categorification]]", "[[Cosheaf]]", "[[Esquisse d'un Programme]]", "[[Higher-dimensional algebra]]", "[[Induced homomorphism]]", "[[R-algebroid]]", "[[2-Yoneda lemma]]", "[[3-category]]", "[[AB5 category]]", "[[Abstract elementary class]]"]
---

# Size functor

Given a size pair  
  
    
      
        M
        ,
        f
         
      
    
    
  
 where 
  
    
      
        M
         
      
    
    
  
 is a manifold of dimension

  
    
      
        n
         
      
    
    
  
 and 
  
    
      
        f
         
      
    
    
  
 is an arbitrary real continuous function  defined
on it, the 
  
    
      
        i
      
    
    
  
-th size functor, with 
  
    
      
        i
        0
        ,
        …
        ,
        n
         
      
    
    
  
, denoted by 
  
    
      
        
          F
          
            i
          
        
         
      
    
    
  
, is the functor in 
  
    
      
        F
        u
        n
        
          R
          o
          r
          d
        
        ,
        
          A
          b
        
         
      
    
    
  
, where  
  
    
      
        
          R
          o
          r
          d
        
         
      
    
    
  
 is the category of  ordered real numbers, and 
  
    
      
        
          A
          b
        
         
      
    
    
  
 is the category of Abelian groups, defined in the following way. For 
  
    
      
        x
        ≤
        y
         
      
    
    
  
, setting  
  
    
      
        
          M
          
            x
          
        
        {
        p
        ∈
        M
        :
        f
        p
        ≤
        x
         
      
    
    
  
, 
  
    
      
        
          M
          
            y
          
        
        {
        p
        ∈
        M
        :
        f
        p
        ≤
        y
         
      
    
    
  
, 
  
    
      
        
          j
          
            x
            y
          
        
         
      
    
    
  
 equal to the inclusion from 
  
    
      
        
          M
          
            x
          
        
         
      
    
    
  
 into 
  
    
      
        
          M
          
            y
          
        
         
      
    
    
  
, and 
  
    
      
        
          k
          
            x
            y
          
        
         
      
    
    
  
 equal to the morphism in 
  
    
      
        
          R
          o
          r
          d
        
         
      
    
    
  
 from 
  
    
      
        x
         
      
    
    
  
 to 
  
    
      
        y
         
      
    
    
  
,

for each 
  
    
      
        x
        ∈
        
          R
        
         
      
    
    
  
, 
  
    
      
        
          F
          
            i
          
        
        x
        =
        
          H
          
            i
          
        
        
          M
          
            x
          
        
        ;
         
      
    
    
  

  
    
      
        
          F
          
            i
          
        
        
          k
          
            x
            y
          
        
        =
        
          H
          
            i
          
        
        
          j
          
            x
            y
          
        
        .
         
      
    
    
  

In other words, the size functor  studies the
process of the birth and death of homology classes as the lower level set changes.
When 
  
    
      
        M
         
      
    
    
  
 is smooth and compact and 
  
    
      
        f
         
      
    
    
  
 is a Morse function, the functor 
  
    
      
        
          F
          
            0
          
        
         
      
    
    
  
 can be
described by oriented trees, called 
  
    
      
        
          H
          
            0
          
        
         
      
    
    
  
 − trees.
The concept of size functor was introduced as an extension to homology theory and category theory of the idea of size function.  The main motivation for introducing the size functor originated  by the observation that the size function 
  
    
      
        
          ℓ
          
            M
            ,
            f
          
        
        x
        ,
        y
         
      
    
    
  
 can be seen as the rank
of the image of 
  
    
      
        
          H
          
            0
          
        
        
          j
          
            x
            y
          
        
        :
        
          H
          
            0
          
        
        
          M
          
            x
          
        
        →
        
          H
          
            0
          
        
        
          M
          
            y
          
        
      
    
    
  
.
The concept of size functor is strictly related to the concept of persistent homology group, studied in persistent homology. It is worth to point out that the 
  
    
      
        i
         
      
    
    
  
-th persistent homology group coincides with the image of the homomorphism 
  
    
      
        
          F
          
            i
          
        
        
          k
          
            x
            y
          
        
        =
        
          H
          
            i
          
        
        
          j
          
            x
            y
          
        
        :
        
          H
          
            i
          
        
        
          M
          
            x
          
        
        →
        
          H
          
            i
          
        
        
          M
          
            y
          
        
      
    
    
  
.

## Related

- [[Categorification]]
- [[Cosheaf]]
- [[Esquisse d'un Programme]]
- [[Higher-dimensional algebra]]
- [[Induced homomorphism]]
- [[R-algebroid]]
- [[2-Yoneda lemma]]
- [[3-category]]
- [[AB5 category]]
- [[Abstract elementary class]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Size_functor