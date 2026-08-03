---
title: "Parallel computation thesis"
tags: ["cs", "theory-of-computation", "intermediate"]
domain: Theory of Computation
level: intermediate
source: "https://en.wikipedia.org/wiki/Parallel_computation_thesis"
wikipedia_categories: ["Parallel computing", "Theory of computation"]
related: ["[[ABIT BP6]]", "[[Ackermann function]]", "[[Admissible numbering]]", "[[Advanced Synchronization Facility]]", "[[Aiyara cluster]]", "[[Alewife (multiprocessor)]]", "[[Algorithmic skeleton]]", "[[All nearest smaller values]]", "[[All-to-all (parallel pattern)]]", "[[AMD Instinct]]"]
---

# Parallel computation thesis

In computational complexity theory, the parallel computation thesis is a hypothesis which states that the time used by a (reasonable) parallel machine is polynomially related to the space used by a sequential machine.  The parallel computation thesis was set forth by Chandra and Stockmeyer in 1976.
In other words, for a computational model which allows computations to branch and run in parallel without bound, a formal language which is decidable under the model using no more than 
  
    
      
        t
        n
      
    
    
  
 steps for inputs of length n is decidable by a non-branching machine using no more than 
  
    
      
        t
        n
        
          
            k
          
        
      
    
    
  
 units of storage for some constant k.  Similarly, if a machine in the unbranching model decides a language using no more than 
  
    
      
        s
        n
      
    
    
  
 storage, a machine in the parallel model can decide the language in no more than 
  
    
      
        s
        n
        
          
            k
          
        
      
    
    
  
 steps for some constant k.
The parallel computation thesis is not a rigorous formal statement, as it does not clearly define what constitutes an acceptable parallel model.  A parallel machine must be sufficiently powerful to emulate the sequential machine in time polynomially related to the sequential space; compare Turing machine, non-deterministic Turing machine, and alternating Turing machine.  N. Blum (1983) introduced a model for which the thesis does not hold.
However, the model allows 
  
    
      
        
          2
          
            
              2
              
                O
                T
                n
                )
              
            
          
        
      
    
    
  
 parallel threads of computation after 
  
    
      
        T
        n
      
    
    
  
 steps.  (See Big O notation.)  Parberry (1986) suggested a more "reasonable" bound would be 
  
    
      
        
          2
          
            O
            T
            n
            )
          
        
      
    
    
  
 or 
  
    
      
        
          2
          
            T
            n
            
              
                O
                1
              
            
          
        
      
    
    
  
, in defense of the thesis.
Goldschlager (1982) proposed a model which is sufficiently universal to emulate all "reasonable" parallel models. In this model, the thesis is provably true.
Chandra and Stockmeyer originally formalized and proved results related to the thesis for deterministic and alternating Turing machines, which is where the thesis originated.

## Related

- [[ABIT BP6]]
- [[Ackermann function]]
- [[Admissible numbering]]
- [[Advanced Synchronization Facility]]
- [[Aiyara cluster]]
- [[Alewife (multiprocessor)]]
- [[Algorithmic skeleton]]
- [[All nearest smaller values]]
- [[All-to-all (parallel pattern)]]
- [[AMD Instinct]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Parallel_computation_thesis