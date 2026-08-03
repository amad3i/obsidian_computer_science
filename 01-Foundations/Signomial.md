---
title: "Signomial"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Signomial"
wikipedia_categories: ["Functions and mappings", "Mathematical optimization"]
related: ["[[3D projection]]", "[[Algorithmic problems on convex sets]]", "[[Analysis of Boolean functions]]", "[[Antilinear map]]", "[[Backtracking line search]]", "[[Barzilai–Borwein method]]", "[[Basis pursuit]]", "[[Basis pursuit denoising]]", "[[Bauer maximum principle]]", "[[Bayesian efficiency]]"]
---

# Signomial

A signomial is an algebraic function of one or more independent variables.  It is perhaps most easily thought of as an algebraic extension of multivariable polynomials—an extension that permits exponents to be arbitrary real numbers (rather than just non-negative integers) while requiring the independent variables to be strictly positive (so that division by zero and other inappropriate algebraic operations are not encountered).
Formally, a signomial is a function with domain 
  
    
      
        
          
            R
          
          
            0
          
          
            n
          
        
      
    
    
  
 which takes values

  
    
      
        f
        
          x
          
            1
          
        
        ,
        
          x
          
            2
          
        
        ,
        …
        ,
        
          x
          
            n
          
        
        =
        
          ∑
          
            i
            1
          
          
            M
          
        
        
          
            
              c
              
                i
              
            
            
              ∏
              
                j
                1
              
              
                n
              
            
            
              x
              
                j
              
              
                
                  a
                  
                    i
                    j
                  
                
              
            
          
        
      
    
    
  

where the coefficients 
  
    
      
        
          c
          
            i
          
        
      
    
    
  
 and the exponents 
  
    
      
        
          a
          
            i
            j
          
        
      
    
    
  
 are real numbers.  Signomials are closed under addition, subtraction, multiplication, and scaling.
If we restrict all 
  
    
      
        
          c
          
            i
          
        
      
    
    
  
 to be positive, then the function f is a posynomial. Consequently, each signomial is either a posynomial, the negative of a posynomial, or the difference of two posynomials.  If, in addition, all exponents 
  
    
      
        
          a
          
            i
            j
          
        
      
    
    
  
 are  non-negative integers, then the signomial becomes a polynomial whose domain is the positive orthant.
For example, 

  
    
      
        f
        
          x
          
            1
          
        
        ,
        
          x
          
            2
          
        
        ,
        
          x
          
            3
          
        
        =
        2.7
        
          x
          
            1
          
          
            2
          
        
        
          x
          
            2
          
          
            1
            
              /
            
            3
          
        
        
          x
          
            3
          
          
            0.7
          
        
        2
        
          x
          
            1
          
          
            4
          
        
        
          x
          
            3
          
          
            2
            
              /
            
            5
          
        
      
    
    
  

is a signomial. 
The term "signomial" was introduced by Richard J. Duffin and Elmor L. Peterson in their seminal joint work on general algebraic optimization—published in the late 1960s and early 1970s.  A recent introductory exposition involves optimization problems.  Nonlinear optimization problems with constraints and/or objectives defined by signomials are harder to solve than those defined by only posynomials, because (unlike posynomials) signomials cannot necessarily be made convex by applying a logarithmic change of variables. Nevertheless, signomial optimization problems often provide a much more accurate mathematical representation of real-world nonlinear optimization problems.

## Related

- [[3D projection]]
- [[Algorithmic problems on convex sets]]
- [[Analysis of Boolean functions]]
- [[Antilinear map]]
- [[Backtracking line search]]
- [[Barzilai–Borwein method]]
- [[Basis pursuit]]
- [[Basis pursuit denoising]]
- [[Bauer maximum principle]]
- [[Bayesian efficiency]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Signomial