---
title: "Kempner series"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Kempner_series"
wikipedia_categories: ["Base-dependent integer sequences", "Numerical analysis", "Series (mathematics)"]
related: ["[[Method of dominant balance]]", "[[2Sum]]", "[[Abramowitz and Stegun]]", "[[Adaptive step size]]", "[[Adjoint state method]]", "[[Affine arithmetic]]", "[[Applied element method]]", "[[Approximation]]", "[[Approximation error]]", "[[Approximation theory]]"]
---

# Kempner series

The Kempner series is a modification of the harmonic series, formed by omitting all terms whose denominator expressed in base 10 contains the digit 9. That is, it is the sum

  
    
      
        
          
            
              
                
                  
                    
                      
                        ∑
                      
                    
                  
                
              
              
              
                
                  ∑
                
                ′
              
            
            
              n
              1
            
            
              ∞
            
          
        
        
          
            1
            n
          
        
      
    
    
  

where the prime indicates that n takes only values whose decimal expansion has no nines. The series was first studied by A. J. Kempner in 1914. The series is counterintuitive because, unlike the harmonic series, it converges. Kempner showed the sum of this series is less than 90. Baillie showed that, rounded to 20 decimals, the actual sum is 22.92067661926415034816
(sequence A082838 in the OEIS).
Heuristically, this series converges because most large integers contain every digit. For example, a random 100-digit integer is very likely to contain at least one '9', causing it to be excluded from the above sum.
Schmelzer and Baillie found an efficient algorithm for the more general problem of any omitted string of digits. For example, the sum of ⁠1/n⁠ where n has no instances of "42" is about 228.44630415923081325415. Another example: the sum of ⁠1/n⁠ where n has no occurrence of the digit string "314159" is about 2302582.33386378260789202376. (All values are rounded in the last decimal place.)

## Related

- [[Method of dominant balance]]
- [[2Sum]]
- [[Abramowitz and Stegun]]
- [[Adaptive step size]]
- [[Adjoint state method]]
- [[Affine arithmetic]]
- [[Applied element method]]
- [[Approximation]]
- [[Approximation error]]
- [[Approximation theory]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Kempner_series