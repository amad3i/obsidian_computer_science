---
title: "MADNESS"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/MADNESS"
wikipedia_categories: ["Computational chemistry software", "Free mathematics software", "Mathematical software", "Numerical software", "Parallel computing"]
related: ["[[Maple (software)]]", "[[ILNumerics]]", "[[MATLAB]]", "[[Pipeline Pilot]]", "[[Wolfram Mathematica]]", "[[ABIT BP6]]", "[[Advanced Synchronization Facility]]", "[[Aiyara cluster]]", "[[Alewife (multiprocessor)]]", "[[Algorithmic skeleton]]"]
---

# MADNESS

MADNESS (Multiresolution Adaptive Numerical Environment for Scientific Simulation)
is a high-level software environment for the solution of integral and differential equations in many dimensions using adaptive and fast harmonic analysis methods with guaranteed precision based on multiresolution analysis
and separated representations.
There are three main components to MADNESS. At the lowest level is a petascale parallel programming environment
that aims to increases programmer productivity and code performance/scalability while maintaining backward compatibility with current programming tools such as the message-passing interface and Global Arrays. The numerical capabilities built upon the parallel tools provide a high-level environment for composing and solving numerical problems in many (1-6+) dimensions. Finally, built upon the numerical tools are new applications with initial focus upon chemistry, atomic and molecular physics,
material science, and nuclear structure.  It is open-source, has an object-oriented design, and is designed to be a parallel processing program for computers with up to millions of cores running already on the Cray XT5 at Oak Ridge National Laboratory and the IBM Blue Gene at Argonne National Laboratory.  The small matrix multiplication (relative to large, BLAS-optimized matrices) is the primary computational kernel in MADNESS; thus, an efficient implement on modern CPUs is an ongoing research effort.
Adapting the irregular computation in MADNESS to heterogeneous platforms is nontrivial due to the size of the kernel, which is too small to be offloaded via compiler directives (e.g. OpenACC), but has been demonstrated for CPU–GPU systems.
Intel has publicly stated that MADNESS is one of the codes running on the Intel MIC architecture
but no performance data has been published yet.
MADNESS' chemistry capability includes Hartree–Fock and density functional theory in chemistry
(including analytic derivatives, response properties
and time-dependent density functional theory with asymptotically corrected potentials)
as well as nuclear density functional theory
and
Hartree–Fock–Bogoliubov theory.
MADNESS and BigDFT are the two most widely known codes that perform DFT and TDDFT using wavelets.
Many-body wavefunctions requiring six-dimensional spatial representations are also implemented
(e.g. MP2).
The parallel runtime inside of MADNESS has been used to implement a wide variety of features, including graph optimization.
From a mathematical perspective, MADNESS emphasizes rigorous numerical precision without loss of computational performance. This is useful not only in quantum chemistry and nuclear physics, but also the modeling of partial differential equations.
MADNESS was recognized by the R&D 100 Awards in 2011. It is an important code to Department of Energy supercomputing sites and is being used by both the leadership computing facilities at Argonne National Laboratory
and Oak Ridge National Laboratory to evaluate the stability and performance of their latest supercomputers.  It has users around the world, including the United States and Japan.
MADNESS has been a workhorse code for computational chemistry in the DOE INCITE program
at the Oak Ridge Leadership Computing Facility
and is noted as one of the important codes to run on the Cray Cascade architecture.

## Related

- [[Maple (software)]]
- [[ILNumerics]]
- [[MATLAB]]
- [[Pipeline Pilot]]
- [[Wolfram Mathematica]]
- [[ABIT BP6]]
- [[Advanced Synchronization Facility]]
- [[Aiyara cluster]]
- [[Alewife (multiprocessor)]]
- [[Algorithmic skeleton]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/MADNESS