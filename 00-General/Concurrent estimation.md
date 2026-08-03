---
title: "Concurrent estimation"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Concurrent_estimation"
wikipedia_categories: ["Control theory", "Events (computing)"]
related: ["[[4D-RCS Reference Model Architecture]]", "[[Ackermann's formula]]", "[[Active disturbance rejection control]]", "[[Adaptive control]]", "[[Advanced process control]]", "[[Affect control theory]]", "[[American Automatic Control Council]]", "[[Anticausal system]]", "[[Artstein's theorem]]", "[[Asymptotic gain model]]"]
---

# Concurrent estimation

In discrete event simulation concurrent estimation  is a technique used to estimate the effect of alternate parameter settings on a discrete event system. For example, from observation of a (computer simulated) telecommunications system with a specified buffer size 
  
    
      
        
          B
          
            0
          
        
      
    
    
  
, one estimates what the performance would be if the buffer size had been set to the alternate values 
  
    
      
        
          B
          
            1
          
        
        ,
        …
        ,
        
          B
          
            n
          
        
      
    
    
  
. Effectively the technique generates (during a single simulation run) 
  
    
      
        n
      
    
    
  
 alternative histories for the system state variables, which have the same probability of occurring as the main simulated state path; this results in a computational saving as compared to running 
  
    
      
        n
      
    
    
  
 additional simulations, one for each alternative parameter value.
The technique was developed by Cassandras, Strickland and Panayiotou.

## Related

- [[4D-RCS Reference Model Architecture]]
- [[Ackermann's formula]]
- [[Active disturbance rejection control]]
- [[Adaptive control]]
- [[Advanced process control]]
- [[Affect control theory]]
- [[American Automatic Control Council]]
- [[Anticausal system]]
- [[Artstein's theorem]]
- [[Asymptotic gain model]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Concurrent_estimation