---
title: "Quantum error correction"
tags: ["cs", "quantum-emerging", "core"]
domain: Quantum & Emerging
level: core
source: "https://en.wikipedia.org/wiki/Quantum_error_correction"
wikipedia_categories: ["Fault-tolerant computer systems", "Quantum computing"]
related: ["[[Fault tolerant quantum computing]]", "[[Adiabatic quantum computation]]", "[[Algorithmic qubits]]", "[[Andrea Morello]]", "[[Availability zone]]", "[[Bacon–Shor code]]", "[[BQP]]", "[[Byzantine fault]]", "[[Cat qubit quantum computer]]", "[[Cirac–Zoller controlled-NOT gate]]"]
---

# Quantum error correction

Quantum error correction (QEC) comprises a set of techniques used in quantum memory and quantum computing to protect quantum information from errors arising from decoherence and other sources of quantum noise. QEC schemes that employ codewords stabilized by a set of commuting operators are known as stabilizer codes, and the corresponding codewords are referred to as quantum error-correcting codes (QECCs).
Conceptually, to use a quantum error-correcting code, one can append ancilla qubits to qubits that need protection, and apply a unitary encoding circuit to rotate the global state into a subspace of a larger Hilbert space. This highly entangled, encoded state corrects for local noisy errors. A quantum error-correcting code makes quantum computation and quantum communication practical by providing a way for a sender and receiver to simulate a noiseless qubit channel given a noisy qubit channel whose noise conforms to a particular error model.

== Overview ==
Much of the terminology in QEC is derived from its classical counterpart, the classical error-correcting code. In classical coding theory, a code is commonly denoted by the notation 
  
    
      
        n
        ,
        k
        ,
        d
      
    
    
  
, which represents the encoding of 
  
    
      
        k
      
    
    
  
 logical bits into 
  
    
      
        n
      
    
    
  
 physical bits with code distance 
  
    
      
        d
      
    
    
  
; that is, any logical operation requires flipping at least d bits. Analogously, a quantum code that encodes k logical qubits into n physical qubits with code distance d is denoted by 
  
    
      
        [
        n
        ,
        k
        ,
        d
        ]
      
    
    
  
. Although this qubit-to-qubit encoding is the most common setting, other variants exist—such as encodings between qubits and oscillators, or between oscillators themselves—since physical implementations of quantum information may involve systems with more than two energy levels.
Based on the parameters 
  
    
      
        [
        n
        ,
        k
        ,
        d
        ]
      
    
    
  
, one can define a key figure of merit for QECCs—the code rate, given by the ratio 
  
    
      
        
          
            
              k
              n
            
          
        
      
    
    
  
. The code rate measures a code's efficiency: a higher value corresponds to lower resource overhead. It generally depends on the code distance d. An ideal QECC simultaneously achieves a large distance and a high code rate. Consequently, optimizing QECC designs to improve code rate while maintaining sufficient distance is a central objective in QEC, both theoretically and experimentally. Conversely, for cases where 
  
    
      
        k
      
    
    
  
 and 
  
    
      
        d
      
    
    
  
 are fixed (often small), increasing the code rate reduces resource requirements, making such codes particularly suitable for small-scale or resource-limited experimental implementations.
Before considering scenario-dependent objectives, a QEC scheme fundamentally consists of three stages:

Encoding the logical information into physical carriers,
Transmitting or storing the encoded information through a spatial or temporal channel (corresponding to communication or memory, respectively), and
Syndrome extraction and recovery (decoding) to identify and correct errors.
A QECC is constructed under specific assumptions about the types of errors that may occur and must be capable of correcting them. The stabilizers to be measured are carefully chosen so as not to reveal any logical information, but only information about the errors themselves—as otherwise the measurement would destroy any quantum superposition of this logical qubit with other qubits in the quantum computer, which would prevent it from being used to convey quantum information. In most QECCs, the type of error is either a bit flip, or a phase flip, or both (corresponding to the Pauli matrices 
  
    
      
        X
      
    
    
  
, 
  
    
      
        Y
      
    
    
  
, and 
  
    
      
        Z
      
    
    
  
).
Various strategies exist for encoding and decoding, including classical algorithms that map measured error syndromes to their corresponding recovery operations. The sequence of applied quantum gates can also be optimized, as multi-qubit gates are generally more challenging to implement than single-qubit ones. Furthermore, the total number of possible syndromes is 
  
    
      
        
          2
          
            n
            k
          
        
      
    
    
  
, which can be prohibitively large for a simple lookup-table approach. Consequently, efficient classical decoding algorithms are generally required, except in cases where the code structure is sufficiently simple.
Compared with quantum memory, where channel-induced errors are the primary concern, the frequent application of quantum gates in quantum computation necessitates fault-tolerant design. For QECCs implemented on qubit-based platforms, fault tolerance additionally accounts for imperfect quantum gates, faulty state preparation, and measurement errors. In contrast, for QECCs that encode information into oscillators, the term fault tolerance is sometimes used interchangeably with ordinary quantum error correction and does not carry additional meaning.

=== Types of errors ===
The types of errors that occur in a quantum system depend strongly on the underlying physical platform, rather than on device-independent assumptions. For instance, even when a qubit is under active control, it remains coupled to its environment through nonzero Einstein coefficients. When the environment is cooled to its vacuum state, this coupling gives rise to amplitude-damping errors (or excitation loss), which reflect the system's tendency to relax toward thermal equilibrium and are characterized by a relaxation time. Moreover, even an isolated qubit possesses an intrinsic Hamiltonian corresponding to its internal dynamics, leading to coherent errors. Together, amplitude damping and coherent evolution contribute to dephasing, one of the dominant noise processes in most qubit implementations.
As noted earlier, most QECCs assume that the dominant errors are bit flips, phase flips, or combinations of both—corresponding to the Pauli operators. An implicit assumption in this framework is that general physical errors can be approximated as elements of the Pauli group. Under this model, each qubit's error can be represented by two classical bits (00: no error, 01: 
  
    
      
        Z
      
    
    
  
, 10: 
  
    
      
        X
      
    
    
  
, 11: 
  
    
      
        Y
      
    
    
  
). Consequently, errors on an n-qubit system can be described by a binary string of length 2n, allowing classical error-correction techniques to be applied under suitable constraints. Although this approximation does not capture all realistic noise processes, it remains widely used because it greatly simplifies both theoretical analysis and code design.

=== More general QEC schemes ===
The 
  
    
      
        [
        n
        ,
        k
        ,
        d
        ]
      
    
    
  
 QECCs do not encompass all possible quantum codes. These belong to the class of additive codes, defined within the stabilizer formalism. A more general class, known as non-additive codes, extends beyond this framework. For instance, the 
  
    
      
        (
        5
        ,
        6
        ,
        2
        )
      
    
    
  
 code encodes more than two qubits 
  
    
      
        
          
            2
          
        
         
        6
        ≈
        2.585
      
    
    
  
 into five physical qubits with code distance two.  Non-additive codes can, in principle, achieve higher code rates than additive ones, but their construction and analysis are considerably more challenging. As a result, they remain relatively unexplored, with only limited studies to date.
Beyond encoding qubits into qubits, quantum information can also be stored in more general physical systems, such as 
  
    
      
        d
      
    
    
  
-level systems (qudits) or infinite-dimensional oscillators. Encoding a smaller logical system into a larger physical Hilbert space is an active area of research.

== Important code families ==

The first QECC, named after Peter Shor, can be generalized as a 
  
    
      
        [
        
          d
          
            2
          
        
        ,
        1
        ,
        d
        ]
      
    
    
  
 code, which increases the code distance at the expense of a reduced code rate. Its design philosophy employs inner and outer 
  
    
      
        d
        ,
        1
        ,
        d
      
    
    
  
 repetition codes to independently correct bit-flip and phase-flip errors. In contrast, Andrew Steane improved the code rate by replacing repetition codes with the classical 
  
    
      
        7
        ,
        4
      
    
    
  
 Hamming code and treating bit-flip and phase-flip errors symmetrically, without distinguishing inner and outer layers. The approach of Steane can be generalized as 
  
    
      
        [
        
          2
          
            r
          
        
        1
        ,
        
          2
          
            r
          
        
        1
        2
        r
        ,
        3
        ]
      
    
    
  
 quantum Hamming codes. A generalization of these approaches led to the development of the CSS codes—named after Robert Calderbank, Peter Shor, and Andrew Steane. The structure of CSS codes is particularly well-suited for fault-tolerant syndrome measurement, as the 
  
    
      
        X
      
    
    
  
 and 
  
    
      
        Z
      
    
    
  
 stabilizers are cleanly separated.
While the Shor code emphasizes code distance and the Steane code emphasizes code rate, other CSS codes can be constructed to balance these parameters. For example, using overlapped-repetition codes enables CSS codes with improved performance and the 
  
    
      
        [
        7
        ,
        1
        ,
        3
        ]
      
    
    
  
 Shor-type code is shown. Furthermore, this Shor-type code can be modified as subsystem codes such as the Bacon–Shor code which might optimize the syndrome measurement.
The quantum threshold theorem, shows that quantum computations of arbitrary length are possible. It states that errors can be corrected by recursively concatenating quantum codes—such as CSS codes—across logarithmically many levels, provided the error rate of individual quantum gates remains below a certain threshold. Above this threshold, attempts to measure syndromes and correct errors would introduce more errors than they eliminate. As of 2004, estimates suggest this threshold could be as high as 1–3%, assuming a sufficiently large number of qubits is available.
To achieve a higher code rate for encoding a single logical qubit with single-error correction, Raymond Laflamme et al. discovered a five-qubit code using four stabilizers that mix 
  
    
      
        X
      
    
    
  
 and 
  
    
      
        Z
      
    
    
  
 operators. A well-known variant employs four cyclic 
  
    
      
        X
        Z
        Z
        X
        I
      
    
    
  
 stabilizers. Although this code is clearly not a CSS code, DiVincenzo and Shor demonstrated that it can still be made fault-tolerant. The five-qubit code is the smallest possible code capable of protecting one logical qubit against arbitrary single-qubit errors. According to the quantum Hamming bound, encoding a single logical qubit with the ability to correct any single-qubit error requires at least five physical qubits.
Beyond coding-theoretic designs, topological QECCs are particularly intuitive to visualize and can provide a clear layout of local stabilizer measurements, which is experimentally friendly. Alexei Kitaev introduced the toric code without boundaries, which was later adapted into the surface code with boundaries, yielding a 2D planar layout that avoids non-local measurements. Surface codes are pivotal for scalable quantum error correction in 2025, enabling below-threshold logical qubits with improved fidelity in superconducting systems.

Unlike a two-level system, a quantum harmonic oscillator possesses infinitely many energy levels within a single physical system. These codes exploit the inherent redundancy within a single oscillator, rather than relying on multiple two-level qubits for encoding.
While the cat code and GKP codes are purely bosonic with no direct qubit correspondence, (extended) binomial codes are closely related to (high-rate) Shor codes. The underlying idea is to treat the grouped qubits in each inner repetition code as identical particles, mapping them to a single bosonic mode in the Fock basis, thereby linking qubit codes to bosonic codes.

=== Other code families ===
Constant-excitation codes are designed to protect against collective coherent errors arising from the intrinsic Hamiltonian of physical qubits during an unknown storage or transmission duration, such as when the receiver may be in motion.
Entanglement-assisted stabilizer formalism, constructed by Todd Brun et al., is an extension of the standard stabilizer formalism that incorporates quantum entanglement shared between a sender and a receiver.
Eric Rains and John Smolin et al. generalize previous non-additive codes to more distance two cases. Yu et al. further improve the code distance to three.
Noh et al. proposed a QEC scheme that protects a single oscillator using an ancillary GKP state.

== Classical codes as bias quantum code ==
Classical error-correcting codes that employ redundancy can be mapped to biased quantum codes that correct either Pauli X (bit-flip) or Pauli Z (phase-flip) errors. The simplest, though inefficient, example is the repetition code. In a repetition code, the logical information is stored as multiple copies of a bit. If these copies are later found to disagree due to errors, the most likely original value is inferred via majority vote.
For example, consider a logical bit in the "1" state copied three times. If noise corrupts one of the three bits, leaving the other two unchanged, the most likely scenario is that a single-bit error occurred, and the original logical value was "1." While it is possible that two bits flip, producing three zeros, this outcome is less probable. In this example, the logical information is the single bit, and the three copies are the physical representation.
Repetition codes work in classical channels because classical bits can be freely measured and duplicated. In quantum channels, however, the no-cloning theorem prevents copying an unknown qubit, seemingly posing an obstacle to quantum error correction. This challenge is overcome by encoding the logical information of a single qubit into a highly entangled state of multiple physical qubits. For example, the three-qubit bit-flip code, first proposed by Asher Peres in 1985, uses entanglement and syndrome measurements to correct errors in a manner analogous to the classical repetition code. A phase-flip code is similarly constructed and is equivalent to the bit-flip code up to transversal Hadamard gates.

=== Bit-flip code ===

Consider the situation in which we want to transmit the state of a single qubit 
  
    
      
        |
        ψ
        ⟩
      
    
    
  
 through a noisy channel 
  
    
      
        
          
            E
          
        
      
    
    
  
. Let us moreover assume that this channel either flips the state of the qubit, with probability 
  
    
      
        p
      
    
    
  
, or leaves it unchanged. The action of 
  
    
      
        
          
            E
          
        
      
    
    
  
 on a general input 
  
    
      
        ρ
      
    
    
  
 can therefore be written as 
  
    
      
        
          
            E
          
        
        ρ
        =
        1
        p
        ρ
        p
        ⋅
        X
        ρ
        X
      
    
    
  
.
Let 
  
    
      
        
          |
        
        ψ
        ⟩
        
          α
          
            0
          
        
        
          |
        
        0
        ⟩
        
          α
          
            1
          
        
        
          |
        
        1
        ⟩
      
    
    
  
 be the quantum state to be transmitted. With no error-correcting protocol in place, the transmitted state will be correctly transmitted with probability 
  
    
      
        1
        p
      
    
    
  
. We can however improve on this number by encoding the state into a greater number of qubits, in such a way that errors in the corresponding logical qubits can be detected and corrected. In the case of the simple three-qubit repetition code, the encoding consists in the mappings 
  
    
      
        |
        0
        ⟩
        →
        |
        
          0
          
            
              L
            
          
        
        ⟩
        ≡
        |
        000
        ⟩
      
    
    
  
 and 
  
    
      
        |
        1
        ⟩
        →
        |
        
          1
          
            
              L
            
          
        
        ⟩
        ≡
        |
        111
        ⟩
      
    
    
  
. The input state 
  
    
      
        |
        ψ
        ⟩
      
    
    
  
 is encoded into the state 
  
    
      
        |
        
          ψ
          ′
        
        ⟩
        
          α
          
            0
          
        
        |
        000
        ⟩
        
          α
          
            1
          
        
        |
        111
        ⟩
      
    
    
  
. This mapping can be realized for example using two CNOT gates, entangling the system with two ancillary qubits initialized in the state 
  
    
      
        |
        0
        ⟩
      
    
    
  
. The encoded state 
  
    
      
        |
        
          ψ
          ′
        
        ⟩
      
    
    
  
 is what is now passed through the noisy channel.
The channel acts on 
  
    
      
        |
        
          ψ
          ′
        
        ⟩
      
    
    
  
 by flipping some subset (possibly empty) of its qubits. No qubit is flipped with probability 
  
    
      
        1
        p
        
          
            3
          
        
      
    
    
  
, a single qubit is flipped with probability 
  
    
      
        3
        p
        1
        p
        
          
            2
          
        
      
    
    
  
, two qubits are flipped with probability 
  
    
      
        3
        
          p
          
            2
          
        
        1
        p
      
    
    
  
, and all three qubits are flipped with probability 
  
    
      
        
          p
          
            3
          
        
      
    
    
  
. Note that a further assumption about the channel is made here: we assume that 
  
    
      
        
          
            E
          
        
      
    
    
  
 acts equally and independently on each of the three qubits in which the state is now encoded. The problem is now how to detect and correct such errors, while not corrupting the transmitted state.

Let us assume for simplicity that 
  
    
      
        p
      
    
    
  
 is small enough that the probability of more than a single qubit being flipped is negligible. One can then detect whether a qubit was flipped, without also querying for the values being transmitted, by asking whether one of the qubits differs from the others. This amounts to performing a measurement with four different outcomes, corresponding to the following four projective measurements:
  
    
      
        
          
            
              
                
                  P
                  
                    0
                  
                
              
              
                
                
                  |
                
                000
                ⟩
                ⟨
                000
                
                  |
                
                
                  |
                
                111
                ⟩
                ⟨
                111
                
                  |
                
                ,
              
            
            
              
                
                  P
                  
                    1
                  
                
              
              
                
                
                  |
                
                100
                ⟩
                ⟨
                100
                
                  |
                
                
                  |
                
                011
                ⟩
                ⟨
                011
                
                  |
                
                ,
              
            
            
              
                
                  P
                  
                    2
                  
                
              
              
                
                
                  |
                
                010
                ⟩
                ⟨
                010
                
                  |
                
                
                  |
                
                101
                ⟩
                ⟨
                101
                
                  |
                
                ,
              
            
            
              
                
                  P
                  
                    3
                  
                
              
              
                
                
                  |
                
                001
                ⟩
                ⟨
                001
                
                  |
                
                
                  |
                
                110
                ⟩
                ⟨
                110
                
                  |
                
                .
              
            
          
        
      
    
    
  
This reveals which qubits are different from the others, without at the same time giving information about the state of the qubits themselves. If the outcome corresponding to 
  
    
      
        
          P
          
            0
          
        
      
    
    
  
 is obtained, no correction is applied, while if the outcome corresponding to 
  
    
      
        
          P
          
            i
          
        
      
    
    
  
 is observed, then the Pauli X gate is applied to the 
  
    
      
        i
      
    
    
  
-th qubit. Formally, this correcting procedure corresponds to the application of the following map to the output of the channel:

  
    
      
        
          
            
              E
            
          
          
            corr
          
        
        ρ
        =
        
          P
          
            0
          
        
        ρ
        
          P
          
            0
          
        
        
          ∑
          
            i
            1
          
          
            3
          
        
        
          X
          
            i
          
        
        
          P
          
            i
          
        
        ρ
        
        
          P
          
            i
          
        
        
          X
          
            i
          
        
        .
      
    
    
  
Note that, while this procedure perfectly corrects the output when zero or one flips are introduced by the channel, if more than one qubit is flipped then the output is not properly corrected. For example, if the first and second qubits are flipped, then the syndrome measurement gives the outcome 
  
    
      
        
          P
          
            3
          
        
      
    
    
  
, and the third qubit is flipped, instead of the first two. To assess the performance of this error-correcting scheme for a general input we can study the fidelity 
  
    
      
        F
        
          ψ
          ′
        
      
    
    
  
 between the input 
  
    
      
        |
        
          ψ
          ′
        
        ⟩
      
    
    
  
 and the output 
  
    
      
        
          ρ
          
            out
          
        
        ≡
        
          
            
              E
            
          
          
            corr
          
        
        
          
            E
          
        
        |
        
          ψ
          ′
        
        ⟩
        ⟨
        
          ψ
          ′
        
        |
        )
      
    
    
  
. Being the output state 
  
    
      
        
          ρ
          
            out
          
        
      
    
    
  
 correct when no more than one qubit is flipped, which happens with probability 
  
    
      
        1
        p
        
          
            3
          
        
        3
        p
        1
        p
        
          
            2
          
        
      
    
    
  
, we can write it as 
  
    
      
        (
        1
        p
        
          
            3
          
        
        3
        p
        1
        p
        
          
            2
          
        
        
        |
        
          ψ
          ′
        
        ⟩
        ⟨
        
          ψ
          ′
        
        |
        (
        .
        .
        .
      
    
    
  
, where the dots denote components of 
  
    
      
        
          ρ
          
            out
          
        
      
    
    
  
 resulting from errors not properly corrected by the protocol. It follows that 
  
    
      
        F
        
          ψ
          ′
        
        =
        ⟨
        
          ψ
          ′
        
        |
        
          ρ
          
            out
          
        
        |
        
          ψ
          ′
        
        ⟩
        ≥
        1
        p
        
          
            3
          
        
        3
        p
        1
        p
        
          
            2
          
        
        1
        3
        
          p
          
            2
          
        
        2
        
          p
          
            3
          
        
        .
      
    
    
  
This fidelity is to be compared with the corresponding fidelity obtained when no error-correcting protocol is used, which was shown before to equal 
  
    
      
        
          1
          p
        
      
    
    
  
. A little algebra then shows that the fidelity after error correction is greater than the one without for 
  
    
      
        p
        1
        
          /
        
        2
      
    
    
  
. Note that this is consistent with the working assumption that was made while deriving the protocol (of 
  
    
      
        p
      
    
    
  
 being small enough).

=== Sign-flip code ===

The bit flip is the only kind of error in classical computers. In quantum computers, however, another kind of error is possible: the sign flip. Through transmission in a channel, the relative sign between 
  
    
      
        
          |
        
        0
        ⟩
      
    
    
  
 and 
  
    
      
        
          |
        
        1
        ⟩
      
    
    
  
 can become inverted. For instance, a qubit in the state 
  
    
      
        
          |
        
        ⟩
        (
        
          |
        
        0
        ⟩
        
          |
        
        1
        ⟩
        
          /
        
        
          
            2
          
        
      
    
    
  
 may have its sign flip to 
  
    
      
        
          |
        
        ⟩
        (
        
          |
        
        0
        ⟩
        
          |
        
        1
        ⟩
        
          /
        
        
          
            2
          
        
        .
      
    
    
  

The original state of the qubit

  
    
      
        
          |
        
        ψ
        ⟩
        
          α
          
            0
          
        
        
          |
        
        0
        ⟩
        
          α
          
            1
          
        
        
          |
        
        1
        ⟩
      
    
    
  

will be changed into the state

  
    
      
        
          |
        
        
          ψ
          ′
        
        ⟩
        
          α
          
            0
          
        
        
          |
        
        
        
        
        
        
        
        ⟩
        
          α
          
            1
          
        
        
          |
        
        
        
        
        
        
        
        ⟩
        .
      
    
    
  

In the Hadamard basis, bit flips become sign flips and sign flips become bit flips. Let 
  
    
      
        
          E
          
            phase
          
        
      
    
    
  
 be a quantum channel that can cause at most one phase flip. Then the bit-flip code from above can recover 
  
    
      
        
          |
        
        ψ
        ⟩
      
    
    
  
 by transforming into the Hadamard basis before and after transmission through 
  
    
      
        
          E
          
            phase
          
        
      
    
    
  
.

== Encoding logical qubits into physical qubits ==

=== Shor code ===

The error channel may induce either a bit flip, a sign flip (i.e., a phase flip), or both. It is possible to correct for both types of errors on a logical qubit using a well-designed QEC code. One example of a code that does this is the Shor code, published in 1995. Since these two types of errors are the only types of errors that can result after a projective measurement, a Shor code corrects arbitrary single-qubit errors.

Let 
  
    
      
        E
      
    
    
  
 be a quantum channel that can arbitrarily corrupt a single qubit. The 1st, 4th and 7th qubits are for the sign flip code, while the three groups of qubits (1,2,3), (4,5,6), and (7,8,9) are designed for the bit flip code. With the Shor code, a qubit state 
  
    
      
        
          |
        
        ψ
        ⟩
        
          α
          
            0
          
        
        
          |
        
        0
        ⟩
        
          α
          
            1
          
        
        
          |
        
        1
        ⟩
      
    
    
  
 will be transformed into the product of 9 qubits 
  
    
      
        
          |
        
        
          ψ
          ′
        
        ⟩
        
          α
          
            0
          
        
        
          |
        
        
          0
          
            S
          
        
        ⟩
        
          α
          
            1
          
        
        
          |
        
        
          1
          
            S
          
        
        ⟩
      
    
    
  
, where

  
    
      
        
          |
        
        
          0
          
            
              S
            
          
        
        ⟩
        
          
            1
            
              2
              
                
                  2
                
              
            
          
        
        
          |
        
        000
        ⟩
        
          |
        
        111
        ⟩
        ⊗
        
          |
        
        000
        ⟩
        
          |
        
        111
        ⟩
        ⊗
        
          |
        
        000
        ⟩
        
          |
        
        111
        ⟩
      
    
    
  

  
    
      
        
          |
        
        
          1
          
            
              S
            
          
        
        ⟩
        
          
            1
            
              2
              
                
                  2
                
              
            
          
        
        
          |
        
        000
        ⟩
        
          |
        
        111
        ⟩
        ⊗
        
          |
        
        000
        ⟩
        
          |
        
        111
        ⟩
        ⊗
        
          |
        
        000
        ⟩
        
          |
        
        111
        ⟩
      
    
    
  

If a bit flip error happens to a qubit, the syndrome analysis will be performed on each block of qubits (1,2,3), (4,5,6), and (7,8,9) to detect and correct at most one bit flip error in each block.
If the three bit flip group (1,2,3), (4,5,6), and (7,8,9) are considered as three inputs, then the Shor code circuit can be reduced as a sign flip code. This means that the Shor code can also repair a sign flip error for a single qubit.
The Shor code also can correct for any arbitrary errors (both bit flip and sign flip) to a single qubit. If an error is modeled by a unitary transform U, which will act on a qubit 
  
    
      
        
          |
        
        ψ
        ⟩
      
    
    
  
, then 
  
    
      
        U
      
    
    
  
 can be described in the form

  
    
      
        U
        
          c
          
            0
          
        
        I
        
          c
          
            1
          
        
        X
        
          c
          
            2
          
        
        Y
        
          c
          
            3
          
        
        Z
      
    
    
  

where 
  
    
      
        
          c
          
            0
          
        
      
    
    
  
,
  
    
      
        
          c
          
            1
          
        
      
    
    
  
,
  
    
      
        
          c
          
            2
          
        
      
    
    
  
, and 
  
    
      
        
          c
          
            3
          
        
      
    
    
  
 are complex constants, I is the identity, and the Pauli matrices are given by

  
    
      
        
          
            
              
                X
              
              
                
                
                  
                    
                      
                        
                          0
                        
                        
                          1
                        
                      
                      
                        
                          1
                        
                        
                          0
                        
                      
                    
                  
                
                ;
              
            
            
              
                Y
              
              
                
                
                  
                    
                      
                        
                          0
                        
                        
                          i
                        
                      
                      
                        
                          i
                        
                        
                          0
                        
                      
                    
                  
                
                ;
              
            
            
              
                Z
              
              
                
                
                  
                    
                      
                        
                          1
                        
                        
                          0
                        
                      
                      
                        
                          0
                        
                        
                          1
                        
                      
                    
                  
                
                .
              
            
          
        
      
    
    
  

If U is equal to I, then no error occurs. If 
  
    
      
        U
        X
      
    
    
  
, a bit flip error occurs. If 
  
    
      
        U
        Z
      
    
    
  
, a sign flip error occurs. If 
  
    
      
        U
        i
        Y
      
    
    
  
 then both a bit flip error and a sign flip error occur. In other words, the Shor code can correct any combination of bit or phase errors on a single qubit.
More generally, the error operator U does not need to be unitary, but can be a Kraus operator from a quantum operation representing a system interacting with its environment.

== Application ==

=== In quantum metrology ===
Quantum error correction can be applied to quantum metrology. Thus, a logical qubit is stored in several physical qubits. In the case of a linear interferometer, there is not interaction between the logical qubits. However, the dynamics is given with operators that contain multiqubit correlation operators of the physical qubits corresponding to a logical qubits. In this scheme, the errors can be detected, and corrected following the general rules of quantum error correction.
In another approach, the goal is not correcting the quantum state, but to keep a state that makes quantum metrology with high precision possible even if noise is present. It has been observed that some quantum states that cannot outperform separable states in quantum metrology, can be better than separable states in the multi-copy case, hence their metrological abilities can be activated. 
Thus, instead of stroring each logical qubit in several physical qubits, we store several copies of the entire quantum state. For instance, consider an 
  
    
      
        N
      
    
    
  
-qubit quantum state 
  
    
      
        ϱ
      
    
    
  
 living in the space

  
    
      
        
          |
        
        0
        
          ⟩
          
            ⊗
            N
          
        
        ,
        
          |
        
        1
        
          ⟩
          
            ⊗
            N
          
        
        .
      
    
    
  

This subspace includes the noisy quantum state

  
    
      
        p
        
          |
        
        
          
            
              G
              H
              Z
            
          
          
            N
          
        
        ⟩
        ⟨
        
          
            
              G
              H
              Z
            
          
          
            N
          
        
        
          |
        
        (
        1
        p
        
          
            
              
                |
              
              0
              ⟩
              ⟨
              0
              
                |
              
              
                
                  ⊗
                  N
                
              
              (
              
                |
              
              1
              ⟩
              ⟨
              1
              
                |
              
              
                
                  ⊗
                  N
                
              
            
            2
          
        
        ,
      
    
    
  

where the Greenberger-Horne-Zeilinger (GHZ) state is given as

  
    
      
        
          |
        
        
          
            
              G
              H
              Z
            
          
          
            N
          
        
        ⟩
        
          
            1
            
              2
            
          
        
        
          |
        
        0
        
          ⟩
          
            ⊗
            N
          
        
        
          |
        
        1
        
          ⟩
          
            ⊗
            N
          
        
        .
      
    
    
  

Let us consider 
  
    
      
        M
      
    
    
  
 copies of the state

  
    
      
        
          ϱ
          
            M
            
              -copy
            
          
        
        
          ϱ
          
            ⊗
            M
          
        
        .
      
    
    
  

Then, the following Hamiltonian

  
    
      
        H
        
          ∑
          
            n
            1
          
          
            N
          
        
        
          ∏
          
            m
            1
          
          
            M
          
        
        
          σ
          
            z
          
          
            n
            ,
            m
          
        
      
    
    
  

acts on the 
  
    
      
        M
      
    
    
  
-copy quantum state. Here, 
  
    
      
        
          σ
          
            z
          
          
            n
            ,
            m
          
        
      
    
    
  
 is the Pauli spin matrix 
  
    
      
        
          σ
          
            z
          
        
      
    
    
  
 for the nth qubit of the mth copy. The metrological usefulness characterized by the quantum Fisher information as

  
    
      
        
          F
          
            Q
          
        
        ϱ
        ,
        H
      
    
    
  

increases exponentially with the number of copies, 
  
    
      
        M
      
    
    
  
,
and approaches the metrological usefulness of the GHZ state, 
  
    
      
        4
        
          N
          
            2
          
        
        .
      
    
    
  
 Separable states reach 
  
    
      
        4
        N
        .
      
    
    
  

If the state is outside of the subspace described above, then it can be brought back to the subspace with the usual steps of error correction with the bitflip code.
In another example, one can see that in this scheme a phase error is suppressed even without error correction. Let us call the three copies of the 
  
    
      
        N
      
    
    
  
-qubit GHZ state then a single phase

  
    
      
        
          |
        
        Ψ
        ⟩
        
          |
        
        
          
            
              G
              H
              Z
            
          
          
            N
          
        
        ⟩
        ⊗
        
          |
        
        
          
            
              G
              H
              Z
            
          
          
            N
          
        
        ⟩
        ⊗
        
          |
        
        
          
            
              G
              H
              Z
            
          
          
            N
          
        
        ⟩
        ,
      
    
    
  

and consider the Hamiltonian above. Then, the metrological usefulness of the state is characterized by the quantum Fisher information 
  
    
      
        
          F
          
            Q
          
        
        
          |
        
        Ψ
        ⟩
        ⟨
        Ψ
        
          |
        
        ,
        H
      
    
    
  
.
Let us denote the state after one of the qubits passes through a phase flip channel by 
  
    
      
        
          ϱ
          
            
              p
              h
              a
              s
              e
              f
              l
              i
              p
            
          
        
        .
      
    
    
  
 It can be shown that the metrological usefulness of the state does not change

  
    
      
        
          F
          
            Q
          
        
        
          ϱ
          
            
              p
              h
              a
              s
              e
              f
              l
              i
              p
            
          
        
        ,
        H
        =
        
          F
          
            Q
          
        
        
          |
        
        Ψ
        ⟩
        ⟨
        Ψ
        
          |
        
        ,
        H
      
    
    
  

and it remains maximal. Thus, even without an error correction step, the metrological properties remain the same. (See the Supplement E in Ref., and Ref.)

== Experimental realization ==
There have been several experimental realizations of CSS-based codes. The first demonstration was with nuclear magnetic resonance qubits. Subsequently, demonstrations have been made with linear optics, trapped ions, and superconducting (transmon) qubits.

In 2016 for the first time the lifetime of a quantum bit was prolonged by employing a QEC code.
The error-correction demonstration was performed on Schrödinger-cat states encoded in a superconducting resonator, and employed a quantum controller capable of performing real-time feedback operations including read-out of the quantum information, its analysis, and the correction of its detected errors. The work demonstrated how the quantum-error-corrected system reaches the break-even point at which the lifetime of a logical qubit exceeds the lifetime of the underlying constituents of the system (the physical qubits).
Other error correcting codes have also been implemented, such as one aimed at correcting for photon loss, the dominant error source in photonic qubit schemes.
In 2021, an entangling gate between two logical qubits encoded in topological quantum error-correction codes has first been realized using 10 ions in a trapped-ion quantum computer.
2021 also saw the first experimental demonstration of fault-tolerant Bacon-Shor code in a single logical qubit of a trapped-ion system, i.e. a demonstration for which the addition of error correction is able to suppress more errors than is introduced by the overhead required to implement the error correction as well as fault tolerant Steane code.
In a different direction, using an encoding corresponding to the Jordan-Wigner mapped Majorana zero modes of a Kitaev chain, researchers were able to perform quantum teleportation of a logical qubit, where an improvement in fidelity from 71% to 85% was observed.
In 2022, researchers at the University of Innsbruck have demonstrated a fault-tolerant universal set of gates on two logical qubits in a trapped-ion quantum computer.
They have performed a logical two-qubit controlled-NOT gate between two instances of the seven-qubit color code, and fault-tolerantly prepared a logical magic state.
In 2022, research at University of Engineering and Technology Lahore demonstrated error cancellation by inserting single-qubit Z-axis rotation gates into strategically chosen locations of the superconductor quantum circuits.
The scheme has been shown to effectively correct errors that would otherwise rapidly add up under constructive interference of coherent noise. This is a circuit-level calibration scheme that traces deviations (e.g. sharp dips or notches) in the decoherence curve to detect and localize the coherent error, but does not require encoding or parity measurements. However, further investigation is needed to establish the effectiveness of this method for the incoherent noise.
In February 2023, researchers at Google claimed to have decreased quantum errors by increasing the qubit number in experiments, they used a fault tolerant surface code measuring an error rate of 3.028% and 2.914% for a distance-3 qubit array and a distance-5 qubit array respectively.
In April 2024, researchers at Microsoft claimed to have successfully tested a quantum error correction code that allowed them to achieve an error rate with logical qubits that is 800 times better than the underlying physical error rate.
This qubit virtualization system was used to create 4 logical qubits with 30 of the 32 qubits on Quantinuum's trapped-ion hardware. The system uses an active syndrome extraction technique to diagnose errors and correct them while calculations are underway without destroying the logical qubits.
In January 2025, researchers at UNSW Sydney managed to develop an error correction method using antimony-based materials, including antimonides, leveraging high-dimensional quantum states (qudits) with up to eight states. Using a Kane quantum computer employing advanced pulse control techniques, they demonstrated enhanced error resilience.

== See also ==
Error detection and correction
Fault tolerant quantum computing
Soft error

== References ==

== Further reading ==
Daniel Lidar and Todd Brun, ed. (2013). Quantum Error Correction. Cambridge University Press.
La Guardia, Giuliano Gadioli, ed. (2020). Quantum Error Correction: Symmetric, Asymmetric, Synchronizable, and Convolutional Codes. Springer Nature.
Frank Gaitan (2008). Quantum Error Correction and Fault Tolerant Quantum Computing. Taylor & Francis.
Freedman, Michael H.; Meyer, David A.; Luo, Feng (2002). "Z2-Systolic freedom and quantum codes". Mathematics of quantum computation. Comput. Math. Ser. Boca Raton, FL: Chapman & Hall/CRC. pp. 287–320.
Freedman, Michael H.; Meyer, David A. (1998). "Projective plane and planar quantum codes". Found. Comput. Math. 2001 (3): 325–332. arXiv:quant-ph/9810055. Bibcode:1998quant.ph.10055F.

== External links ==
"Topological Quantum Error Correction". Quantum Light. University of Sheffield. 2018-09-28. Archived from the original on 2021-12-22 – via YouTube.

*(note truncated for size; full article at the source link below)*

## Related

- [[Fault tolerant quantum computing]]
- [[Adiabatic quantum computation]]
- [[Algorithmic qubits]]
- [[Andrea Morello]]
- [[Availability zone]]
- [[Bacon–Shor code]]
- [[BQP]]
- [[Byzantine fault]]
- [[Cat qubit quantum computer]]
- [[Cirac–Zoller controlled-NOT gate]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Quantum_error_correction