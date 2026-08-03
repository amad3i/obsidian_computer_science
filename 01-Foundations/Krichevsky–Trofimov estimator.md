---
title: "Krichevsky–Trofimov estimator"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Krichevsky–Trofimov_estimator"
wikipedia_categories: ["Data compression", "Information theory", "Probability stubs"]
related: ["[[Entropy (information theory)]]", "[[Error exponent]]", "[[Grammar-based code]]", "[[Information projection]]", "[[Information theory]]", "[[Kolmogorov complexity]]", "[[Modulo-N code]]", "[[Nyquist–Shannon sampling theorem]]", "[[Rate–distortion theory]]", "[[Redundancy (information theory)]]"]
---

# Krichevsky–Trofimov estimator

In information theory, given an unknown stationary source π with alphabet A and a sample w from π, the Krichevsky–Trofimov (KT) estimator produces an estimate pi(w) of the probability of each symbol i ∈ A. This estimator is optimal in the sense that it minimizes the worst-case regret asymptotically.
For a binary alphabet and a string w with m zeroes and n ones, the KT estimator pi(w) is defined as:

  
    
      
        
          
            
              
                
                  p
                  
                    0
                  
                
                w
              
              
                
                
                  
                    
                      m
                      1
                      
                        /
                      
                      2
                    
                    
                      m
                      n
                      1
                    
                  
                
                ,
              
            
            
              
                
                  p
                  
                    1
                  
                
                w
              
              
                
                
                  
                    
                      n
                      1
                      
                        /
                      
                      2
                    
                    
                      m
                      n
                      1
                    
                  
                
                .
              
            
          
        
      
    
    
  

This corresponds to the posterior mean of a Beta-Bernoulli posterior distribution with prior 
  
    
      
        1
        
          /
        
        2
      
    
    
  
.
For the general case the estimate is made using a Dirichlet-Categorical distribution.

## Related

- [[Entropy (information theory)]]
- [[Error exponent]]
- [[Grammar-based code]]
- [[Information projection]]
- [[Information theory]]
- [[Kolmogorov complexity]]
- [[Modulo-N code]]
- [[Nyquist–Shannon sampling theorem]]
- [[Rate–distortion theory]]
- [[Redundancy (information theory)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Krichevsky–Trofimov_estimator