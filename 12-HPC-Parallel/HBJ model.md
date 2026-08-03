---
title: "HBJ model"
tags: ["cs", "hpc-parallel", "intermediate"]
domain: HPC & Parallel
level: intermediate
source: "https://en.wikipedia.org/wiki/HBJ_model"
wikipedia_categories: ["Computer science stubs", "Parallel computing"]
related: ["[[Alewife (multiprocessor)]]", "[[Automatic mutual exclusion]]", "[[Cellular multiprocessing]]", "[[Cost efficiency]]", "[[Degree of parallelism]]", "[[Explicit parallelism]]", "[[Implicit parallelism]]", "[[LogP machine]]", "[[Microparallelism]]", "[[Program dependence graph]]"]
---

# HBJ model

In computer science, the Helman-Bader-JaJa model 
 is a concise message-passing model of parallel computing defined with the following parameters:

  
    
      
        p
      
    
    
  
 is number of processors.

  
    
      
        n
      
    
    
  
 is the problem size.

  
    
      
        m
      
    
    
  
 is number of machine words in a packet sent over the network.

  
    
      
        τ
      
    
    
  
 is the latency, or time at which a processor takes to initiate a communication on a network.

  
    
      
        σ
      
    
    
  
 is the bandwidth, or time per machine word at which a processor can inject or receive 
  
    
      
        m
      
    
    
  
 machine words from the network.

  
    
      
        
          T
          
            c
            o
            m
            p
          
        
      
    
    
  
 is the largest computation time expended on a processor.

  
    
      
        
          T
          
            c
            o
            m
            m
          
        
      
    
    
  
 is the time spent in communication on the network.
This model assumes that for any subset of 
  
    
      
        q
      
    
    
  
 processors, a block permutation among the 
  
    
      
        q
      
    
    
  
 processors takes 
  
    
      
        τ
        σ
        m
      
    
    
  
 time, where 
  
    
      
        m
      
    
    
  
 is the size of the largest block.

## Related

- [[Alewife (multiprocessor)]]
- [[Automatic mutual exclusion]]
- [[Cellular multiprocessing]]
- [[Cost efficiency]]
- [[Degree of parallelism]]
- [[Explicit parallelism]]
- [[Implicit parallelism]]
- [[LogP machine]]
- [[Microparallelism]]
- [[Program dependence graph]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/HBJ_model