---
title: "All-to-all (parallel pattern)"
tags: ["cs", "hpc-parallel", "intermediate"]
domain: HPC & Parallel
level: intermediate
source: "https://en.wikipedia.org/wiki/All-to-all_(parallel_pattern)"
wikipedia_categories: ["Parallel computing"]
related: ["[[ABIT BP6]]", "[[Advanced Synchronization Facility]]", "[[Aiyara cluster]]", "[[Alewife (multiprocessor)]]", "[[Algorithmic skeleton]]", "[[All nearest smaller values]]", "[[AMD Instinct]]", "[[Amorphous computing]]", "[[Apache Samza]]", "[[Apache Storm]]"]
---

# All-to-all (parallel pattern)

In parallel computing, all-to-all (also known as index operation or total exchange) is a collective operation, where each processor sends an individual message to every other processor.
Initially, each processor holds p messages of size m each, and the goal is to exchange the i-th message of processor j with the j-th message of processor i.
The number of communication rounds and the overall communication volume are measures to evaluate the quality of an all-to-all algorithm. We consider a single-ported full-duplex machine throughout this article. On such a machine, an all-to-all algorithm requires at least 
  
    
      
        ⌈
        
          
            2
          
        
         
        n
        ⌉
      
    
    
  
 communication rounds. Further a minimum of 
  
    
      
        
          ⌈
          
            m
            n
            1
          
          ⌉
        
      
    
    
  
 units of data is transferred. Optimum for both these measures can not be achieved simultaneously.
Depending on the network topology (fully connected, hypercube, ring), different all-to-all algorithms are required.

## Related

- [[ABIT BP6]]
- [[Advanced Synchronization Facility]]
- [[Aiyara cluster]]
- [[Alewife (multiprocessor)]]
- [[Algorithmic skeleton]]
- [[All nearest smaller values]]
- [[AMD Instinct]]
- [[Amorphous computing]]
- [[Apache Samza]]
- [[Apache Storm]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/All-to-all_(parallel_pattern)