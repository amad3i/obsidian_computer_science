---
title: "Hypercube (communication pattern)"
tags: ["cs", "hpc-parallel", "intermediate"]
domain: HPC & Parallel
level: intermediate
source: "https://en.wikipedia.org/wiki/Hypercube_(communication_pattern)"
wikipedia_categories: ["Parallel computing"]
related: ["[[ABIT BP6]]", "[[Advanced Synchronization Facility]]", "[[Aiyara cluster]]", "[[Alewife (multiprocessor)]]", "[[Algorithmic skeleton]]", "[[All nearest smaller values]]", "[[All-to-all (parallel pattern)]]", "[[AMD Instinct]]", "[[Amorphous computing]]", "[[Apache Samza]]"]
---

# Hypercube (communication pattern)

d
      
    
    
  
-dimensional hypercube is a network topology for parallel computers with 
  
    
      
        
          2
          
            d
          
        
      
    
    
  
 processing elements. The topology allows for an efficient implementation of some basic communication primitives such as Broadcast, All-Reduce, and Prefix sum. The processing elements are numbered 
  
    
      
        0
      
    
    
  
 through 
  
    
      
        
          2
          
            d
          
        
        1
      
    
    
  
. Each processing element is adjacent to processing elements whose numbers differ in one and only one bit. The algorithms described in this page utilize this structure efficiently.

## Related

- [[ABIT BP6]]
- [[Advanced Synchronization Facility]]
- [[Aiyara cluster]]
- [[Alewife (multiprocessor)]]
- [[Algorithmic skeleton]]
- [[All nearest smaller values]]
- [[All-to-all (parallel pattern)]]
- [[AMD Instinct]]
- [[Amorphous computing]]
- [[Apache Samza]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Hypercube_(communication_pattern)