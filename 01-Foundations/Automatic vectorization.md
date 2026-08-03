---
title: "Automatic vectorization"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Automatic_vectorization"
wikipedia_categories: ["Compiler optimizations", "Distributed computing problems", "Parallel computing", "SIMD computing"]
related: ["[[Automatic parallelization]]", "[[Embarrassingly parallel]]", "[[Expeed]]", "[[Flattening transformation]]", "[[FR-V (microprocessor)]]", "[[Loop unrolling]]", "[[Milbeaut]]", "[[Single instruction, multiple data]]", "[[Single instruction, multiple threads]]", "[[SWAR]]"]
---

# Automatic vectorization

Automatic vectorization, in parallel computing, is a special case of automatic parallelization, where a computer program is converted from a scalar implementation, which processes a single pair of operands at a time, to a vector implementation, which processes one operation on multiple pairs of operands at once. For example, modern conventional computers, including specialized supercomputers, typically have vector operations that simultaneously perform operations such as the following four additions (via SIMD or SPMD hardware):

  
    
      
        
          
            
              
                
                  c
                  
                    1
                  
                
              
              
                
                
                  a
                  
                    1
                  
                
                
                  b
                  
                    1
                  
                
              
            
            
              
                
                  c
                  
                    2
                  
                
              
              
                
                
                  a
                  
                    2
                  
                
                
                  b
                  
                    2
                  
                
              
            
            
              
                
                  c
                  
                    3
                  
                
              
              
                
                
                  a
                  
                    3
                  
                
                
                  b
                  
                    3
                  
                
              
            
            
              
                
                  c
                  
                    4
                  
                
              
              
                
                
                  a
                  
                    4
                  
                
                
                  b
                  
                    4
                  
                
              
            
          
        
      
    
    
  

However, in most programming languages one typically writes loops that sequentially perform additions of many numbers. Here is an example of such a loop, written in C:

A vectorizing compiler transforms such loops into sequences of vector operations. These vector operations perform additions on blocks of elements from the arrays a, b and c. Automatic vectorization is a major research topic in computer science.

## Related

- [[Automatic parallelization]]
- [[Embarrassingly parallel]]
- [[Expeed]]
- [[Flattening transformation]]
- [[FR-V (microprocessor)]]
- [[Loop unrolling]]
- [[Milbeaut]]
- [[Single instruction, multiple data]]
- [[Single instruction, multiple threads]]
- [[SWAR]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Automatic_vectorization