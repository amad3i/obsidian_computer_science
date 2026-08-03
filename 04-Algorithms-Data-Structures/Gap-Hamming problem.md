---
title: "Gap-Hamming problem"
tags: ["cs", "algorithms-data-structures", "advanced"]
domain: Algorithms & Data Structures
level: advanced
source: "https://en.wikipedia.org/wiki/Gap-Hamming_problem"
wikipedia_categories: ["Computational complexity theory", "Quantum complexity theory"]
related: ["[[Bernstein–Vazirani algorithm]]", "[[Claw finding problem]]", "[[Communication complexity]]", "[[Hamiltonian complexity]]", "[[Quantum complexity theory]]", "[[Aanderaa–Karp–Rosenberg conjecture]]", "[[Advice (complexity)]]", "[[Analysis of algorithms]]", "[[Approximation algorithm]]", "[[Asymptotic computational complexity]]"]
---

# Gap-Hamming problem

In communication complexity, the gap-Hamming problem asks, if Alice and Bob are each given a (potentially different) string, what is the minimal number of bits that they need to exchange in order for Alice to approximately compute the Hamming distance between their strings. The solution to the problem roughly states that, if Alice and Bob are each given a string, then any communication protocol used to compute the Hamming distance between their strings does (asymptotically) no better than Bob sending his whole string to Alice. More specifically, if Alice and Bob are each given 
  
    
      
        n
      
    
    
  
-bit strings, there exists no communication protocol that lets Alice compute the hamming distance between their strings to within 
  
    
      
        ±
        
          
            n
          
        
      
    
    
  
 using less than 
  
    
      
        Ω
        n
      
    
    
  
 bits.
The gap-Hamming problem has applications to proving lower bounds for many streaming algorithms, including moment frequency estimation and entropy estimation.

## Related

- [[Bernstein–Vazirani algorithm]]
- [[Claw finding problem]]
- [[Communication complexity]]
- [[Hamiltonian complexity]]
- [[Quantum complexity theory]]
- [[Aanderaa–Karp–Rosenberg conjecture]]
- [[Advice (complexity)]]
- [[Analysis of algorithms]]
- [[Approximation algorithm]]
- [[Asymptotic computational complexity]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Gap-Hamming_problem