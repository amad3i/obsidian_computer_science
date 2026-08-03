---
title: "Write–write conflict"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Write–write_conflict"
wikipedia_categories: ["Data management", "Transaction processing"]
related: ["[[Atomicity (database systems)]]", "[[Big data]]", "[[Big memory]]", "[[Commit (data management)]]", "[[Commitment ordering]]", "[[Concurrency control]]", "[[Consistency (database systems)]]", "[[Data preservation]]", "[[Database transaction schedule]]", "[[Distributed concurrency control]]"]
---

# Write–write conflict

In computer science, in the field of databases, write–write conflict, also known as overwriting uncommitted data is a computational anomaly associated with interleaved execution of transactions. Specifically, a write–write conflict occurs when "transaction requests to write an entity for which an unclosed transaction has already made a write request."
Given a schedule S

  
    
      
        S
        
          
            
              
                
                  T
                  1
                
                
                  T
                  2
                
              
              
                
                  W
                  A
                
                
              
              
                
                
                  W
                  B
                
              
              
                
                  W
                  B
                
                
              
              
                
                  C
                  o
                  m
                  .
                
                
              
              
                
                
                  W
                  A
                
              
              
                
                
                  C
                  o
                  m
                  .
                
              
            
          
        
      
    
    
  

note that there is no read in this schedule. The writes are called blind writes.
We have a dirty write.  Any attempts to make this schedule serial would give off two different results (either T1's version of A and B is shown, or T2's version of A and B is shown), and would not be the same as the above schedule.  This schedule would not be serializable.
Strict 2PL overcomes this inconsistency by locking T1 out from B.  Unfortunately, deadlocks are something Strict 2PL does not overcome all the time.

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

- Wikipedia: https://en.wikipedia.org/wiki/Write–write_conflict