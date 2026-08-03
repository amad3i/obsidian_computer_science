---
title: "Davidson correction"
tags: ["cs", "hci-interdisciplinary", "intermediate"]
domain: HCI & Interdisciplinary
level: intermediate
source: "https://en.wikipedia.org/wiki/Davidson_correction"
wikipedia_categories: ["Computational chemistry"]
related: ["[[1s Slater-type function]]", "[[Ab initio quantum chemistry methods]]", "[[Accessible surface area]]", "[[Activation strain model]]", "[[Adaptive sampling]]", "[[Adiabatic connection fluctuation dissipation theorem]]", "[[Alexander Boldyrev]]", "[[Basis set (chemistry)]]", "[[Bette Korber]]", "[[Bond order potential]]"]
---

# Davidson correction

The Davidson correction is an energy correction often applied in calculations using the method of truncated configuration interaction, which is one of several post-Hartree–Fock ab initio quantum chemistry methods in the field of computational chemistry. It was introduced by Ernest R. Davidson.
It allows one to estimate the value of the full configuration interaction energy from a limited configuration interaction expansion result, although more precisely it estimates the energy of configuration interaction up to quadruple excitations (CISDTQ) from the energy of configuration interaction up to double excitations (CISD). It uses the formula

  
    
      
        Δ
        
          E
          
            Q
          
        
        (
        1
        
          a
          
            0
          
          
            2
          
        
        (
        
          E
          
            
              C
              I
              S
              D
            
          
        
        
          E
          
            
              H
              F
            
          
        
        ,
         
      
    
    
  

  
    
      
        
          E
          
            
              C
              I
              S
              D
              T
              Q
            
          
        
        ≈
        
          E
          
            
              C
              I
              S
              D
            
          
        
        Δ
        
          E
          
            Q
          
        
        ,
         
      
    
    
  

where a0 is the coefficient of the Hartree–Fock wavefunction in the CISD expansion, ECISD and EHF are the energies of the CISD and Hartree–Fock wavefunctions respectively, and ΔEQ is the correction to estimate ECISDTQ, the energy of the CISDTQ wavefunction.  Such estimation is based on perturbation theory analysis. Therefore, CISD calculations with the Davidson correction included are frequently referred to as CISD(Q).

## Related

- [[1s Slater-type function]]
- [[Ab initio quantum chemistry methods]]
- [[Accessible surface area]]
- [[Activation strain model]]
- [[Adaptive sampling]]
- [[Adiabatic connection fluctuation dissipation theorem]]
- [[Alexander Boldyrev]]
- [[Basis set (chemistry)]]
- [[Bette Korber]]
- [[Bond order potential]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Davidson_correction