---
title: "Density matrix embedding theory"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Density_matrix_embedding_theory"
wikipedia_categories: ["Computational chemistry", "Computational chemistry stubs", "Computational physics", "Computational physics stubs", "Matrices (mathematics)", "Matrix stubs"]
related: ["[[Computational chemical methods in solid-state physics]]", "[[Intracule]]", "[[Bond order potential]]", "[[Brandt matrix]]", "[[Car–Parrinello molecular dynamics]]", "[[CCP4 (file format)]]", "[[CCPForge]]", "[[Cell lists]]", "[[Centre for Theoretical and Computational Chemistry]]", "[[Column groups and row groups]]"]
---

# Density matrix embedding theory

The density matrix embedding theory (DMET) is a numerical technique to solve strongly correlated electronic structure problems. By mapping the system to a fragment plus its entangled quantum bath, the local electron correlation effects on the fragment can be accurately modeled by a post-Hartree–Fock solver.  This method has shown high-quality results in 1D- and 2D- Hubbard models,
and in chemical model systems incorporating the fully interacting electronic Hamiltonian, including long-range interactions.

The basis of DMET is the Schmidt decomposition for quantum states, which shows that a given quantum many-body state, with macroscopically many degrees of freedom, K, can be represented exactly by an Impurity model consisting of 2N degrees of freedom for N<<K. Using an existing approximation (here called the effective lattice model) to the many-body state (for example in the mean-field approximation where correlations are neglected), DMET relates this effective lattice model to the impurity model by a one-body local potential, U. This potential is then optimised by requiring that the Density matrix of the impurity model and effective lattice model projected onto the impurity cluster match. When this matching is determined self-consistently, U thus derived in principle exactly models the correlations of the system (since the mapping from the full Hamiltonian to the impurity Hamiltonian is exact).

## Related

- [[Computational chemical methods in solid-state physics]]
- [[Intracule]]
- [[Bond order potential]]
- [[Brandt matrix]]
- [[Car–Parrinello molecular dynamics]]
- [[CCP4 (file format)]]
- [[CCPForge]]
- [[Cell lists]]
- [[Centre for Theoretical and Computational Chemistry]]
- [[Column groups and row groups]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Density_matrix_embedding_theory