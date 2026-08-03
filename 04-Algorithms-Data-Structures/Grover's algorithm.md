---
title: "Grover's algorithm"
tags: ["cs", "algorithms-data-structures", "core"]
domain: Algorithms & Data Structures
level: core
source: "https://en.wikipedia.org/wiki/Grover's_algorithm"
wikipedia_categories: ["Post-quantum cryptography", "Quantum algorithms", "Search algorithms"]
related: ["[[Amplitude amplification]]", "[[Shor's algorithm]]", "[[(1+ε)-approximate nearest neighbor search]]", "[[A- search algorithm]]", "[[Aharonov–Jones–Landau algorithm]]", "[[All nearest smaller values]]", "[[Alpha–beta pruning]]", "[[Anytime A-]]", "[[Anytime algorithm]]", "[[B-]]"]
---

# Grover's algorithm

In quantum computing, Grover's algorithm, also known as the quantum search algorithm, is a quantum algorithm for unstructured search that finds with high probability the unique input to a black box function that produces a particular output value, using just 
  
    
      
        O
        
          
            N
          
        
      
    
    
  
 evaluations of the function, where 
  
    
      
        N
      
    
    
  
 is the size of the function's domain. It was devised by an Indian-American computer scientist Lov Grover in 1996.
The analogous problem in classical computation would have a query complexity 
  
    
      
        O
        N
      
    
    
  
 (i.e., the function would have to be evaluated 
  
    
      
        O
        N
      
    
    
  
 times: there is no better approach than trying out all input values one after the other, which, on average, takes 
  
    
      
        N
        
          /
        
        2
      
    
    
  
 steps).
Charles H. Bennett, Ethan Bernstein, Gilles Brassard, and Umesh Vazirani proved that any quantum solution to the problem needs to evaluate the function 
  
    
      
        Ω
        
          
            N
          
        
      
    
    
  
 times, so Grover's algorithm is asymptotically optimal. Since classical algorithms for NP-complete problems require exponentially many steps, and Grover's algorithm provides at most a quadratic speedup over the classical solution for unstructured search, this suggests that Grover's algorithm by itself will not provide polynomial-time solutions for NP-complete problems (as the square root of an exponential function is still an exponential, not a polynomial function).
Unlike other quantum algorithms, which may provide exponential speedup over their classical counterparts, Grover's algorithm provides only a quadratic speedup. However, even quadratic speedup is considerable when 
  
    
      
        N
      
    
    
  
 is large, and Grover's algorithm can be applied to speed up broad classes of algorithms. Grover's algorithm could brute-force a 128-bit symmetric cryptographic key in roughly 264 iterations, or a 256-bit key in roughly 2128 iterations. It may not be the case that Grover's algorithm poses a significantly increased risk to encryption over existing classical algorithms, however.

== Applications and limitations ==
Grover's algorithm, along with variants like amplitude amplification, can be used to speed up a broad range of algorithms. In particular, algorithms for NP-complete problems which contain exhaustive search as a subroutine can be sped up by Grover's algorithm. The current theoretical best algorithm, in terms of worst-case complexity, for 3SAT is one such example. Generic constraint satisfaction problems also see quadratic speedups with Grover. These algorithms do not require that the input be given in the form of an oracle, since Grover's algorithm is being applied with an explicit function, e.g. the function checking that a set of bits satisfies a 3SAT instance. However, it is unclear whether Grover's algorithm could speed up best practical algorithms for these problems.
Grover's algorithm can also give provable speedups for black-box problems in quantum query complexity, including element distinctness and the collision problem (solved with the Brassard–Høyer–Tapp algorithm). In these types of problems, one treats the oracle function f as a database, and the goal is to use the quantum query to this function as few times as possible.

=== Cryptography ===
Grover's algorithm essentially solves the task of function inversion. Roughly speaking, if we have a function 
  
    
      
        y
        f
        x
      
    
    
  
 that can be evaluated on a quantum computer, Grover's algorithm allows us to calculate 
  
    
      
        x
      
    
    
  
 when given 
  
    
      
        y
      
    
    
  
. Consequently, Grover's algorithm gives broad asymptotic speed-ups to many kinds of brute-force attacks on symmetric-key cryptography, including collision attacks and pre-image attacks. However, this may not necessarily be the most efficient algorithm since, for example, the Pollard's rho algorithm is able to find a collision in SHA-2 more efficiently than Grover's algorithm.

=== Limitations ===
Grover's original paper described the algorithm as a database search algorithm, and this description is still common. The database in this analogy is a table of all of the function's outputs, indexed by the corresponding input. However, this database is not represented explicitly. Instead, an oracle is invoked to evaluate an item by its index. Reading a full database item by item and converting it into such a representation may take a lot longer than Grover's search. To account for such effects, Grover's algorithm can be viewed as solving an equation or satisfying a constraint. In such applications, the oracle is a way to check the constraint and is not related to the search algorithm. This separation usually prevents algorithmic optimizations, whereas conventional search algorithms often rely on such optimizations and avoid exhaustive search. Fortunately, fast Grover's oracle implementation is possible for many constraint satisfaction and optimization problems.
The major barrier to instantiating a speedup from Grover's algorithm is that the quadratic speedup achieved is too modest to overcome the large overhead of near-term quantum computers. However, later generations of fault-tolerant quantum computers with better hardware performance may be able to realize these speedups for practical instances of data.

== Problem description ==
As input for Grover's algorithm, suppose we have a function 
  
    
      
        f
        :
        0
        ,
        1
        ,
        …
        ,
        N
        1
        →
        0
        ,
        1
      
    
    
  
. In the "unstructured database" analogy, the domain represent indices to a database, and 
  
    
      
        f
        x
        =
        1
      
    
    
  
 if the data that 
  
    
      
        x
      
    
    
  
 points to satisfies the search criterion. We additionally assume that only one index satisfies 
  
    
      
        f
        x
        =
        1
      
    
    
  
, and we call this index 
  
    
      
        ω
      
    
    
  
. Our goal is to identify 
  
    
      
        ω
      
    
    
  
.
We can access 
  
    
      
        f
      
    
    
  
 with a subroutine (sometimes called an oracle) in the form of a unitary operator 
  
    
      
        
          U
          
            ω
          
        
      
    
    
  
 that acts as follows:

  
    
      
        
          
            
              
                
                  
                    U
                    
                      ω
                    
                  
                  
                    |
                  
                  x
                  ⟩
                  −
                  
                    |
                  
                  x
                  ⟩
                
                
                  
                    for 
                  
                  x
                  ω
                  
                    , that is, 
                  
                  f
                  x
                  =
                  1
                  ,
                
              
              
                
                  
                    U
                    
                      ω
                    
                  
                  
                    |
                  
                  x
                  ⟩
                  
                    |
                  
                  x
                  ⟩
                
                
                  
                    for 
                  
                  x
                  ≠
                  ω
                  
                    , that is, 
                  
                  f
                  x
                  =
                  0.
                
              
            
            
          
        
      
    
    
  

This uses the 
  
    
      
        N
      
    
    
  
-dimensional state space 
  
    
      
        
          
            H
          
        
      
    
    
  
, which is supplied by a register with 
  
    
      
        n
        ⌈
        
          
            2
          
        
         
        N
        ⌉
      
    
    
  
 qubits.
This is often written as

  
    
      
        
          U
          
            ω
          
        
        
          |
        
        x
        ⟩
        (
        1
        
          
            f
            x
          
        
        
          |
        
        x
        ⟩
        .
      
    
    
  

Grover's algorithm outputs 
  
    
      
        ω
      
    
    
  
 with probability at least 
  
    
      
        1
        
          /
        
        2
      
    
    
  
 using 
  
    
      
        O
        
          
            N
          
        
      
    
    
  
 applications of 
  
    
      
        
          U
          
            ω
          
        
      
    
    
  
. This probability can be made arbitrarily large by running Grover's algorithm multiple times. If one runs Grover's algorithm until 
  
    
      
        ω
      
    
    
  
 is found, the expected number of applications is still 
  
    
      
        O
        
          
            N
          
        
      
    
    
  
, since it will only be run twice on average.

=== Alternative oracle definition ===
This section compares the above oracle 
  
    
      
        
          U
          
            ω
          
        
      
    
    
  
 with an oracle 
  
    
      
        
          U
          
            f
          
        
      
    
    
  
.

  
    
      
        
          U
          
            ω
          
        
      
    
    
  
 is different from the standard quantum oracle for a function 
  
    
      
        f
      
    
    
  
. This standard oracle, denoted here as 
  
    
      
        
          U
          
            f
          
        
      
    
    
  
, uses an ancillary qubit system. The operation then represents an inversion (NOT gate) on the main system conditioned by the value of f(x) from the ancillary system:

  
    
      
        
          
            
              
                
                  
                    U
                    
                      f
                    
                  
                  
                    |
                  
                  x
                  ⟩
                  
                    |
                  
                  y
                  ⟩
                  
                    |
                  
                  x
                  ⟩
                  
                    |
                  
                  ¬
                  y
                  ⟩
                
                
                  
                    for 
                  
                  x
                  ω
                  
                    , that is, 
                  
                  f
                  x
                  =
                  1
                  ,
                
              
              
                
                  
                    U
                    
                      f
                    
                  
                  
                    |
                  
                  x
                  ⟩
                  
                    |
                  
                  y
                  ⟩
                  
                    |
                  
                  x
                  ⟩
                  
                    |
                  
                  y
                  ⟩
                
                
                  
                    for 
                  
                  x
                  ≠
                  ω
                  
                    , that is, 
                  
                  f
                  x
                  =
                  0
                  ,
                
              
            
            
          
        
      
    
    
  

or briefly,

  
    
      
        
          U
          
            f
          
        
        
          |
        
        x
        ⟩
        
          |
        
        y
        ⟩
        
          |
        
        x
        ⟩
        
          |
        
        y
        ⊕
        f
        x
        ⟩
        .
      
    
    
  

These oracles are typically realized using uncomputation.
If we are given 
  
    
      
        
          U
          
            f
          
        
      
    
    
  
 as our oracle, then we can also implement 
  
    
      
        
          U
          
            ω
          
        
      
    
    
  
, since 
  
    
      
        
          U
          
            ω
          
        
      
    
    
  
 is 
  
    
      
        
          U
          
            f
          
        
      
    
    
  
 when the ancillary qubit is in the state 
  
    
      
        
          |
        
        ⟩
        
          
            1
            
              2
            
          
        
        
          
          
        
        
          |
        
        0
        ⟩
        
          |
        
        1
        ⟩
        
          
          
        
        H
        
          |
        
        1
        ⟩
      
    
    
  
:

  
    
      
        
          
            
              
                
                  U
                  
                    f
                  
                
                
                  
                  
                
                
                  |
                
                x
                ⟩
                ⊗
                
                  |
                
                ⟩
                
                  
                  
                
              
              
                
                
                  
                    1
                    
                      2
                    
                  
                
                
                  
                    
                      U
                      
                        f
                      
                    
                    
                      |
                    
                    x
                    ⟩
                    
                      |
                    
                    0
                    ⟩
                    
                      U
                      
                        f
                      
                    
                    
                      |
                    
                    x
                    ⟩
                    
                      |
                    
                    1
                    ⟩
                  
                
              
            
            
              
              
                
                
                  
                    1
                    
                      2
                    
                  
                
                
                  
                    
                      |
                    
                    x
                    ⟩
                    
                      |
                    
                    0
                    ⊕
                    f
                    x
                    ⟩
                    
                      |
                    
                    x
                    ⟩
                    
                      |
                    
                    1
                    ⊕
                    f
                    x
                    ⟩
                  
                
              
            
            
              
              
                
                
                  
                    
                      
                        
                          
                            
                              1
                              
                                2
                              
                            
                          
                          
                            
                              
                                |
                              
                              x
                              ⟩
                              
                                |
                              
                              0
                              ⟩
                              
                                |
                              
                              x
                              ⟩
                              
                                |
                              
                              1
                              ⟩
                            
                          
                        
                        
                          
                            if 
                          
                          f
                          x
                          =
                          1
                          ,
                        
                      
                      
                        
                          
                            
                              1
                              
                                2
                              
                            
                          
                          
                            
                              
                                |
                              
                              x
                              ⟩
                              
                                |
                              
                              0
                              ⟩
                              
                                |
                              
                              x
                              ⟩
                              
                                |
                              
                              1
                              ⟩
                            
                          
                        
                        
                          
                            if 
                          
                          f
                          x
                          =
                          0
                        
                      
                    
                    
                  
                
              
            
            
              
              
                
                (
                
                  U
                  
                    ω
                  
                
                
                  |
                
                x
                ⟩
                ⊗
                
                  |
                
                ⟩
              
            
          
        
      
    
    
  

So, Grover's algorithm can be run regardless of which oracle is given. If 
  
    
      
        
          U
          
            f
          
        
      
    
    
  
 is given, then we must maintain an additional qubit in the state 
  
    
      
        
          |
        
        ⟩
      
    
    
  
 and apply 
  
    
      
        
          U
          
            f
          
        
      
    
    
  
 in place of 
  
    
      
        
          U
          
            ω
          
        
      
    
    
  
.

== Algorithm ==

The steps of Grover's algorithm are given as follows:

Initialize the system to the uniform superposition over all states
  
    
      
        
          |
        
        s
        ⟩
        
          
            1
            
              N
            
          
        
        
          ∑
          
            x
            0
          
          
            N
            1
          
        
        
          |
        
        x
        ⟩
        .
      
    
    
  

Perform the following "Grover iteration" 
  
    
      
        r
        N
      
    
    
  
 times:
Apply the operator 
  
    
      
        
          U
          
            ω
          
        
      
    
    
  

Apply the Grover diffusion operator 
  
    
      
        
          U
          
            s
          
        
        2
        
          |
          s
          ⟩
        
        
        
        
          ⟨
          s
          |
        
        I
      
    
    
  

Measure the resulting quantum state in the computational basis.
For the correctly chosen value of 
  
    
      
        r
      
    
    
  
, the output will be 
  
    
      
        
          |
        
        ω
        ⟩
      
    
    
  
 with probability approaching 1 for N ≫ 1. Analysis shows that this eventual value for 
  
    
      
        r
        N
      
    
    
  
 satisfies 
  
    
      
        r
        N
        ≤
        
          
            ⌈
          
        
        
          
            π
            4
          
        
        
          
            N
          
        
        
          
            ⌉
          
        
      
    
    
  
.
Implementing the steps for this algorithm can be done using a number of gates linear in the number of qubits. Thus, the gate complexity of this algorithm is 
  
    
      
        O
        log
         
        N
        r
        N
        )
      
    
    
  
, or 
  
    
      
        O
        log
         
        N
        )
      
    
    
  
 per iteration.

== Geometric proof ==

There is a geometric interpretation of Grover's algorithm, following from the observation that the quantum state of Grover's algorithm stays in a two-dimensional subspace after each step. Consider the plane spanned by 
  
    
      
        
          |
        
        s
        ⟩
      
    
    
  
 and 
  
    
      
        
          |
        
        ω
        ⟩
      
    
    
  
; equivalently, the plane spanned by 
  
    
      
        
          |
        
        ω
        ⟩
      
    
    
  
 and the perpendicular ket 
  
    
      
        
          
            |
          
          
            s
            ′
          
          ⟩
          
            
              1
              
                N
                1
              
            
          
          
            ∑
            
              x
              ≠
              ω
            
          
          
            |
          
          x
          ⟩
        
      
    
    
  
.
Grover's algorithm begins with the initial ket 
  
    
      
        
          |
        
        s
        ⟩
      
    
    
  
, which lies in the subspace. The operator 
  
    
      
        
          U
          
            ω
          
        
      
    
    
  
 is a reflection at the hyperplane orthogonal to 
  
    
      
        
          |
        
        ω
        ⟩
      
    
    
  
 for vectors in the plane spanned by 
  
    
      
        
          |
        
        
          s
          ′
        
        ⟩
      
    
    
  
 and 
  
    
      
        
          |
        
        ω
        ⟩
      
    
    
  
, i.e. it acts as a reflection across 
  
    
      
        
          |
        
        
          s
          ′
        
        ⟩
      
    
    
  
. This can be seen by writing 
  
    
      
        
          U
          
            ω
          
        
      
    
    
  
 in the form of a Householder reflection:

  
    
      
        
          U
          
            ω
          
        
        I
        2
        
          |
        
        ω
        ⟩
        ⟨
        ω
        
          |
        
        .
      
    
    
  

The operator 
  
    
      
        
          U
          
            s
          
        
        2
        
          |
        
        s
        ⟩
        ⟨
        s
        
          |
        
        I
      
    
    
  
 is a reflection through 
  
    
      
        
          |
        
        s
        ⟩
      
    
    
  
. Both operators 
  
    
      
        
          U
          
            s
          
        
      
    
    
  
 and 
  
    
      
        
          U
          
            ω
          
        
      
    
    
  
 take states in the plane spanned by 
  
    
      
        
          |
        
        
          s
          ′
        
        ⟩
      
    
    
  
 and 
  
    
      
        
          |
        
        ω
        ⟩
      
    
    
  
 to states in the plane. Therefore, Grover's algorithm stays in this plane for the entire algorithm.
It is straightforward to check that the operator 
  
    
      
        
          U
          
            s
          
        
        
          U
          
            ω
          
        
      
    
    
  
 of each Grover iteration step rotates the state vector by an angle of 
  
    
      
        θ
        2
        arcsin
         
        
          
            
              1
              
                N
              
            
          
        
      
    
    
  
. So, with enough iterations, one can rotate from the initial state 
  
    
      
        
          |
        
        s
        ⟩
      
    
    
  
 to the desired output state 
  
    
      
        
          |
        
        ω
        ⟩
      
    
    
  
. The initial ket is close to the state orthogonal to 
  
    
      
        
          |
        
        ω
        ⟩
      
    
    
  
:

  
    
      
        ⟨
        
          s
          ′
        
        
          |
        
        s
        ⟩
        
          
            
              
                N
                1
              
              N
            
          
        
        .
      
    
    
  

In geometric terms, the angle 
  
    
      
        θ
        
          /
        
        2
      
    
    
  
 between 
  
    
      
        
          |
        
        s
        ⟩
      
    
    
  
 and 
  
    
      
        
          |
        
        
          s
          ′
        
        ⟩
      
    
    
  
 is given by

  
    
      
         
        
          
            θ
            2
          
        
        
          
            1
            
              N
            
          
        
        .
      
    
    
  

We need to stop when the state vector passes close to 
  
    
      
        
          |
        
        ω
        ⟩
      
    
    
  
; after this, subsequent iterations rotate the state vector away from 
  
    
      
        
          |
        
        ω
        ⟩
      
    
    
  
, reducing the probability of obtaining the correct answer. The exact probability of measuring the correct answer is

  
    
      
        
          
            2
          
        
         
        
          
            
              
              
            
            r
            
              
                1
                2
              
            
            
              
              
            
            θ
          
        
        ,
      
    
    
  

where r is the (integer) number of Grover iterations. The earliest time that we get a near-optimal measurement is therefore 
  
    
      
        r
        ≈
        π
        
          
            N
          
        
        
          /
        
        4
      
    
    
  
.

== Algebraic proof ==
To complete the algebraic analysis, we need to find out what happens when we repeatedly apply 
  
    
      
        
          U
          
            s
          
        
        
          U
          
            ω
          
        
      
    
    
  
. A natural way to do this is by eigenvalue analysis of a matrix. Notice that during the entire computation, the state of the algorithm is a linear combination of 
  
    
      
        s
      
    
    
  
 and 
  
    
      
        ω
      
    
    
  
. We can write the action of 
  
    
      
        
          U
          
            s
          
        
      
    
    
  
 and 
  
    
      
        
          U
          
            ω
          
        
      
    
    
  
 in the space spanned by 
  
    
      
        
          |
        
        s
        ⟩
        ,
        
          |
        
        ω
        ⟩
      
    
    
  
 as:

  
    
      
        
          
            
              
                
                  U
                  
                    s
                  
                
                :
                a
                
                  |
                
                ω
                ⟩
                b
                
                  |
                
                s
                ⟩
              
              
                
                ↦
                
                  |
                
                ω
                ⟩
                
                
                  |
                
                s
                ⟩
                
                  
                    
                      
                        
                          1
                        
                        
                          0
                        
                      
                      
                        
                          2
                          
                            /
                          
                          
                            
                              N
                            
                          
                        
                        
                          1
                        
                      
                    
                  
                
                
                  
                    
                      
                        
                          a
                        
                      
                      
                        
                          b
                        
                      
                    
                  
                
                .
              
            
            
              
                
                  U
                  
                    ω
                  
                
                :
                a
                
                  |
                
                ω
                ⟩
                b
                
                  |
                
                s
                ⟩
              
              
                
                ↦
                
                  |
                
                ω
                ⟩
                
                
                  |
                
                s
                ⟩
                
                  
                    
                      
                        
                          1
                        
                        
                          2
                          
                            /
                          
                          
                            
                              N
                            
                          
                        
                      
                      
                        
                          0
                        
                        
                          1
                        
                      
                    
                  
                
                
                  
                    
                      
                        
                          a
                        
                      
                      
                        
                          b
                        
                      
                    
                  
                
                .
              
            
          
        
      
    
    
  

So in the basis 
  
    
      
        
          |
        
        ω
        ⟩
        ,
        
          |
        
        s
        ⟩
      
    
    
  
 (which is neither orthogonal nor a basis of the whole space) the action 
  
    
      
        
          U
          
            s
          
        
        
          U
          
            ω
          
        
      
    
    
  
 of applying 
  
    
      
        
          U
          
            ω
          
        
      
    
    
  
 followed by 
  
    
      
        
          U
          
            s
          
        
      
    
    
  
 is given by the matrix

  
    
      
        
          U
          
            s
          
        
        
          U
          
            ω
          
        
        
          
            
              
                
                  1
                
                
                  0
                
              
              
                
                  2
                  
                    /
                  
                  
                    
                      N
                    
                  
                
                
                  1
                
              
            
          
        
        
          
            
              
                
                  1
                
                
                  2
                  
                    /
                  
                  
                    
                      N
                    
                  
                
              
              
                
                  0
                
                
                  1
                
              
            
          
        
        
          
            
              
                
                  1
                
                
                  2
                  
                    /
                  
                  
                    
                      N
                    
                  
                
              
              
                
                  2
                  
                    /
                  
                  
                    
                      N
                    
                  
                
                
                  1
                  4
                  
                    /
                  
                  N
                
              
            
          
        
        .
      
    
    
  

This matrix happens to have a very convenient Jordan form. If we define 
  
    
      
        t
        arcsin
         
        1
        
          /
        
        
          
            N
          
        
      
    
    
  
, it is

  
    
      
        
          U
          
            s
          
        
        
          U
          
            ω
          
        
        M
        
          
            
              
                
                  
                    e
                    
                      2
                      i
                      t
                    
                  
                
                
                  0
                
              
              
                
                  0
                
                
                  
                    e
                    
                      2
                      i
                      t
                    
                  
                
              
            
          
        
        
          M
          
            1
          
        
      
    
    
  

where 
  
    
      
        M
        
          
            
              
                
                  i
                
                
                  i
                
              
              
                
                  
                    e
                    
                      i
                      t
                    
                  
                
                
                  
                    e
                    
                      i
                      t
                    
                  
                
              
            
          
        
        .
      
    
    
  

It follows that r-th power of the matrix (corresponding to r iterations) is

  
    
      
        
          U
          
            s
          
        
        
          U
          
            ω
          
        
        
          
            r
          
        
        M
        
          
            
              
                
                  
                    e
                    
                      2
                      r
                      i
                      t
                    
                  
                
                
                  0
                
              
              
                
                  0
                
                
                  
                    e
                    
                      2
                      r
                      i
                      t
                    
                  
                
              
            
          
        
        
          M
          
            1
          
        
        .
      
    
    
  

Using this form, we can use trigonometric identities to compute the probability of observing ω after r iterations mentioned in the previous section,

  
    
      
        
          
            |
            
              
                
                  
                    
                      
                        ⟨
                        ω
                        
                          |
                        
                        ω
                        ⟩
                      
                      
                        ⟨
                        ω
                        
                          |
                        
                        s
                        ⟩
                      
                    
                  
                
              
              
                U
                
                  s
                
              
              
                U
                
                  ω
                
              
              
                
                  r
                
              
              
                
                  
                    
                      
                        0
                      
                    
                    
                      
                        1
                      
                    
                  
                
              
            
            |
          
          
            2
          
        
        
          
            2
          
        
         
        
          
            2
            r
            1
            t
          
        
        .
      
    
    
  

Alternatively, one might reasonably imagine that a near-optimal time to distinguish would be when the angles 2rt and −2rt are as far apart as possible, which corresponds to 
  
    
      
        2
        r
        t
        ≈
        π
        
          /
        
        2
      
    
    
  
, or 
  
    
      
        r
        π
        
          /
        
        4
        t
        π
        
          /
        
        4
        arcsin
         
        1
        
          /
        
        
          
            N
          
        
        ≈
        π
        
          
            N
          
        
        
          /
        
        4
      
    
    
  
. Then the system is in state

  
    
      
        
          |
        
        ω
        ⟩
        
        
          |
        
        s
        ⟩
        (
        
          U
          
            s
          
        
        
          U
          
            ω
          
        
        
          
            r
          
        
        
          
            
              
                
                  0
                
              
              
                
                  1
                
              
            
          
        
        ≈
        
          |
        
        ω
        ⟩
        
        
          |
        
        s
        ⟩
        M
        
          
            
              
                
                  i
                
                
                  0
                
              
              
                
                  0
                
                
                  i
                
              
            
          
        
        
          M
          
            1
          
        
        
          
            
              
                
                  0
                
              
              
                
                  1
                
              
            
          
        
        
          |
        
        ω
        ⟩
        
          
            1
            
               
              t
            
          
        
        
          |
        
        s
        ⟩
        
          
            
               
              t
            
            
               
              t
            
          
        
        .
      
    
    
  

A short calculation now shows that the observation yields the correct answer ω with error 
  
    
      
        O
        
          
            
              1
              N
            
          
        
      
    
    
  
.

== Extensions and variants ==

=== Multiple matching entries ===

If, instead of 1 matching entry, there are k matching entries, the same algorithm works, but the number of iterations must be 
  
    
      
        
          
            π
            4
          
        
        
          
            
              N
              k
            
          
        
      
    
    {\textstyle {\frac {\pi }{4}}{\sqrt {\frac {N}{k}}}}
  
 instead of 
  
    
      
        
          
            π
            4
          
        
        
          
            N
          
        
      
    
    {\textstyle {\frac {\pi }{4}}{\sqrt {N}}}
  
.
There are several ways to handle the case if k is unknown. A simple solution performs optimally up to a constant factor: run Grover's algorithm repeatedly for increasingly small values of k, e.g., taking k = N, N/2, N/4, ..., and so on, taking 
  
    
      
        k
        N
        
          /
        
        
          2
          
            t
          
        
      
    
    
  
 for iteration t until a matching entry is found.
With sufficiently high probability, a marked entry will be found by iteration 
  
    
      
        t
        
          
            2
          
        
         
        N
        
          /
        
        k
        +
        c
      
    
    
  
 for some constant c. Thus, the total number of iterations taken is at most

  
    
      
        
          
            π
            4
          
        
        
          
          
        
        1
        
          
            2
          
        
        
          
            4
          
        
        ⋯
        
          
            
              N
              
                k
                
                  2
                  
                    c
                  
                
              
            
          
        
        
          
          
        
        O
        
          
          
        
        
          
            N
            
              /
            
            k
          
        
        
          
          
        
        .
      
    
    
  

Another approach if k is unknown is to derive it via the quantum counting algorithm prior.
If 
  
    
      
        k
        N
        
          /
        
        2
      
    
    
  
 (or the traditional one marked state Grover's Algorithm if run with 
  
    
      
        N
        2
      
    
    
  
), the algorithm will provide no amplification. If 
  
    
      
        k
        N
        
          /
        
        2
      
    
    
  
, increasing k will begin to increase the number of iterations necessary to obtain a solution. On the other hand, if 
  
    
      
        k
        ≥
        N
        
          /
        
        2
      
    
    
  
, a classical running of the checking oracle on a single random choice of input will more likely than not give a correct solution.
A version of this algorithm is used in order to solve the collision problem.

=== Quantum partial search ===
A  modification of Grover's algorithm called quantum partial search was described by Grover and Radhakrishnan in 2004. In partial search, one is not interested in finding the exact address of the target item, only the first few digits of the address. Equivalently, we can think of "chunking" the search space into blocks, and then asking "in which block is the target item?". In many applications, such a search yields enough information if the target address contains the information wanted. For instance, to use the example given by L. K. Grover, if one has a list of students organized by class rank, we may only be interested in whether a student is in the lower 25%, 25–50%, 50–75% or 75–100% percentile.
To describe partial search, we consider a database separated into 
  
    
      
        K
      
    
    
  
 blocks, each of size 
  
    
      
        b
        N
        
          /
        
        K
      
    
    
  
. The partial search problem is easier. Consider the approach we would take classically – we pick one block at random, and then perform a normal search through the rest of the blocks (in set theory language, the complement). If we do not find the target, then we know it is in the block we did not search. The average number of iterations drops from 
  
    
      
        N
        
          /
        
        2
      
    
    
  
 to 
  
    
      
        N
        b
        
          /
        
        2
      
    
    
  
.
Grover's algorithm requires 
  
    
      
        
          
            π
            4
          
        
        
          
            N
          
        
      
    
    {\textstyle {\frac {\pi }{4}}{\sqrt {N}}}
  
 iterations. Partial search will be faster by a numerical factor that depends on the number of blocks 
  
    
      
        K
      
    
    
  
. Partial search uses 
  
    
      
        
          n
          
            1
          
        
      
    
    
  
 global iterations and 
  
    
      
        
          n
          
            2
          
        
      
    
    
  
 local iterations. The global Grover operator is designated 
  
    
      
        
          G
          
            1
          
        
      
    
    
  
 and the local Grover operator is designated 
  
    
      
        
          G
          
            2
          
        
      
    
    
  
.
The global Grover operator acts on the blocks. Essentially, it is given as follows:

Perform 
  
    
      
        
          j
          
            1
          
        
      
    
    
  
 standard Grover iterations on the entire database.
Perform 
  
    
      
        
          j
          
            2
          
        
      
    
    
  
 local Grover iterations. A local Grover iteration is a direct sum of Grover iterations over each block.
Perform one standard Grover iteration.
The optimal values of 
  
    
      
        
          j
          
            1
          
        
      
    
    
  
 and 
  
    
      
        
          j
          
            2
          
        
      
    
    
  
 are discussed in the paper by Grover and Radhakrishnan. One might also wonder what happens if one applies successive partial searches at different levels of "resolution". This idea was studied in detail by Vladimir Korepin and Xu, who called it binary quantum search. They proved that it is not in fact any faster than performing a single partial search.

== Optimality ==
Grover's algorithm is optimal up to sub-constant factors. That is, any algorithm that accesses the database only by using the operator Uω must apply Uω at least a 
  
    
      
        1
        o
        1
      
    
    
  
 fraction as many times as Grover's algorithm. The extension of Grover's algorithm to k matching entries, π(N/k)1/2/4, is also optimal. This result is important in understanding the limits of quantum computation.
If the Grover's search problem was solvable with logc N applications of Uω, that would imply that NP is contained in BQP, by transforming problems in NP into Grover-type search problems. The optimality of Grover's algorithm suggests that quantum computers cannot solve NP-Complete problems in polynomial time, and thus NP is not contained in BQP.
It has been shown that a class of non-local hidden variable quantum computers could implement a search of an 
  
    
      
        N
      
    
    
  
-item database in at most 
  
    
      
        O
        
          
            N
            
              3
            
          
        
      
    
    
  
 steps. This is faster than the 
  
    
      
        O
        
          
            N
          
        
      
    
    
  
 steps taken by Grover's algorithm.

== See also ==
Amplitude amplification
Brassard–Høyer–Tapp algorithm (for solving the collision problem)
Shor's algorithm (for factorization)
Quantum walk search

== Notes ==

== References ==
Grover L.K.: A fast quantum mechanical algorithm for database search, Proceedings, 28th Annual ACM Symposium on the Theory of Computing, (May 1996) p. 212
Grover L.K.: From Schrödinger's equation to quantum search algorithm, American Journal of Physics, 69(7): 769–777, 2001. Pedagogical review of the algorithm and its history.
Grover L.K.: QUANTUM COMPUTING: How the weird logic of the subatomic world could make it possible for machines to calculate millions of times faster than they do today The Sciences, July/August 1999, pp. 24–30.
Nielsen, M.A. and Chuang, I.L. Quantum computation and quantum information. Cambridge University Press, 2000. Chapter 6.
What's a Quantum Phone Book?, Lov Grover, Lucent Technologies

== External links ==

Davy Wybiral. "Quantum Circuit Simulator". Archived from the original on 2017-01-16. Retrieved 2017-01-13.
Craig Gidney (2013-03-05). "Grover's Quantum Search Algorithm". Archived from the original on 2020-11-17. Retrieved 2013-03-08.
François Schwarzentruber (2013-05-18). "Grover's algorithm".
Alexander Prokopenya. "Quantum Circuit Implementing Grover's Search Algorithm". Wolfram Alpha.
"Quantum computation, theory of", Encyclopedia of Mathematics, EMS Press, 2001 
Roberto Maestre (2018-05-11). "Grover's Algorithm implemented in R and C". GitHub.
Bernhard Ömer. "QCL - A Programming Language for Quantum Computers". Retrieved 2022-04-30. Implemented in /qcl-0.6.4/lib/grover.qcl

*(note truncated for size; full article at the source link below)*

## Related

- [[Amplitude amplification]]
- [[Shor's algorithm]]
- [[(1+ε)-approximate nearest neighbor search]]
- [[A- search algorithm]]
- [[Aharonov–Jones–Landau algorithm]]
- [[All nearest smaller values]]
- [[Alpha–beta pruning]]
- [[Anytime A-]]
- [[Anytime algorithm]]
- [[B-]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Grover's_algorithm