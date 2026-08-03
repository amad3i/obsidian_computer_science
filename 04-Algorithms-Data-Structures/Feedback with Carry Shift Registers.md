---
title: "Feedback with Carry Shift Registers"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Feedback_with_Carry_Shift_Registers"
wikipedia_categories: ["Cryptographic algorithms", "Digital registers", "Pseudorandom number generators", "Stream ciphers"]
related: ["[[Linear-feedback shift register]]", "[[CryptGenRandom]]", "[[Key generator]]", "[[B92 protocol]]", "[[Bach's algorithm]]", "[[BB84]]", "[[Beaufort cipher]]", "[[Block cipher mode of operation]]", "[[CDMF]]", "[[Ciphertext stealing]]"]
---

# Feedback with Carry Shift Registers

In sequence design, a Feedback with Carry Shift Register (or FCSR) is the arithmetic or with carry analog of a linear-feedback shift register (LFSR).  If 
  
    
      
        N
        1
      
    
    
  
 is an integer, then an N-ary FCSR of length 
  
    
      
        r
      
    
    
  
 is a finite state device with a state 
  
    
      
        a
        ;
        z
        =
        
          a
          
            0
          
        
        ,
        
          a
          
            1
          
        
        ,
        …
        ,
        
          a
          
            r
            1
          
        
        ;
        z
      
    
    
  
 consisting of a vector of elements 
  
    
      
        
          a
          
            i
          
        
      
    
    
  
 in 
  
    
      
        0
        ,
        1
        ,
        …
        ,
        N
        1
        =
        S
      
    
    
  
 and an integer 
  
    
      
        z
      
    
    
  
.  The state change operation is determined by a set of coefficients 
  
    
      
        
          q
          
            1
          
        
        ,
        …
        ,
        
          q
          
            n
          
        
      
    
    
  
 and is defined as follows: compute 
  
    
      
        s
        
          q
          
            r
          
        
        
          a
          
            0
          
        
        
          q
          
            r
            1
          
        
        
          a
          
            1
          
        
        ⋯
        
          q
          
            1
          
        
        
          a
          
            r
            1
          
        
        z
      
    
    
  
.  Express s as 
  
    
      
        s
        
          a
          
            r
          
        
        N
        
          z
          ′
        
      
    
    
  
 with 
  
    
      
        
          a
          
            r
          
        
      
    
    
  
 in 
  
    
      
        S
      
    
    
  
.  Then the new state is 
  
    
      
        
          a
          
            1
          
        
        ,
        
          a
          
            2
          
        
        ,
        …
        ,
        
          a
          
            r
          
        
        ;
        
          z
          ′
        
      
    
    
  
.  By iterating the state change an FCSR generates an infinite, eventually periodic sequence of numbers in 
  
    
      
        S
      
    
    
  
.
FCSRs have been used in the design of stream ciphers (such as the F-FCSR generator), in the cryptanalysis of the summation combiner stream cipher (the reason Goresky and Klapper invented them), and in generating pseudorandom numbers for quasi-Monte Carlo (under the name Multiply With Carry (MWC) generator - invented by Couture and L'Ecuyer,) generalizing work of Marsaglia and Zaman.
FCSRs are analyzed using number theory.  Associated with the FCSR is a connection integer 
  
    
      
        q
        
          q
          
            r
          
        
        
          N
          
            r
          
        
        ⋯
        
          q
          
            1
          
        
        
          N
          
            1
          
        
        1
      
    
    
  
.  Associated with the output sequence is the N-adic number 
  
    
      
        a
        
          a
          
            0
          
        
        
          a
          
            1
          
        
        N
        
          a
          
            2
          
        
        
          N
          
            2
          
        
        …
      
    
    
  
 The fundamental theorem of FCSRs says that there is an integer 
  
    
      
        u
      
    
    
  
 so that 
  
    
      
        a
        u
        
          /
        
        q
      
    
    
  
, a rational number.  The output sequence is strictly periodic if and only if 
  
    
      
        u
      
    
    
  
 is between 
  
    
      
        q
      
    
    
  
 and 
  
    
      
        0
      
    
    
  
. It is possible to express u as a simple quadratic polynomial involving the initial state and the qi.
There is also an exponential representation of FCSRs: if 
  
    
      
        g
      
    
    
  
 is the inverse of 
  
    
      
        N
        
          
          mod
          
          q
        
      
    
    
  
, and the output sequence is strictly periodic, then 
  
    
      
        
          a
          
            i
          
        
        (
        A
        
          g
          
            i
          
        
        
          mod
          
            q
          
        
        
          mod
          
            N
          
        
      
    
    
  
, where 
  
    
      
        A
      
    
    
  
 is an integer. It follows that the period is at most the order of N in the multiplicative group of units modulo q. This is maximized when q is prime and N is a primitive element modulo q. In this case, the period is 
  
    
      
        q
        1
      
    
    
  
.  In this case the output sequence is called an l-sequence (for "long sequence").
l-sequences have many excellent statistical properties that make them candidates for use in applications, including near uniform distribution of sub-blocks, ideal arithmetic autocorrelations, and the arithmetic shift and add property.  They are the with-carry analog of m-sequences or maximum length sequences.
There are efficient algorithms for FCSR synthesis.  This is the problem: given a prefix of a sequence, construct a minimal length FCSR that outputs the sequence.  This can be solved with a variant of Mahler and De Weger's lattice based analysis of N-adic numbers when 
  
    
      
        N
        2
      
    
    
  
; by a variant of the Euclidean algorithm when N is prime; and in general by Xu's adaptation of the Berlekamp-Massey algorithm.  If L is the size of the smallest FCSR that outputs the sequence (called the N-adic complexity of the sequence), then all these algorithms require a prefix of length about 
  
    
      
        2
        L
      
    
    
  
 to be successful and have quadratic time complexity.  It follows that, as with LFSRs and linear complexity, any stream cipher whose N-adic complexity is low should not be used for cryptography.
FCSRs and LFSRs are special cases of a very general algebraic construction of sequence generators called Algebraic Feedback Shift Registers (AFSRs) in which the integers are replaced by an arbitrary ring R and N is replaced by an arbitrary non-unit in R.  A general reference on the subject of LFSRs, FCSRs, and AFSRs is the book.

## Related

- [[Linear-feedback shift register]]
- [[CryptGenRandom]]
- [[Key generator]]
- [[B92 protocol]]
- [[Bach's algorithm]]
- [[BB84]]
- [[Beaufort cipher]]
- [[Block cipher mode of operation]]
- [[CDMF]]
- [[Ciphertext stealing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Feedback_with_Carry_Shift_Registers