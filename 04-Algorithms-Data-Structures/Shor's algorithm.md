---
title: "Shor's algorithm"
tags: ["cs", "algorithms-data-structures", "core"]
domain: Algorithms & Data Structures
level: core
source: "https://en.wikipedia.org/wiki/Shor's_algorithm"
wikipedia_categories: ["Integer factorization algorithms", "Post-quantum cryptography", "Quantum algorithms"]
related: ["[[Grover's algorithm]]", "[[HHL algorithm]]", "[[Aharonov–Jones–Landau algorithm]]", "[[Amplitude amplification]]", "[[Bernstein–Vazirani algorithm]]", "[[BHT algorithm]]", "[[Boson sampling]]", "[[Continuous-time quantum walk]]", "[[Deutsch–Jozsa algorithm]]", "[[Feynman's algorithm]]"]
---

# Shor's algorithm

Shor's algorithm is a quantum algorithm for finding the prime factors of an integer. It was developed in 1994 by the American mathematician Peter Shor. It is one of the few known quantum algorithms with compelling potential applications and strong evidence of superpolynomial speedup compared to best known classical (non-quantum) algorithms. However, beating classical computers may require quantum computers with millions of qubits due to the overhead caused by quantum error correction.
Shor proposed multiple similar algorithms for solving the factoring problem, the discrete logarithm problem, and the period-finding problem. "Shor's algorithm" usually refers to the factoring algorithm, but may refer to any of the three algorithms. The discrete logarithm algorithm and the factoring algorithm are instances of the period-finding algorithm, and all three are instances of the hidden subgroup problem.
On a quantum computer, to factor an integer 
  
    
      
        N
      
    
    
  
, Shor's algorithm runs in polynomial time, meaning the time taken is polynomial in 
  
    
      
         
        N
      
    
    
  
. It takes quantum gates of order 
  
    
      
        O
        
        
          
            log
             
            N
            
              
                2
              
            
            log
             
             
            N
            (
             
             
             
            N
          
        
      
    
    
  
 using fast multiplication, or even 
  
    
      
        O
        
        
          
            log
             
            N
            
              
                2
              
            
            log
             
             
            N
          
        
      
    
    
  
 using the asymptotically fastest multiplication algorithm currently known due to Harvey and van der Hoeven, thus demonstrating that the integer factorization problem is in complexity class BQP. Shor's algorithm is asymptotically faster than the most scalable classical factoring algorithm, the general number field sieve, which works in sub-exponential time: 
  
    
      
        O
        
        
          
            e
            
              1.9
              log
               
              N
              
                
                  1
                  
                    /
                  
                  3
                
              
              log
               
               
              N
              
                
                  2
                  
                    /
                  
                  3
                
              
            
          
        
      
    
    
  
.

== Feasibility and implications ==

Assuming a quantum computer with a sufficient number of qubits could operate without succumbing to quantum noise and other quantum-decoherence phenomena, then Shor's algorithm could be used to break public-key cryptography schemes, such as

The RSA scheme
The finite-field Diffie–Hellman key exchange
The elliptic-curve Diffie–Hellman key exchange
RSA can be broken if factoring large integers is computationally feasible. As far as is known, this is not possible using classical (non-quantum) computers; no classical algorithm is known that can factor integers in polynomial time. However, Shor's algorithm shows that factoring integers can be done with a polynomial complexity circuit on an ideal quantum computer. Thus, it might be feasible to defeat RSA by constructing a large enough quantum computer. This was a powerful motivator for the design and construction of quantum computers, and for the study of new quantum-computer algorithms. It has also facilitated research on new cryptosystems that are secure from quantum computers, collectively called post-quantum cryptography (PQC).

=== Physical implementation ===
As of 2026, the high error rates of quantum computers and limited number of physical qubits available for quantum error correction, laboratory demonstrations of Shor's algorithm obtain correct results in only a fraction of attempts, and have only succeeded with small semiprimes.
In 2001, Shor's algorithm was demonstrated by a group at IBM, who factored 
  
    
      
        15
      
    
    
  
 into 
  
    
      
        3
        5
      
    
    
  
, using an NMR implementation of a quantum computer with seven qubits. After IBM's implementation, two independent groups implemented Shor's algorithm using photonic qubits. In 2012, the factorization of 
  
    
      
        15
      
    
    
  
 was performed with solid-state qubits. Later, in 2012, the factorization of 
  
    
      
        21
      
    
    
  
 was achieved. In 2016, the factorization of 
  
    
      
        15
      
    
    
  
 was performed again using trapped-ion qubits. However, none of these demonstrations fulfill the requirements of Shor’s algorithm: they compile the circuit using prior knowledge of the solution, and some have even oversimplified the algorithm in a way that makes it equivalent to coin flipping.

== Algorithm ==
The problem that we are trying to solve is: given an odd composite number 
  
    
      
        N
      
    
    
  
, find its integer factors.
To achieve this, Shor's algorithm consists of two parts:

A classical reduction of the factoring problem to the problem of order-finding. This reduction is similar to that used for other factoring algorithms, such as the quadratic sieve.
A quantum algorithm to solve the order-finding problem.

=== Classical reduction ===
A complete factoring algorithm is possible if we're able to efficiently factor arbitrary 
  
    
      
        N
      
    
    
  
 into just two integers 
  
    
      
        p
      
    
    
  
 and 
  
    
      
        q
      
    
    
  
 greater than 1, since if either 
  
    
      
        p
      
    
    
  
 or 
  
    
      
        q
      
    
    
  
 are not prime, then the factoring algorithm can in turn be run on those until only primes remain.
A basic observation is that, using Euclid's algorithm, we can always compute the GCD between two integers efficiently. In particular, this means we can check efficiently whether 
  
    
      
        N
      
    
    
  
 is even, in which case 2 is trivially a factor. Let us thus assume that 
  
    
      
        N
      
    
    
  
 is odd for the remainder of this discussion. Afterwards, we can use efficient classical algorithms to check whether 
  
    
      
        N
      
    
    
  
 is a prime power. For prime powers, efficient classical factorization algorithms exist, hence the rest of the quantum algorithm may assume that 
  
    
      
        N
      
    
    
  
 is not a prime power.
If those easy cases do not produce a nontrivial factor of 
  
    
      
        N
      
    
    
  
, the algorithm proceeds to handle the remaining case. We pick a random integer 
  
    
      
        2
        ≤
        a
        N
        
          .
        
      
    
    
  
 A possible nontrivial divisor of 
  
    
      
        N
      
    
    
  
 can be found by computing 
  
    
      
        gcd
        a
        ,
        N
      
    
    
  
, which can be done classically and efficiently using the Euclidean algorithm. If this produces a nontrivial factor (meaning 
  
    
      
        gcd
        a
        ,
        N
        ≠
        1
      
    
    
  
), the algorithm is finished, and the other nontrivial factor is 
  
    
      
        N
        
          /
        
        gcd
        a
        ,
        N
      
    
    
  
. If a nontrivial factor was not identified, then this means that 
  
    
      
        N
      
    
    
  
 and the choi

*(note truncated for size; full article at the source link below)*

## Related

- [[Grover's algorithm]]
- [[HHL algorithm]]
- [[Aharonov–Jones–Landau algorithm]]
- [[Amplitude amplification]]
- [[Bernstein–Vazirani algorithm]]
- [[BHT algorithm]]
- [[Boson sampling]]
- [[Continuous-time quantum walk]]
- [[Deutsch–Jozsa algorithm]]
- [[Feynman's algorithm]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Shor's_algorithm