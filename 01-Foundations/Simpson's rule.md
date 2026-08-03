---
title: "Simpson's rule"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Simpson's_rule"
wikipedia_categories: ["Integral calculus", "Numerical analysis", "Numerical integration"]
related: ["[[Boole's rule]]", "[[Local linearization method]]", "[[Numerical integration]]", "[[Nyström method]]", "[[2Sum]]", "[[Abramowitz and Stegun]]", "[[Adaptive step size]]", "[[Adjoint state method]]", "[[Affine arithmetic]]", "[[Applied element method]]"]
---

# Simpson's rule

In numerical integration, Simpson's rules are several approximations for definite integrals, named after Thomas Simpson (1710–1761).
The most basic of these rules, called Simpson's 1/3 rule, or just Simpson's rule, reads

  
    
      
        
          ∫
          
            a
          
          
            b
          
        
        f
        x
        
        d
        x
        ≈
        
          
            
              b
              a
            
            6
          
        
        
          
            f
            a
            +
            4
            f
            
              
                
                  
                    a
                    b
                  
                  2
                
              
            
            f
            b
          
        
        .
      
    
    
  

In German and some other languages, it is named after Johannes Kepler, who derived it in 1615 after seeing it used for wine barrels (barrel rule, Keplersche Fassregel). The approximate equality in the rule becomes exact if f is a polynomial up to and including 3rd degree.
If the 1/3 rule is applied to n equal subdivisions of the integration range [a, b], one obtains the composite Simpson's 1/3 rule. Points inside the integration range are given alternating weights 4/3 and 2/3.
Simpson's 3/8 rule, also called Simpson's second rule, requires one more function evaluation inside the integration range and gives lower error bounds, but does not improve the order of the error.
If the 3/8 rule is applied to n equal subdivisions of the integration range [a, b], one obtains the composite Simpson's 3/8 rule.
Simpson's 1/3 and 3/8 rules are two special cases of closed Newton–Cotes formulas.
In naval architecture and ship stability estimation, there also exists Simpson's third rule, which has no special importance in general numerical analysis, see Simpson's rules (ship stability).

## Related

- [[Boole's rule]]
- [[Local linearization method]]
- [[Numerical integration]]
- [[Nyström method]]
- [[2Sum]]
- [[Abramowitz and Stegun]]
- [[Adaptive step size]]
- [[Adjoint state method]]
- [[Affine arithmetic]]
- [[Applied element method]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Simpson's_rule