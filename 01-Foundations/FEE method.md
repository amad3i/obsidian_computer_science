---
title: "FEE method"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/FEE_method"
wikipedia_categories: ["Computer arithmetic algorithms", "Numerical analysis", "Pi algorithms"]
related: ["[[2Sum]]", "[[Abramowitz and Stegun]]", "[[Adaptive step size]]", "[[Adjoint state method]]", "[[Affine arithmetic]]", "[[Applied element method]]", "[[Approximation]]", "[[Approximation error]]", "[[Approximation theory]]", "[[Arc-length method]]"]
---

# FEE method

In mathematics, the FEE method, or fast E-function evaluation method, is the method of fast summation of series of a special form. It was constructed in 1990 by Ekaterina Karatsuba and is so-named because it makes fast computations of the Siegel E-functions possible, in particular of 
  
    
      
        
          e
          
            x
          
        
      
    
    
  
.
A class of functions, which are "similar to the exponential function," was given the name "E-functions" by Carl Ludwig Siegel. Among these functions are such special functions as the hypergeometric function, cylinder, spherical functions and so on.
Using the FEE, it is possible to prove the following theorem:
Theorem: Let 
  
    
      
        y
        f
        x
      
    
    
  
 be an elementary transcendental function, that is the exponential function, or a 
trigonometric function, or an elementary algebraic function, or their superposition, or their inverse, or a superposition of the inverses. Then

  
    
      
        
          s
          
            f
          
        
        n
        =
        O
        M
        n
        
          
            2
          
        
         
        n
        .
        
      
    
    
  

Here 
  
    
      
        
          s
          
            f
          
        
        n
      
    
    
  
 is the complexity of computation (bit) of the function 
  
    
      
        f
        x
      
    
    
  
 with accuracy up to 
  
    
      
        n
      
    
    
  
 digits, 
  
    
      
        M
        n
      
    
    
  
 is the complexity of multiplication of two 
  
    
      
        n
      
    
    
  
-digit integers.
The algorithms based on the method FEE include the algorithms for fast calculation of any elementary transcendental function for any value of the argument, the classical constants e,  
  
    
      
        π
        ,
      
    
    
  
 the Euler constant 
  
    
      
        γ
        ,
      
    
    
  
 the Catalan and the Apéry constants, such higher transcendental functions as the Euler gamma function and its derivatives, the hypergeometric, spherical, cylinder (including the Bessel) functions and some other functions for
algebraic values of the argument and parameters, the Riemann zeta function for integer values of the argument and the Hurwitz zeta function for integer argument and algebraic values of the parameter, and also such special integrals as the integral of probability, the Fresnel integrals, the integral exponential function, the trigonometric integrals, and some other integrals for algebraic values of the argument with the complexity bound which is close to the optimal one, namely

  
    
      
        
          s
          
            f
          
        
        n
        =
        O
        M
        n
        
          
            2
          
        
         
        n
        .
        
      
    
    
  

The FEE makes it possible to calculate fast the values of the functions from the class of higher transcendental functions, certain special integrals of mathematical physics and such classical constants as Euler's, Catalan's and Apéry's constants. An additional advantage of the method FEE is the possibility of parallelizing the algorithms based on the FEE.

## Related

- [[2Sum]]
- [[Abramowitz and Stegun]]
- [[Adaptive step size]]
- [[Adjoint state method]]
- [[Affine arithmetic]]
- [[Applied element method]]
- [[Approximation]]
- [[Approximation error]]
- [[Approximation theory]]
- [[Arc-length method]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/FEE_method