---
title: "Singular control"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Singular_control"
wikipedia_categories: ["Control theory", "Optimal control"]
related: ["[[Bellman pseudospectral method]]", "[[Chebyshev pseudospectral method]]", "[[Flat pseudospectral method]]", "[[Legendre pseudospectral method]]", "[[Microgrid]]", "[[Optimal projection equations]]", "[[Pseudospectral knotting method]]", "[[Ross' π lemma]]", "[[Ross–Fahroo lemma]]", "[[Ross–Fahroo pseudospectral method]]"]
---

# Singular control

In optimal control, problems of singular control are problems that are difficult to solve because a straightforward application of Pontryagin's minimum principle fails to yield a complete solution.  Only a few such problems have been solved, such as Merton's portfolio problem in financial economics or trajectory optimization in aeronautics. A more technical explanation follows.
The most common difficulty in applying Pontryagin's principle arises when the Hamiltonian depends linearly on the control 
  
    
      
        u
      
    
    
  
, i.e., is of the form: 
  
    
      
        H
        u
        =
        ϕ
        x
        ,
        λ
        ,
        t
        u
        ⋯
      
    
    
  
 and the control is restricted to being between an upper and a lower bound: 
  
    
      
        a
        ≤
        u
        t
        ≤
        b
      
    
    
  
.  To minimize 
  
    
      
        H
        u
      
    
    
  
, we need to make 
  
    
      
        u
      
    
    
  
 as big or as small as possible, depending on the sign of 
  
    
      
        ϕ
        x
        ,
        λ
        ,
        t
      
    
    
  
, specifically:

  
    
      
        u
        t
        =
        
          
            
              
                
                  b
                  ,
                
                
                  ϕ
                  x
                  ,
                  λ
                  ,
                  t
                  <
                  0
                
              
              
                
                  ?
                  ,
                
                
                  ϕ
                  x
                  ,
                  λ
                  ,
                  t
                  =
                  0
                
              
              
                
                  a
                  ,
                
                
                  ϕ
                  x
                  ,
                  λ
                  ,
                  t
                  >
                  0.
                
              
            
            
          
        
      
    
    
  

If 
  
    
      
        ϕ
      
    
    
  
 is positive at some times, negative at others and is only zero instantaneously, then the solution is straightforward and is a bang-bang control that switches from 
  
    
      
        b
      
    
    
  
 to 
  
    
      
        a
      
    
    
  
 at times when 
  
    
      
        ϕ
      
    
    
  
 switches from negative to positive.  
The case when 
  
    
      
        ϕ
      
    
    
  
 remains at zero for a finite length of time 
  
    
      
        
          t
          
            1
          
        
        ≤
        t
        ≤
        
          t
          
            2
          
        
      
    
    
  
 is called the singular control case.  Between 
  
    
      
        
          t
          
            1
          
        
      
    
    
  
 and 
  
    
      
        
          t
          
            2
          
        
      
    
    
  
 the maximization of the Hamiltonian with respect to 
  
    
      
        u
      
    
    
  
 gives us no useful information and the solution in that time interval is going to have to be found from other considerations.  One approach is to repeatedly differentiate 
  
    
      
        ∂
        H
        
          /
        
        ∂
        u
      
    
    
  
 with respect to time until the control u again explicitly appears, though this is not guaranteed to happen eventually.  One can then set that expression to zero and solve for u.  This amounts to saying that between 
  
    
      
        
          t
          
            1
          
        
      
    
    
  
 and 
  
    
      
        
          t
          
            2
          
        
      
    
    
  
 the control 
  
    
      
        u
      
    
    
  
 is determined by the requirement that the singularity condition continues to hold.  The resulting so-called singular arc, if it is optimal, will satisfy the Kelley condition:

  
    
      
        −
        1
        
          
            k
          
        
        
          
            ∂
            
              ∂
              u
            
          
        
        
          
            
              
                
                  
                    
                      d
                      
                        d
                        t
                      
                    
                  
                
              
              
                2
                k
              
            
            
              H
              
                u
              
            
          
        
        ≥
        0
        ,
        
        k
        0
        ,
        1
        ,
        ⋯
      
    
    
  

Others refer to this condition as the generalized Legendre–Clebsch condition.
The term bang-singular control refers to a control that has a bang-bang portion as well as a singular portion.

## Related

- [[Bellman pseudospectral method]]
- [[Chebyshev pseudospectral method]]
- [[Flat pseudospectral method]]
- [[Legendre pseudospectral method]]
- [[Microgrid]]
- [[Optimal projection equations]]
- [[Pseudospectral knotting method]]
- [[Ross' π lemma]]
- [[Ross–Fahroo lemma]]
- [[Ross–Fahroo pseudospectral method]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Singular_control