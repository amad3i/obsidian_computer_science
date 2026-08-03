---
title: "Fritz John conditions"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Fritz_John_conditions"
wikipedia_categories: ["Mathematical optimization"]
related: ["[[Algorithmic problems on convex sets]]", "[[Analysis of Boolean functions]]", "[[Backtracking line search]]", "[[Barzilai–Borwein method]]", "[[Basis pursuit]]", "[[Basis pursuit denoising]]", "[[Bauer maximum principle]]", "[[Bayesian efficiency]]", "[[Bilinear program]]", "[[Binary constraint]]"]
---

# Fritz John conditions

The Fritz John conditions (abbr. FJ conditions), in mathematics, are a necessary condition for a solution in nonlinear programming to be optimal. They are used as lemma in the proof of the Karush–Kuhn–Tucker conditions, but they are relevant on their own.
We consider the following optimization problem:

  
    
      
        
          
            
              
                
                  minimize 
                
              
              
                f
                x
                
              
            
            
              
                
                  subject to: 
                
              
              
                
                  g
                  
                    i
                  
                
                x
                ≤
                0
                ,
                 
                i
                ∈
                
                  
                    1
                    ,
                    …
                    ,
                    m
                  
                
              
            
            
              
              
                
                  h
                  
                    j
                  
                
                x
                =
                0
                ,
                 
                j
                ∈
                
                  
                    m
                    1
                    ,
                    …
                    ,
                    n
                  
                
              
            
          
        
      
    
    
  

where ƒ is the function to be minimized, 
  
    
      
        
          g
          
            i
          
        
      
    
    
  
 the inequality constraints and 
  
    
      
        
          h
          
            j
          
        
      
    
    
  
 the equality constraints, and where, respectively, 
  
    
      
        
          
            I
          
        
      
    
    
  
, 
  
    
      
        
          
            A
          
        
      
    
    
  
 and 
  
    
      
        
          
            E
          
        
      
    
    
  
 are the indices sets of inactive, active and equality constraints and 
  
    
      
        
          x
          
          
        
      
    
    
  
 is an optimal solution of 
  
    
      
        f
      
    
    
  
, then there exists a non-zero vector 
  
    
      
        λ
        [
        
          λ
          
            0
          
        
        ,
        
          λ
          
            1
          
        
        ,
        
          λ
          
            2
          
        
        ,
        …
        ,
        
          λ
          
            n
          
        
      
    
    
  
 such that:

  
    
      
        
          
            
              
                
                  
                    λ
                    
                      0
                    
                  
                  ∇
                  f
                  
                    x
                    
                    
                  
                  +
                  
                    ∑
                    
                      i
                      ∈
                      
                        
                          A
                        
                      
                    
                  
                  
                    λ
                    
                      i
                    
                  
                  ∇
                  
                    g
                    
                      i
                    
                  
                  
                    x
                    
                    
                  
                  +
                  
                    ∑
                    
                      i
                      ∈
                      
                        
                          E
                        
                      
                    
                  
                  
                    λ
                    
                      i
                    
                  
                  ∇
                  
                    h
                    
                      i
                    
                  
                  
                    x
                    
                    
                  
                  =
                  0
                
              
              
                
                  
                    λ
                    
                      i
                    
                  
                  ≥
                  0
                  ,
                   
                  i
                  ∈
                  
                    
                      A
                    
                  
                  ∪
                  0
                
              
              
                
                  ∃
                  i
                  ∈
                  
                    
                      0
                      ,
                      1
                      ,
                      …
                      ,
                      n
                      ∖
                      
                        
                          I
                        
                      
                    
                  
                  
                    
                      
                        λ
                        
                          i
                        
                      
                      ≠
                      0
                    
                  
                
              
            
            
          
        
      
    
    
  

  
    
      
        
          λ
          
            0
          
        
        0
      
    
    
  
 if the 
  
    
      
        ∇
        
          g
          
            i
          
        
        i
        ∈
        
          
            A
          
        
      
    
    
  
 and 
  
    
      
        ∇
        
          h
          
            i
          
        
        i
        ∈
        
          
            E
          
        
      
    
    
  
 are linearly independent or, more generally, when a constraint qualification holds.
Named after Fritz John, these conditions are equivalent to the Karush–Kuhn–Tucker conditions in the case 
  
    
      
        
          λ
          
            0
          
        
        0
      
    
    
  
. When 
  
    
      
        
          λ
          
            0
          
        
        0
      
    
    
  
, the condition is equivalent to the violation of Mangasarian–Fromovitz constraint qualification (MFCQ). In other words, the Fritz John condition is equivalent to the optimality condition KKT or not-MFCQ.

## Related

- [[Algorithmic problems on convex sets]]
- [[Analysis of Boolean functions]]
- [[Backtracking line search]]
- [[Barzilai–Borwein method]]
- [[Basis pursuit]]
- [[Basis pursuit denoising]]
- [[Bauer maximum principle]]
- [[Bayesian efficiency]]
- [[Bilinear program]]
- [[Binary constraint]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Fritz_John_conditions