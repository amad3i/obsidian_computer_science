---
title: "Classical shadow"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Classical_shadow"
wikipedia_categories: ["Quantum computing", "Quantum information science", "Quantum information theory", "Quantum measurement"]
related: ["[[Quantum state discrimination]]", "[[Parity measurement]]", "[[Bell's theorem]]", "[[Circuit Layer Operations per Second]]", "[[Cloud-based quantum computing]]", "[[Cross-entropy benchmarking]]", "[[D-Wave Systems]]", "[[Decoherence-free subspaces]]", "[[Elitzur–Vaidman bomb tester]]", "[[Hamiltonian quantum computation]]"]
---

# Classical shadow

In quantum computing, classical shadow is a protocol for predicting expectation values of a quantum state using only a logarithmic number of measurements. Given an unknown state 
  
    
      
        ρ
      
    
    
  
, a tomographically complete set of gates 
  
    
      
        U
      
    
    
  
 (e.g. Clifford gates), a set of 
  
    
      
        M
      
    
    
  
 observables 
  
    
      
        
          O
          
            i
          
        
      
    
    
  
 and a quantum channel 
  
    
      
        
          
            E
          
        
      
    
    
  
 defined by randomly sampling from 
  
    
      
        U
      
    
    
  
, applying it to 
  
    
      
        ρ
      
    
    
  
 and measuring the resulting state, predict the expectation values 
  
    
      
        tr
         
        
          O
          
            i
          
        
        ρ
      
    
    
  
. A list of classical shadows 
  
    
      
        S
      
    
    
  
 is created using 
  
    
      
        ρ
      
    
    
  
, 
  
    
      
        U
      
    
    
  
 and 
  
    
      
        
          
            E
          
        
      
    
    
  
 by running a Shadow generation algorithm. When predicting the properties of 
  
    
      
        ρ
      
    
    
  
, a Median-of-means estimation algorithm is used to deal with the outliers in 
  
    
      
        S
      
    
    
  
. Classical shadow is useful for direct fidelity estimation, entanglement verification, estimating correlation functions, and predicting entanglement entropy.
Recently, researchers have built on classical shadow to devise provably efficient classical machine learning algorithms for a wide range of quantum many-body problems. For example, machine learning models could learn to solve ground states of quantum many-body systems and classify quantum phases of matter.

## Related

- [[Quantum state discrimination]]
- [[Parity measurement]]
- [[Bell's theorem]]
- [[Circuit Layer Operations per Second]]
- [[Cloud-based quantum computing]]
- [[Cross-entropy benchmarking]]
- [[D-Wave Systems]]
- [[Decoherence-free subspaces]]
- [[Elitzur–Vaidman bomb tester]]
- [[Hamiltonian quantum computation]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Classical_shadow