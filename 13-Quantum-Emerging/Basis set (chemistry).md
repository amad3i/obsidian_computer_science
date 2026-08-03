---
title: "Basis set (chemistry)"
tags: ["cs", "quantum-emerging", "intermediate"]
domain: Quantum & Emerging
level: intermediate
source: "https://en.wikipedia.org/wiki/Basis_set_(chemistry)"
wikipedia_categories: ["Computational chemistry", "Quantum chemistry", "Theoretical chemistry"]
related: ["[[Adiabatic connection fluctuation dissipation theorem]]", "[[Car–Parrinello molecular dynamics]]", "[[CHELPG]]", "[[Coulomb operator]]", "[[Distributed multipole analysis]]", "[[Energy level]]", "[[Full configuration interaction]]", "[[Görling–Levy perturbation theory]]", "[[Hamiltonian (quantum mechanics)]]", "[[Hartree equations]]"]
---

# Basis set (chemistry)

In theoretical and computational chemistry, a basis set is a set of functions (called basis functions) that is used to represent the electronic wave function in the Hartree–Fock method or density-functional theory in order to turn the partial differential equations of the model into algebraic equations suitable for efficient implementation on a computer.
The use of basis sets is equivalent to the use of an approximate resolution of the identity: the atomic orbitals 
  
    
      
        
          |
        
        
          ψ
          
            i
          
        
        ⟩
      
    
    
  
 are expanded within the basis set as a linear combination of the basis functions 
  
    
      
        
          |
        
        
          ψ
          
            i
          
        
        ⟩
        ≈
        
          ∑
          
            μ
          
        
        
          c
          
            μ
            i
          
        
        
          |
        
        μ
        ⟩
      
    
    {\textstyle |\psi _{i}\rangle \approx \sum _{\mu }c_{\mu i}|\mu \rangle }
  
, where the expansion coefficients 
  
    
      
        
          c
          
            μ
            i
          
        
      
    
    
  
 are given by 
  
    
      
        
          c
          
            μ
            i
          
        
        
          ∑
          
            ν
          
        
        ⟨
        μ
        
          |
        
        ν
        
          ⟩
          
            1
          
        
        ⟨
        ν
        
          |
        
        
          ψ
          
            i
          
        
        ⟩
      
    
    {\textstyle c_{\mu i}=\sum _{\nu }\langle \mu |\nu \rangle ^{-1}\langle \nu |\psi _{i}\rangle }
  
.
The basis set can either be composed of atomic orbitals (yielding the linear combination of atomic orbitals approach), which is the usual choice within the quantum chemistry community; plane waves which are typically used within the solid state community, or real-space approaches. Several types of atomic orbitals can be used: Gaussian-type orbitals, Slater-type orbitals, or numerical atomic orbitals. Out of the three, Gaussian-type orbitals are by far the most often used, as they allow efficient implementations of post-Hartree–Fock methods.

## Related

- [[Adiabatic connection fluctuation dissipation theorem]]
- [[Car–Parrinello molecular dynamics]]
- [[CHELPG]]
- [[Coulomb operator]]
- [[Distributed multipole analysis]]
- [[Energy level]]
- [[Full configuration interaction]]
- [[Görling–Levy perturbation theory]]
- [[Hamiltonian (quantum mechanics)]]
- [[Hartree equations]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Basis_set_(chemistry)