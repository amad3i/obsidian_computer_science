---
title: "Learning with errors"
tags: ["cs", "security-cryptography", "intermediate"]
domain: Security & Cryptography
level: intermediate
source: "https://en.wikipedia.org/wiki/Learning_with_errors"
wikipedia_categories: ["Post-quantum cryptography"]
related: ["[[Grover's algorithm]]", "[[Ideal lattice]]", "[[Lattice reduction]]", "[[Post-quantum cryptography]]", "[[Quantum Threat]]", "[[Ring learning with errors key exchange]]", "[[Shor's algorithm]]", "[[Short integer solution problem]]", "[[Supersingular isogeny key exchange]]"]
---

# Learning with errors

In cryptography, learning with errors (LWE) is a mathematical problem that is widely used to create secure encryption algorithms. It is based on the idea of representing secret information as a set of equations with errors. In other words, LWE is a way to hide the value of a secret by introducing noise to it. In more technical terms, it refers to the computational problem of inferring a linear 
  
    
      
        n
      
    
    
  
-ary function 
  
    
      
        f
      
    
    
  
 over a finite ring from given samples 
  
    
      
        
          y
          
            i
          
        
        f
        
          
            x
          
          
            i
          
        
      
    
    
  
 some of which may be erroneous. The LWE problem is conjectured to be hard to solve, and thus to be useful in cryptography.
More precisely, the LWE problem is defined as follows. Let 
  
    
      
        
          
            Z
          
          
            q
          
        
      
    
    
  
 denote the ring of integers modulo 
  
    
      
        q
      
    
    
  
 and let

  
    
      
        
          
            Z
          
          
            q
          
          
            n
          
        
      
    
    
  
 denote the set of 
  
    
      
        n
      
    
    
  
-vectors over 
  
    
      
        
          
            Z
          
          
            q
          
        
      
    
    
  
. There exists a certain unknown linear function 
  
    
      
        f
        :
        
          
            Z
          
          
            q
          
          
            n
          
        
        →
        
          
            Z
          
          
            q
          
        
      
    
    
  
, and the input to the LWE problem is a sample of pairs 
  
    
      
        
          x
        
        ,
        y
      
    
    
  
, where 
  
    
      
        
          x
        
        ∈
        
          
            Z
          
          
            q
          
          
            n
          
        
      
    
    
  
 and 
  
    
      
        y
        ∈
        
          
            Z
          
          
            q
          
        
      
    
    
  
, so that with high probability 
  
    
      
        y
        f
        
          x
        
      
    
    
  
. Furthermore, the deviation from the equality is according to some known noise model. The problem calls for finding the function 
  
    
      
        f
      
    
    
  
, or some close approximation thereof, with high probability.
The LWE problem was introduced by Oded Regev in 2005 (who won the 2018 Gödel Prize for this work); it is a generalization of the parity learning problem. Regev showed that the LWE problem is as hard to solve as several worst-case lattice problems. Subsequently, the LWE problem has been used as a hardness assumption to create public-key cryptosystems, such as the ring learning with errors key exchange by Peikert.

## Related

- [[Grover's algorithm]]
- [[Ideal lattice]]
- [[Lattice reduction]]
- [[Post-quantum cryptography]]
- [[Quantum Threat]]
- [[Ring learning with errors key exchange]]
- [[Shor's algorithm]]
- [[Short integer solution problem]]
- [[Supersingular isogeny key exchange]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Learning_with_errors