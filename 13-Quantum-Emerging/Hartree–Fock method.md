---
title: "Hartree–Fock method"
tags: ["cs", "quantum-emerging", "intermediate"]
domain: Quantum & Emerging
level: intermediate
source: "https://en.wikipedia.org/wiki/Hartree–Fock_method"
wikipedia_categories: ["1927 in science", "Computational chemistry", "Computational physics", "Electronic structure methods", "Quantum chemistry", "Theoretical chemistry"]
related: ["[[Car–Parrinello molecular dynamics]]", "[[Variational method (quantum mechanics)]]", "[[Hartree equations]]", "[[Pople diagram]]", "[[Time-dependent density functional theory]]", "[[Adiabatic connection fluctuation dissipation theorem]]", "[[Basis set (chemistry)]]", "[[CHELPG]]", "[[Computational chemical methods in solid-state physics]]", "[[Computational chemistry]]"]
---

# Hartree–Fock method

In computational physics and chemistry, the Hartree–Fock (HF) method is used for approximating the wave function and the energy of a quantum many-body system in a stationary state. It is named after Douglas Hartree and Vladimir Fock.
The Hartree–Fock method often assumes that the exact 
  
    
      
        N
      
    
    
  
-body wave function of the system can be approximated by a single Slater determinant (in the case where the particles are fermions) or by a single permanent (in the case of bosons) of 
  
    
      
        N
      
    
    
  
 spin-orbitals. By invoking the variational method, one can derive a set of 
  
    
      
        N
      
    
    
  
 coupled equations for the 
  
    
      
        N
      
    
    
  
 spin orbitals. A solution of these equations yields the Hartree–Fock wave function and energy of the system. Hartree–Fock approximation is an instance of mean-field theory, where neglecting higher-order fluctuations in order parameter allows interaction terms to be replaced with quadratic terms, obtaining exactly solvable Hamiltonians.
Especially in the older literature, the Hartree–Fock method is also called the self-consistent field method (SCF). In deriving what is now called the Hartree equation as an approximate solution of the Schrödinger equation, Hartree required the final field as computed from the charge distribution to be "self-consistent" with the assumed initial field. Thus, self-consistency was a requirement of the solution. The solutions to the non-linear Hartree–Fock equations also behave as if each particle is subjected to the mean field created by all other particles (see the Fock operator below), and hence the terminology continued. The equations are almost universally solved by means of an iterative method, although the fixed-point iteration algorithm does not always converge. This solution scheme is not the only one possible and is not an essential feature of the Hartree–Fock method.
The Hartree–Fock method finds its typical application in the solution of the Schrödinger equation for atoms, molecules, nanostructures and solids but it has also found widespread use in nuclear physics. (See Hartree–Fock–Bogoliubov method for a discussion of its application in nuclear structure theory).  In atomic structure theory, calculations may be for a spectrum with many excited energy levels, and consequently, the Hartree–Fock method for atoms assumes the wave function is a single configuration state function with well-defined quantum numbers and that the energy level is not necessarily the ground state.
For both atoms and molecules, the Hartree–Fock solution is the central starting point for most methods that describe the many-electron system more accurately.
The rest of this article will focus on applications in electronic structure theory suitable for molecules with the atom as a special case.
The discussion here is only for the restricted Hartree–Fock method, where the atom or molecule is a closed-shell system with all orbitals (atomic or molecular) doubly occupied. Open-shell systems, where some of the electrons are not paired, can be dealt with by either the restricted open-shell or the unrestricted Hartree–Fock methods.

## Related

- [[Car–Parrinello molecular dynamics]]
- [[Variational method (quantum mechanics)]]
- [[Hartree equations]]
- [[Pople diagram]]
- [[Time-dependent density functional theory]]
- [[Adiabatic connection fluctuation dissipation theorem]]
- [[Basis set (chemistry)]]
- [[CHELPG]]
- [[Computational chemical methods in solid-state physics]]
- [[Computational chemistry]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Hartree–Fock_method