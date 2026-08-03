---
title: "Livermore loops"
tags: ["cs", "hpc-parallel", "intermediate"]
domain: HPC & Parallel
level: intermediate
source: "https://en.wikipedia.org/wiki/Livermore_loops"
wikipedia_categories: ["Parallel computing", "Supercomputer benchmarks"]
related: ["[[HPCG benchmark]]", "[[ABIT BP6]]", "[[Advanced Synchronization Facility]]", "[[Aiyara cluster]]", "[[Alewife (multiprocessor)]]", "[[Algorithmic skeleton]]", "[[All nearest smaller values]]", "[[All-to-all (parallel pattern)]]", "[[AMD Instinct]]", "[[Amorphous computing]]"]
---

# Livermore loops

Livermore loops (also known as the Livermore Fortran kernels or LFK) is a benchmark for parallel computers. It was created by Francis H. McMahon from scientific source code run on computers at Lawrence Livermore National Laboratory. It consists of 24 do loops, some of which can be vectorized, and some of which cannot. 
The benchmark was published in 1986 in Livermore fortran kernels: A computer test of numerical performance range.
The Livermore loops were originally written in Fortran, but have since been ported to many programming languages. 
Each loop carries out a different mathematical kernel
.
Those kernels 
are:

hydrodynamics fragment
incomplete Cholesky conjugate gradient
inner product
banded linear systems solution
tridiagonal linear systems solution
general linear recurrence equations
equation of state fragment
alternating direction implicit integration
integrate predictors
difference predictors
first sum
first difference
2-D particle in a cell
1-D particle in a cell
casual Fortran
Monte Carlo search
implicit conditional computation
2-D explicit hydrodynamics fragment
general linear recurrence equations
discrete ordinates transport
matrix-matrix transport
Planckian distribution
2-D implicit hydrodynamics fragment
location of a first array minimum.

## Related

- [[HPCG benchmark]]
- [[ABIT BP6]]
- [[Advanced Synchronization Facility]]
- [[Aiyara cluster]]
- [[Alewife (multiprocessor)]]
- [[Algorithmic skeleton]]
- [[All nearest smaller values]]
- [[All-to-all (parallel pattern)]]
- [[AMD Instinct]]
- [[Amorphous computing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Livermore_loops