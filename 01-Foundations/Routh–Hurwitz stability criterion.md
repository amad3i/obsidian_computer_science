---
title: "Routh–Hurwitz stability criterion"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Routh–Hurwitz_stability_criterion"
wikipedia_categories: ["Electronic amplifiers", "Electronic feedback", "Polynomials", "Signal processing", "Stability theory"]
related: ["[[Asymptotic gain model]]", "[[Blackman's theorem]]", "[[Bode plot]]", "[[Phase margin]]", "[[BIBO stability]]", "[[Derivation of the Routh array]]", "[[Parasitic oscillation]]", "[[Return ratio]]", "[[Step response]]", "[[Adaptive beamformer]]"]
---

# Routh–Hurwitz stability criterion

In control theory and the theory of differential equations, the Routh–Hurwitz stability criterion is a mathematical test that is a necessary and sufficient condition for the stability of a linear time-invariant (LTI) dynamical system or control system. A stable system is one whose output signal is bounded; the position, velocity or energy do not increase to infinity as time goes on. The Routh test is an efficient recursive algorithm that English mathematician Edward John Routh proposed in 1876 to determine whether all the roots of the characteristic polynomial of a linear system have negative real parts. German mathematician Adolf Hurwitz independently proposed in 1895 to arrange the coefficients of the polynomial into a square matrix, called the Hurwitz matrix, and showed that the polynomial is stable if and only if the sequence of determinants of its principal submatrices are all positive. The two procedures are equivalent, with the Routh test providing a more efficient way to compute the Hurwitz determinants (
  
    
      
        
          Δ
          
            i
          
        
      
    
    
  
) than computing them directly.  A polynomial satisfying the Routh–Hurwitz criterion is called a Hurwitz polynomial.
The importance of the criterion is that the roots p of the characteristic equation of a linear system with negative real parts represent solutions ept of the system that are stable (bounded).  Thus the criterion provides a way to determine if the equations of motion of a linear system have only stable solutions, without solving the system directly.  For discrete systems, the corresponding stability test can be handled by the Schur–Cohn criterion, the Jury test and the Bistritz test.
The Routh test can be derived through the use of the Euclidean algorithm and Sturm's theorem in evaluating Cauchy indices. Hurwitz derived his conditions differently.

## Related

- [[Asymptotic gain model]]
- [[Blackman's theorem]]
- [[Bode plot]]
- [[Phase margin]]
- [[BIBO stability]]
- [[Derivation of the Routh array]]
- [[Parasitic oscillation]]
- [[Return ratio]]
- [[Step response]]
- [[Adaptive beamformer]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Routh–Hurwitz_stability_criterion