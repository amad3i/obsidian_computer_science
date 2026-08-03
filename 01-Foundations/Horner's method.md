---
title: "Horner's method"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Horner's_method"
wikipedia_categories: ["Computer algebra", "Numerical analysis", "Polynomials", "Science and technology of the Song dynasty"]
related: ["[[Bernstein polynomial]]", "[[Factorization of polynomials over finite fields]]", "[[Remez algorithm]]", "[[Symbolic-numeric computation]]", "[[Wilkinson's polynomial]]", "[[2Sum]]", "[[Abramowitz and Stegun]]", "[[Adaptive step size]]", "[[Adjoint state method]]", "[[Affine arithmetic]]"]
---

# Horner's method

In mathematics and computer science, Horner's method (or Horner's scheme) is an algorithm for polynomial evaluation. It is named after William George Horner, although it is much older, attributed by Horner to Joseph-Louis Lagrange, and was discovered hundreds of years earlier by Chinese and Persian mathematicians. After the introduction of computers, this algorithm became fundamental for computing efficiently with polynomials.
The algorithm is based on Horner's rule, in which a polynomial is written in nested form:

  
    
      
        
          
            
              
              
                
                  a
                  
                    0
                  
                
                
                  a
                  
                    1
                  
                
                x
                
                  a
                  
                    2
                  
                
                
                  x
                  
                    2
                  
                
                
                  a
                  
                    3
                  
                
                
                  x
                  
                    3
                  
                
                ⋯
                
                  a
                  
                    n
                  
                
                
                  x
                  
                    n
                  
                
              
            
            
              
                

                
              
              
                
                  a
                  
                    0
                  
                
                x
                
                  
                  
                
                
                  a
                  
                    1
                  
                
                x
                
                  
                  
                
                
                  a
                  
                    2
                  
                
                x
                
                  
                  
                
                
                  a
                  
                    3
                  
                
                ⋯
                x
                
                  a
                  
                    n
                    1
                  
                
                x
                
                
                  a
                  
                    n
                  
                
                ⋯
                
                  
                  
                
                
                  
                  
                
                
                  
                  
                
                .
              
            
          
        
      
    
    
  

This allows the evaluation of a polynomial of degree n with only 
  
    
      
        n
      
    
    
  
 multiplications and 
  
    
      
        n
      
    
    
  
 additions. This is optimal, as it is impossible to evaluate polynomials of degree n with fewer arithmetic operations when both x and the coefficients a0, ..., an are given as input.
Horner's method and Horner–Ruffini method also refers to a method for approximating the roots of polynomials, described by Horner in 1819. It is a variant of the Newton–Raphson method made more efficient for hand calculation by application of Horner's rule. It was widely used until computers came into general use around 1970.

## Related

- [[Bernstein polynomial]]
- [[Factorization of polynomials over finite fields]]
- [[Remez algorithm]]
- [[Symbolic-numeric computation]]
- [[Wilkinson's polynomial]]
- [[2Sum]]
- [[Abramowitz and Stegun]]
- [[Adaptive step size]]
- [[Adjoint state method]]
- [[Affine arithmetic]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Horner's_method