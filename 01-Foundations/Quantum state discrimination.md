---
title: "Quantum state discrimination"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Quantum_state_discrimination"
wikipedia_categories: ["Quantum computing", "Quantum information science", "Quantum information theory", "Quantum measurement"]
related: ["[[Classical shadow]]", "[[Parity measurement]]", "[[Bell's theorem]]", "[[Circuit Layer Operations per Second]]", "[[Cloud-based quantum computing]]", "[[Cross-entropy benchmarking]]", "[[D-Wave Systems]]", "[[Decoherence-free subspaces]]", "[[Elitzur–Vaidman bomb tester]]", "[[Hamiltonian quantum computation]]"]
---

# Quantum state discrimination

The term quantum state discrimination collectively refers to quantum-informatics techniques, with the help of which, by performing a small number of measurements on a physical system, its specific quantum state can be identified . And this is provided that the set of states in which the system can be is known in advance, and we only need to determine which one it is. This assumption distinguishes such techniques from quantum tomography, which does not impose additional requirements on the state of the system, but requires many times more measurements.
If the set of states in which the investigated system can be is represented by orthogonal vectors, the situation is particularly simple. To unambiguously determine the state of the system, it is enough to perform a quantum measurement in the basis formed by these vectors. The given quantum state can then be flawlessly identified from the measured value. Moreover, it can be easily shown that if the individual states are not orthogonal to each other, there is no way to tell them apart with certainty. Therefore, in such a case, it is always necessary to take into account the possibility of incorrect or inconclusive determination of the state of the system. However, there are techniques that try to alleviate this deficiency. With exceptions, these techniques can be divided into two groups, namely those based on error minimization and then those that allow the state to be determined unambiguously in exchange for lower efficiency.
The first group of techniques is based on the works of Carl W. Helstrom from the 60s and 70s of the 20th century  and in its basic form consists in the implementation of projective quantum measurement, where the measurement operators are projective representations. The second group is based on the conclusions of a scientific article published by ID Ivanovich in 1987  and requires the use of generalized measurement, in which the elements of the POVM set are taken as measurement operators. Both groups of techniques are currently the subject of active, primarily theoretical, research, and apart from a number of special cases, there is no general solution that would allow choosing measurement operators in the form of expressible analytical formula.
More precisely, in its standard formulation, the problem involves performing some POVM 
  
    
      
        
          E
          
            i
          
        
        
          
            i
          
        
      
    
    
  
 on a given unknown state 
  
    
      
        ρ
      
    
    
  
, under the promise that the state received is an element of a collection of states 
  
    
      
        
          σ
          
            i
          
        
        
          
            i
          
        
      
    
    
  
, with 
  
    
      
        
          σ
          
            i
          
        
      
    
    
  
 occurring with probability 
  
    
      
        
          p
          
            i
          
        
      
    
    
  
, that is, 
  
    
      
        ρ
        
          ∑
          
            i
          
        
        
          p
          
            i
          
        
        
          σ
          
            i
          
        
      
    
    
  
. The task is then to find the probability of the POVM 
  
    
      
        
          E
          
            i
          
        
        
          
            i
          
        
      
    
    
  
 correctly guessing which state was received. Since the probability of the POVM returning the 
  
    
      
        i
      
    
    
  
-th outcome when the given state was 
  
    
      
        
          σ
          
            j
          
        
      
    
    
  
 has the form 
  
    
      
        
          Prob
        
        i
        
          |
        
        j
        =
        tr
         
        
          E
          
            i
          
        
        
          σ
          
            j
          
        
      
    
    
  
, it follows that the probability of successfully determining the correct state is 
  
    
      
        
          P
          
            
              s
              u
              c
              c
              e
              s
              s
            
          
        
        
          ∑
          
            i
          
        
        
          p
          
            i
          
        
        tr
         
        
          σ
          
            i
          
        
        
          E
          
            i
          
        
      
    
    
  
.

## Related

- [[Classical shadow]]
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

- Wikipedia: https://en.wikipedia.org/wiki/Quantum_state_discrimination