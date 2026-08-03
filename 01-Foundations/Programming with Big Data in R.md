---
title: "Programming with Big Data in R"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Programming_with_Big_Data_in_R"
wikipedia_categories: ["Cross-platform free software", "Data-centric programming languages", "Data mining and machine learning software", "Free statistical software"]
related: ["[[R (programming language)]]", "[[Renjin]]", "[[Julia (programming language)]]", "[[DADiSP]]", "[[Distributed R]]", "[[Dlib]]", "[[LIBSVM]]", "[[Maple (software)]]", "[[MATLAB]]", "[[Mlpy]]"]
---

# Programming with Big Data in R

Programming with Big Data in R (pbdR) is a series of R packages and an environment for statistical computing with big data by using high-performance statistical computation. The pbdR uses the same programming language as R with S3/S4 classes and methods which is used among statisticians and data miners for developing statistical software. The significant difference between pbdR and R code is that pbdR mainly focuses on distributed memory systems, where data are distributed across several processors and analyzed in a batch mode, while communications between processors are based on MPI that is easily used in large high-performance computing (HPC) systems. R system mainly focuses on single multi-core machines for data analysis via an interactive mode such as GUI interface.
Two main implementations in R using MPI are Rmpi and pbdMPI of pbdR.

The pbdR built on pbdMPI uses SPMD parallelism where every processor is considered as worker and owns parts of data. The SPMD parallelism introduced in mid 1980 is particularly efficient in homogeneous computing environments for large data, for example, performing singular value decomposition on a large matrix, or performing clustering analysis on high-dimensional large data. On the other hand, there is no restriction to use manager/workers parallelism in SPMD parallelism environment.
The Rmpi uses manager/workers parallelism where one main processor (manager) serves as the control of all other processors (workers). The manager/workers parallelism introduced around early 2000 is particularly efficient for large tasks in small clusters, for example, bootstrap method and Monte Carlo simulation in applied statistics since i.i.d. assumption is commonly used in most statistical analysis. In particular, task pull parallelism has better performance for Rmpi in heterogeneous computing environments.
The idea of SPMD parallelism is to let every processor do the same amount of work, but on different parts of a large data set. For example, a modern GPU is a large collection of slower co-processors that can simply apply the same computation on different parts of relatively smaller data, but the SPMD parallelism ends up with an efficient way to obtain final solutions (i.e. time to solution is shorter).

## Related

- [[R (programming language)]]
- [[Renjin]]
- [[Julia (programming language)]]
- [[DADiSP]]
- [[Distributed R]]
- [[Dlib]]
- [[LIBSVM]]
- [[Maple (software)]]
- [[MATLAB]]
- [[Mlpy]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Programming_with_Big_Data_in_R