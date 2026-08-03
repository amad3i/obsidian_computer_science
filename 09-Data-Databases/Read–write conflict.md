---
title: "Read–write conflict"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Read–write_conflict"
wikipedia_categories: ["Data management", "Transaction processing"]
related: ["[[Atomicity (database systems)]]", "[[Big data]]", "[[Big memory]]", "[[Commit (data management)]]", "[[Commitment ordering]]", "[[Concurrency control]]", "[[Consistency (database systems)]]", "[[Data preservation]]", "[[Database transaction schedule]]", "[[Distributed concurrency control]]"]
---

# Read–write conflict

In computer science, in the field of databases, read–write conflict, also known as unrepeatable reads, is a computational anomaly associated with interleaved execution of transactions. Specifically, a read–write conflict occurs when a "transaction requests to read an entity for which an unclosed transaction has already made a write request."
Given a schedule S

  
    
      
        S
        
          
            
              
                
                  T
                  1
                
                
                  T
                  2
                
              
              
                
                  R
                  A
                
                
              
              
                
                
                  R
                  A
                
              
              
                
                
                  W
                  A
                
              
              
                
                
                  C
                  o
                  m
                  .
                
              
              
                
                  R
                  A
                
                
              
              
                
                  W
                  A
                
                
              
              
                
                  C
                  o
                  m
                  .
                
                
              
            
          
        
      
    
    
  

In this example, T1 has read the original value of A, and is waiting for T2 to finish. T2 also reads the original value of A, overwrites A, and commits.
However, when T1 reads from A, it discovers two different versions of A, and T1 would be forced to abort, because T1 would not know what to do. This is an unrepeatable read. This could never occur in a serial schedule, in which each transaction executes in its entirety before another begins. Strict two-phase locking (Strict 2PL) or Serializable Snapshot Isolation (SSI) prevent this conflict.

## Related

- [[Atomicity (database systems)]]
- [[Big data]]
- [[Big memory]]
- [[Commit (data management)]]
- [[Commitment ordering]]
- [[Concurrency control]]
- [[Consistency (database systems)]]
- [[Data preservation]]
- [[Database transaction schedule]]
- [[Distributed concurrency control]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Read–write_conflict