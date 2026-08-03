---
title: "Safety and liveness properties"
tags: ["cs", "theory-of-computation", "advanced"]
domain: Theory of Computation
level: advanced
source: "https://en.wikipedia.org/wiki/Safety_and_liveness_properties"
wikipedia_categories: ["Concurrent computing", "Model checking", "Theoretical computer science"]
related: ["[[Abstract model checking]]", "[[Actor model]]", "[[Algorithm]]", "[[Algorithm engineering]]", "[[Algorithmic logic]]", "[[Algorithmic technique]]", "[[Algorithmic transparency]]", "[[Alternating timed automaton]]", "[[Analysis of Boolean functions]]", "[[Automated reasoning]]"]
---

# Safety and liveness properties

Properties of an execution of a computer program—particularly for concurrent and distributed systems—have long been formulated by giving safety properties ("bad things don't happen") and liveness properties ("good things do happen"). 
A program is totally correct with respect to a precondition 
  
    
      
        P
      
    
    
  
 and postcondition 
  
    
      
        Q
      
    
    
  
 if any execution started in a state satisfying 
  
    
      
        P
      
    
    
  
 terminates in a state satisfying 
  
    
      
        Q
      
    
    
  
. Total correctness is a conjunction of a safety property and a liveness property:

The safety property prohibits these "bad things": executions that start in a state satisfying 
  
    
      
        P
      
    
    
  
 and terminate in a final state that does not satisfy 
  
    
      
        Q
      
    
    
  
. For a program 
  
    
      
        C
      
    
    
  
, this safety property is usually written using the Hoare triple 
  
    
      
        P
        C
        Q
      
    
    
  
.
The liveness property, the "good thing", is that execution that starts in a state satisfying 
  
    
      
        P
      
    
    
  
 terminates.
Note that a bad thing is discrete, since it happens at a particular place during execution.
A "good thing" need not be discrete, but the liveness property of termination is discrete.
Formal definitions that were ultimately proposed for safety properties and liveness properties demonstrated that this decomposition is not only intuitively appealing but is also complete: all properties of an execution are a conjunction of safety and liveness properties. Moreover, undertaking the decomposition can be helpful, because the formal definitions enable a proof that different methods must be used for verifying safety properties versus for verifying liveness properties.

## Related

- [[Abstract model checking]]
- [[Actor model]]
- [[Algorithm]]
- [[Algorithm engineering]]
- [[Algorithmic logic]]
- [[Algorithmic technique]]
- [[Algorithmic transparency]]
- [[Alternating timed automaton]]
- [[Analysis of Boolean functions]]
- [[Automated reasoning]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Safety_and_liveness_properties