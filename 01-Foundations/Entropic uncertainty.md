---
title: "Entropic uncertainty"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Entropic_uncertainty"
wikipedia_categories: ["Inequalities (mathematics)", "Information theory", "Physical quantities", "Quantum mechanical entropy"]
related: ["[[Fano's inequality]]", "[[Inequalities in information theory]]", "[[Log sum inequality]]", "[[Quantities of information]]", "[[Shearer's inequality]]", "[[Z-channel (information theory)]]", "[[3G MIMO]]", "[[A Mathematical Theory of Communication]]", "[[A Symbolic Analysis of Relay and Switching Circuits]]", "[[Adjusted mutual information]]"]
---

# Entropic uncertainty

In quantum mechanics, information theory, and Fourier analysis, the entropic uncertainty or Hirschman uncertainty is defined as the sum of the temporal and spectral Shannon entropies.  It turns out that Heisenberg's uncertainty principle can be expressed as a lower bound on the sum of these entropies.  This is stronger than the usual statement of the uncertainty principle in terms of the product of standard deviations.
In 1957, Hirschman considered a function f and its Fourier transform g such that

  
    
      
        g
        y
        ≈
        
          ∫
          
            ∞
          
          
            ∞
          
        
        exp
         
        −
        2
        π
        i
        x
        y
        f
        x
        
        d
        x
        ,
        
        f
        x
        ≈
        
          ∫
          
            ∞
          
          
            ∞
          
        
        exp
         
        2
        π
        i
        x
        y
        g
        y
        
        d
        y
         
        ,
      
    
    
  

where the   "≈" indicates convergence in L2, and normalized so that (by Plancherel's theorem),

  
    
      
        
          ∫
          
            ∞
          
          
            ∞
          
        
        
          |
        
        f
        x
        
          
            |
          
          
            2
          
        
        
        d
        x
        
          ∫
          
            ∞
          
          
            ∞
          
        
        
          |
        
        g
        y
        
          
            |
          
          
            2
          
        
        
        d
        y
        1
         
        .
      
    
    
  

He showed that for any such functions the sum of the Shannon entropies is non-negative,

  
    
      
        H
        
          |
        
        f
        
          
            |
          
          
            2
          
        
        +
        H
        
          |
        
        g
        
          
            |
          
          
            2
          
        
        ≡
        
          ∫
          
            ∞
          
          
            ∞
          
        
        
          |
        
        f
        x
        
          
            |
          
          
            2
          
        
         
        
          |
        
        f
        x
        
          
            |
          
          
            2
          
        
        
        d
        x
        
          ∫
          
            ∞
          
          
            ∞
          
        
        
          |
        
        g
        y
        
          
            |
          
          
            2
          
        
         
        
          |
        
        g
        y
        
          
            |
          
          
            2
          
        
        
        d
        y
        ≥
        0.
      
    
    
  

A tighter bound,

was conjectured by Hirschman and Everett, proven in 1975 by W. Beckner and in the same year interpreted as a generalized quantum mechanical uncertainty principle by Białynicki-Birula and Mycielski.
The equality holds in the case of Gaussian distributions.
Note, however, that the above entropic uncertainty function is distinctly different from the quantum Von Neumann entropy represented in phase space.

## Related

- [[Fano's inequality]]
- [[Inequalities in information theory]]
- [[Log sum inequality]]
- [[Quantities of information]]
- [[Shearer's inequality]]
- [[Z-channel (information theory)]]
- [[3G MIMO]]
- [[A Mathematical Theory of Communication]]
- [[A Symbolic Analysis of Relay and Switching Circuits]]
- [[Adjusted mutual information]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Entropic_uncertainty