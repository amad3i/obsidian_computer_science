---
title: "Write–read conflict"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Write–read_conflict"
wikipedia_categories: ["Data management", "Transaction processing"]
related: ["[[Atomicity (database systems)]]", "[[Big data]]", "[[Big memory]]", "[[Commit (data management)]]", "[[Commitment ordering]]", "[[Concurrency control]]", "[[Consistency (database systems)]]", "[[Data preservation]]", "[[Database transaction schedule]]", "[[Distributed concurrency control]]"]
---

# Write–read conflict

In computer science, in the field of databases, write–read conflict (also known as reading uncommitted data and dirty read), is a computational anomaly associated with interleaved execution of transactions. Specifically, a write–read conflict occurs when "a transaction requests to write an entity, for which an unclosed transaction has already made a read request."
Given a schedule S

  
    
      
        S
        
          
            
              
                
                  T
                  1
                
                
                  T
                  2
                
              
              
                
                  R
                  A
                
                
              
              
                
                  W
                  A
                
                
              
              
                
                
                  R
                  A
                
              
              
                
                
                  W
                  A
                
              
              
                
                
                  R
                  B
                
              
              
                
                
                  W
                  B
                
              
              
                
                
                  C
                  o
                  m
                  .
                
              
              
                
                  R
                  B
                
                
              
              
                
                  W
                  B
                
                
              
              
                
                  C
                  o
                  m
                  .
                
                
              
            
          
        
      
    
    
  

T2 could read a database object A, modified by T1 which hasn't committed. This is a dirty or inconsistent read.
T1 may write some value into A which makes the database inconsistent. It is possible that interleaved execution can expose this inconsistency and lead to an inconsistent final database state, violating ACID rules.
Strict 2PL overcomes this inconsistency by locking T2 out from performing a Read/Write on A. Note however that Strict 2PL can have a number of drawbacks, such as the possibility of deadlocks.

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

- Wikipedia: https://en.wikipedia.org/wiki/Write–read_conflict