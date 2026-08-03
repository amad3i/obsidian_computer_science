---
title: "Buzen's algorithm"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Buzen's_algorithm"
wikipedia_categories: ["Queueing theory", "Statistical algorithms"]
related: ["[[Adversarial queueing network]]", "[[Arrival theorem]]", "[[Backpressure routing]]", "[[Balance equation]]", "[[Bartlett's theorem]]", "[[BCMP network]]", "[[Beneš method]]", "[[Birth–death process]]", "[[Burke's theorem]]", "[[Cumulative flow diagram]]"]
---

# Buzen's algorithm

In queueing theory, a discipline within the mathematical theory of probability, Buzen's algorithm (or  convolution algorithm) is an algorithm for calculating the normalization constant G(N) in the Gordon–Newell theorem. This method was first proposed by Jeffrey P. Buzen in his 1971 PhD dissertation and subsequently published in a refereed journal in 1973. Computing G(N) is required to compute the stationary probability distribution of a closed queueing network.
Performing a naïve computation of the normalizing constant requires enumeration of all states. For a closed network with N circulating customers and M service facilities, G(N) is the sum of 
  
    
      
        
          
            
              
              
              
                
                  N
                  M
                  1
                
                
                  M
                  1
                
              
              
              
            
          
        
      
    
    
  
 individual terms, with each term consisting of M  factors raised to powers whose sum is N.  Buzen's algorithm computes G(N) using only NM multiplications and NM additions.  This dramatic improvement  opened the door to applying the Gordon-Newell theorem to models of real world computer systems as well as flexible manufacturing systems and other cases where bottlenecks and queues can form within networks of inter-connected service facilities. The values of G(1), G(2) ... G(N -1), which can be used to calculate other important quantities of interest, are computed as by-products of the algorithm.

## Related

- [[Adversarial queueing network]]
- [[Arrival theorem]]
- [[Backpressure routing]]
- [[Balance equation]]
- [[Bartlett's theorem]]
- [[BCMP network]]
- [[Beneš method]]
- [[Birth–death process]]
- [[Burke's theorem]]
- [[Cumulative flow diagram]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Buzen's_algorithm