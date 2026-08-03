---
title: "Majorization"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Majorization"
wikipedia_categories: ["Linear algebra", "Order theory"]
related: ["[[3D projection]]", "[[Absolutely convex set]]", "[[Adjugate matrix]]", "[[Affine space]]", "[[Amitsur–Levitzki theorem]]", "[[Angles between flats]]", "[[Annihilating polynomial]]", "[[Antilinear map]]", "[[Antiunitary operator]]", "[[Asymmetric norm]]"]
---

# Majorization

In mathematics, majorization is a preorder on vectors of real numbers. For two such vectors, 
  
    
      
        
          x
        
        ,
         
        
          y
        
        ∈
        
          
            R
          
          
            n
          
        
      
    
    
  
, we say that 
  
    
      
        
          x
        
      
    
    
  
 weakly majorizes (or dominates) 
  
    
      
        
          y
        
      
    
    
  
 from below, commonly denoted 
  
    
      
        
          x
        
        
          ≻
          
            w
          
        
        
          y
        
        ,
      
    
    
  
 when

  
    
      
        
          ∑
          
            i
            1
          
          
            k
          
        
        
          x
          
            i
          
          
            ↓
          
        
        ≥
        
          ∑
          
            i
            1
          
          
            k
          
        
        
          y
          
            i
          
          
            ↓
          
        
      
    
    
  
 for all 
  
    
      
        k
        1
        ,
        
        …
        ,
        
        n
      
    
    
  
,
where 
  
    
      
        
          x
          
            i
          
          
            ↓
          
        
      
    
    
  
 denotes the 
  
    
      
        i
      
    
    
  
th largest entry of 
  
    
      
        
          x
        
      
    
    
  
. If 
  
    
      
        
          x
        
        ,
        
          y
        
      
    
    
  
 further satisfy 
  
    
      
        
          ∑
          
            i
            1
          
          
            n
          
        
        
          x
          
            i
          
        
        
          ∑
          
            i
            1
          
          
            n
          
        
        
          y
          
            i
          
        
      
    
    
  
, we say that 
  
    
      
        
          x
        
      
    
    
  
 majorizes (or dominates) 
  
    
      
        
          y
        
      
    
    
  
, commonly denoted 
  
    
      
        
          x
        
        ≻
        
          y
        
      
    
    
  
. 
Both weak majorization and majorization are partial orders for vectors whose entries are non-decreasing, but only a preorder for general vectors, since majorization is agnostic to the ordering of the entries in vectors, e.g., the statement 
  
    
      
        1
        ,
        2
        ≺
        0
        ,
        3
      
    
    
  
 is simply equivalent to 
  
    
      
        2
        ,
        1
        ≺
        3
        ,
        0
      
    
    
  
.
Specifically, 
  
    
      
        
          x
        
        ≻
        
          y
        
        ∧
        
          y
        
        ≻
        
          x
        
      
    
    
  
 if and only if 
  
    
      
        
          x
        
        ,
        
          y
        
      
    
    
  
 are permutations of each other. Similarly for 
  
    
      
        
          ≻
          
            w
          
        
      
    
    
  
.
Majorizing also sometimes refers to entrywise ordering, e.g. the real-valued function f majorizes the real-valued function g when 
  
    
      
        f
        x
        ≥
        g
        x
      
    
    
  
 for all 
  
    
      
        x
      
    
    
  
 in the domain, or other technical definitions, such as majorizing measures in probability theory.

## Related

- [[3D projection]]
- [[Absolutely convex set]]
- [[Adjugate matrix]]
- [[Affine space]]
- [[Amitsur–Levitzki theorem]]
- [[Angles between flats]]
- [[Annihilating polynomial]]
- [[Antilinear map]]
- [[Antiunitary operator]]
- [[Asymmetric norm]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Majorization