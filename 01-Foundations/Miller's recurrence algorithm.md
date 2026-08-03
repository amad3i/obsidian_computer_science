---
title: "Miller's recurrence algorithm"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Miller's_recurrence_algorithm"
wikipedia_categories: ["Algorithms", "Numerical analysis"]
related: ["[[Least-squares spectral analysis]]", "[[Predictor–corrector method]]", "[[Unrestricted algorithm]]", "[[2Sum]]", "[[Abramowitz and Stegun]]", "[[Adaptive algorithm]]", "[[Adaptive step size]]", "[[Adjoint state method]]", "[[Affine arithmetic]]", "[[Algorism]]"]
---

# Miller's recurrence algorithm

Miller's recurrence algorithm is a procedure for the backward calculation of a rapidly decreasing solution of a three-term recurrence relation developed by J. C. P. Miller. It was originally developed to compute tables of the modified Bessel function but also applies to Bessel functions of the first kind and has other applications such as computation of the coefficients of  Chebyshev expansions of other special functions.
Many families of special functions satisfy a recurrence relation that relates the values of the functions of different orders with common argument 
  
    
      
        x
      
    
    
  
.
The modified Bessel functions of the first kind 
  
    
      
        
          I
          
            n
          
        
        x
      
    
    
  
 satisfy the recurrence relation

  
    
      
        
          I
          
            n
            1
          
        
        x
        =
        
          
            
              2
              n
            
            x
          
        
        
          I
          
            n
          
        
        x
        +
        
          I
          
            n
            1
          
        
        x
      
    
    
  
.
However, the modified Bessel functions of the second kind 
  
    
      
        
          K
          
            n
          
        
        x
      
    
    
  
 also satisfy the same recurrence relation

  
    
      
        
          K
          
            n
            1
          
        
        x
        =
        
          
            
              2
              n
            
            x
          
        
        
          K
          
            n
          
        
        x
        +
        
          K
          
            n
            1
          
        
        x
      
    
    
  
.
The first solution decreases rapidly with 
  
    
      
        n
      
    
    
  
.  The second solution increases rapidly with 
  
    
      
        n
      
    
    
  
.  Miller's algorithm provides a numerically stable procedure to obtain the decreasing solution.
To compute the terms of a recurrence 
  
    
      
        
          a
          
            0
          
        
      
    
    
  
 through 
  
    
      
        
          a
          
            N
          
        
      
    
    
  
 according to Miller's algorithm, one first chooses a value 
  
    
      
        M
      
    
    
  
 much larger than 
  
    
      
        N
      
    
    
  
 and computes a trial solution taking initial condition 
  
    
      
        
          a
          
            M
          
        
      
    
    
  
 to an arbitrary non-zero value (such as 1) and taking 
  
    
      
        
          a
          
            M
            1
          
        
      
    
    
  
 and later terms to be zero.  Then the recurrence relation is used to successively compute trial values for 
  
    
      
        
          a
          
            M
            1
          
        
      
    
    
  
, 
  
    
      
        
          a
          
            M
            2
          
        
      
    
    
  
 down to 
  
    
      
        
          a
          
            0
          
        
      
    
    
  
. Noting that a second sequence obtained from the trial sequence by multiplication by a constant normalizing factor will still satisfy the same recurrence relation, one can then apply a separate normalizing relationship to determine the normalizing factor that yields the actual solution.
In the example of the modified Bessel functions, a suitable normalizing relation is a summation involving the even terms of the recurrence: 

  
    
      
        
          I
          
            0
          
        
        x
        +
        2
        
          ∑
          
            m
            1
          
          
            ∞
          
        
        −
        1
        
          
            m
          
        
        
          I
          
            2
            m
          
        
        x
        =
        1
      
    
    
  

where the infinite summation becomes finite due to the approximation that 
  
    
      
        
          a
          
            M
            1
          
        
      
    
    
  
 and later terms are zero.
Finally, it is confirmed that the approximation error of the procedure is acceptable by repeating the procedure with a second choice of 
  
    
      
        M
      
    
    
  
 larger than the initial choice and confirming that the second set of results for 
  
    
      
        
          a
          
            0
          
        
      
    
    
  
 through 
  
    
      
        
          a
          
            N
          
        
      
    
    
  
 agree within the first set within the desired tolerance. Note that to obtain this agreement, the value of 
  
    
      
        M
      
    
    
  
 must be large enough such that the term 
  
    
      
        
          a
          
            M
          
        
      
    
    
  
 is small compared to the desired tolerance.
In contrast to Miller's algorithm, attempts to apply the recurrence relation in the forward direction starting from known values of 
  
    
      
        
          I
          
            0
          
        
        x
      
    
    
  
 and 
  
    
      
        
          I
          
            1
          
        
        x
      
    
    
  
 obtained by other methods will fail as rounding errors introduce components of the rapidly increasing solution.
Olver and Gautschi analyses the error propagation of the algorithm in detail.
For Bessel functions of the first kind, the equivalent recurrence relation and normalizing relationship are:

  
    
      
        
          J
          
            n
            1
          
        
        x
        =
        
          
            
              2
              n
            
            x
          
        
        
          J
          
            n
          
        
        x
        −
        
          J
          
            n
            1
          
        
        x
      
    
    
  

  
    
      
        
          J
          
            0
          
        
        x
        +
        2
        
          ∑
          
            m
            1
          
          
            ∞
          
        
        
          J
          
            2
            m
          
        
        x
        =
        1
      
    
    
  
.
The algorithm is particularly efficient in applications that require the values of the Bessel functions for all orders 
  
    
      
        0
        ⋯
        N
      
    
    
  
 for each value of 
  
    
      
        x
      
    
    
  
 compared to direct independent computations of 
  
    
      
        N
        1
      
    
    
  
 separate functions.

## Related

- [[Least-squares spectral analysis]]
- [[Predictor–corrector method]]
- [[Unrestricted algorithm]]
- [[2Sum]]
- [[Abramowitz and Stegun]]
- [[Adaptive algorithm]]
- [[Adaptive step size]]
- [[Adjoint state method]]
- [[Affine arithmetic]]
- [[Algorism]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Miller's_recurrence_algorithm