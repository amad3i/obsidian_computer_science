---
title: "LogP machine"
tags: ["cs", "hpc-parallel", "intermediate"]
domain: HPC & Parallel
level: intermediate
source: "https://en.wikipedia.org/wiki/LogP_machine"
wikipedia_categories: ["Computer science stubs", "Educational abstract machines", "Models of computation", "Parallel computing", "Theoretical computer science"]
related: ["[[Krivine machine]]", "[[Random-access Turing machine]]", "[[Turing machine]]", "[[Alewife (multiprocessor)]]", "[[Automatic mutual exclusion]]", "[[Bulk synchronous parallel]]", "[[Cellular multiprocessing]]", "[[Cost efficiency]]", "[[Degree of parallelism]]", "[[Description number]]"]
---

# LogP machine

The LogP machine is a model for parallel computation.
It aims at being more practical than the PRAM model while still allowing for easy analysis of computation.
The name is not related to the mathematical logarithmic function:  Instead, the machine is described by the four parameters 
  
    
      
        L
      
    
    
  
, 
  
    
      
        o
      
    
    
  
, 
  
    
      
        g
      
    
    
  
 and 
  
    
      
        P
      
    
    
  
.
The LogP machine consists of arbitrarily many processing units with distributed memory.
The processing units are connected through an abstract communication medium which allows point-to-point communication. This model is pair-wise synchronous and overall asynchronous.
The machine is described by the four parameters:

  
    
      
        L
      
    
    
  
, the latency of the communication medium.

  
    
      
        o
      
    
    
  
, the overhead of sending and receiving a message.

  
    
      
        g
      
    
    
  
, the gap required between two send/receive operations. A more common interpretation of this quantity is as the inverse of the bandwidth of a processor-processor communication channel.

  
    
      
        P
      
    
    
  
, the number of processing units.
Each local operation on each machine takes the same time ('unit time').  This time is called a processor cycle. The units of the parameters 
  
    
      
        L
      
    
    
  
, 
  
    
      
        o
      
    
    
  
 and 
  
    
      
        g
      
    
    
  
 are measured in multiples of processor cycles.

## Related

- [[Krivine machine]]
- [[Random-access Turing machine]]
- [[Turing machine]]
- [[Alewife (multiprocessor)]]
- [[Automatic mutual exclusion]]
- [[Bulk synchronous parallel]]
- [[Cellular multiprocessing]]
- [[Cost efficiency]]
- [[Degree of parallelism]]
- [[Description number]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/LogP_machine