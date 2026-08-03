---
title: "Communication complexity"
tags: ["cs", "foundations-math", "advanced"]
domain: Foundations & Math
level: advanced
source: "https://en.wikipedia.org/wiki/Communication_complexity"
wikipedia_categories: ["Computational complexity theory", "Information theory", "Quantum complexity theory"]
related: ["[[Bernstein–Vazirani algorithm]]", "[[Claw finding problem]]", "[[Effective complexity]]", "[[Gap-Hamming problem]]", "[[Glossary of quantum computing]]", "[[Hamiltonian complexity]]", "[[Kolmogorov complexity]]", "[[Lempel–Ziv complexity]]", "[[Logical depth]]", "[[Quantum capacity]]"]
---

# Communication complexity

In theoretical computer science, communication complexity studies the amount of communication required to solve a problem when the input to the problem is distributed among two or more parties. The study of communication complexity was first introduced by Andrew Yao in 1979, while studying the problem of computation distributed among several machines.
The problem is usually stated as follows: two parties (traditionally called Alice and Bob) each receive a (potentially different) 
  
    
      
        n
      
    
    
  
-bit string 
  
    
      
        x
      
    
    
  
 and 
  
    
      
        y
      
    
    
  
. The goal is for Alice to compute the value of a certain function, 
  
    
      
        f
        x
        ,
        y
      
    
    
  
, that depends on both 
  
    
      
        x
      
    
    
  
 and 
  
    
      
        y
      
    
    
  
, with the least amount of communication between them.
While Alice and Bob can always succeed by having Bob send his whole 
  
    
      
        n
      
    
    
  
-bit string to Alice (who then computes the function 
  
    
      
        f
      
    
    
  
), the idea here is to find clever ways of calculating 
  
    
      
        f
      
    
    
  
 with fewer than 
  
    
      
        n
      
    
    
  
 bits of communication. Note that, unlike in computational complexity theory, communication complexity is not concerned with the amount of computation performed by Alice or Bob, or the size of the memory used, as we generally assume nothing about the computational power of either Alice or Bob.
This abstract problem with two parties (called two-party communication complexity), and its general form with more than two parties, is relevant in many contexts. In VLSI circuit design, for example, one seeks to minimize energy used by decreasing the amount of electric signals passed between the different components during a distributed computation. The problem is also relevant in the study of data structures and in the optimization of computer networks. For surveys of the field, see the textbooks by Rao & Yehudayoff (2020) and Kushilevitz & Nisan (2006).

## Related

- [[Bernstein–Vazirani algorithm]]
- [[Claw finding problem]]
- [[Effective complexity]]
- [[Gap-Hamming problem]]
- [[Glossary of quantum computing]]
- [[Hamiltonian complexity]]
- [[Kolmogorov complexity]]
- [[Lempel–Ziv complexity]]
- [[Logical depth]]
- [[Quantum capacity]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Communication_complexity