---
title: "Error exponent"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Error_exponent"
wikipedia_categories: ["Data compression", "Information theory"]
related: ["[[Entropy (information theory)]]", "[[Grammar-based code]]", "[[Information theory]]", "[[Kolmogorov complexity]]", "[[Krichevsky–Trofimov estimator]]", "[[Modulo-N code]]", "[[Nyquist–Shannon sampling theorem]]", "[[Rate–distortion theory]]", "[[Redundancy (information theory)]]", "[[Shannon's source coding theorem]]"]
---

# Error exponent

In information theory, the error exponent of a channel code or source code over the block length of the code is the rate at which the error probability decays exponentially with the block length of the code. Formally, it is defined as the limiting ratio of the negative logarithm of the error probability to the block length of the code for large block lengths.  For example, if the probability of error 
  
    
      
        
          P
          
            
              e
              r
              r
              o
              r
            
          
        
      
    
    
  
 of a decoder drops as 
  
    
      
        
          e
          
            n
            α
          
        
      
    
    
  
, where 
  
    
      
        n
      
    
    
  
 is the block length, the error exponent is 
  
    
      
        α
      
    
    
  
. In this example, 
  
    
      
        
          
            
              ln
               
              
                P
                
                  
                    e
                    r
                    r
                    o
                    r
                  
                
              
            
            n
          
        
      
    
    
  
 approaches 
  
    
      
        α
      
    
    
  
 for large 
  
    
      
        n
      
    
    
  
. Many of the information-theoretic theorems are of asymptotic nature, for example, the channel coding theorem states that for any rate less than the channel capacity, the probability of the error of the channel code can be made to go to zero as the block length goes to infinity. In practical situations, there are limitations to the delay of the communication and the block length must be finite. Therefore, it is important to study how the probability of error drops as the block length go to infinity.
Classical channel-coding exponents include achievability bounds, such as random-coding exponents, and converse bounds. For discrete memoryless channels, Suguru Arimoto gave a converse bound showing exponential decay of the correct decoding probability for rates above capacity.

## Related

- [[Entropy (information theory)]]
- [[Grammar-based code]]
- [[Information theory]]
- [[Kolmogorov complexity]]
- [[Krichevsky–Trofimov estimator]]
- [[Modulo-N code]]
- [[Nyquist–Shannon sampling theorem]]
- [[Rate–distortion theory]]
- [[Redundancy (information theory)]]
- [[Shannon's source coding theorem]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Error_exponent