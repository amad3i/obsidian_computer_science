---
title: "OpenACC"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/OpenACC"
wikipedia_categories: ["Application programming interfaces", "C programming language family", "Fortran", "Parallel computing", "Standards"]
related: ["[[OpenHMPP]]", "[[OpenMP]]", "[[ISP Formal Verification Tool]]", "[[Message Passing Interface]]", "[[OpenCL]]", "[[Portals network programming application programming interface]]", "[[SHMEM]]", "[[Unified Parallel C]]", "[[ABIT BP6]]", "[[Advanced Synchronization Facility]]"]
---

# OpenACC

OpenACC (for open accelerators) is a programming standard for parallel computing developed by Cray, CAPS, Nvidia and PGI. The standard is designed to simplify parallel programming of heterogeneous CPU/GPU systems.
As in OpenMP, the programmer can annotate C, C++ and Fortran source code to identify the areas that should be accelerated using compiler directives and additional functions. Like OpenMP 4.0 and newer, OpenACC can target both the CPU and GPU architectures and launch computational code on them.
OpenACC members have worked as members of the OpenMP standard group to merge into OpenMP specification to create a common specification which extends OpenMP to support accelerators in a future release of OpenMP. These efforts resulted in a technical report for comment and discussion timed to include the annual Supercomputing Conference (November 2012, Salt Lake City) and to address non-Nvidia accelerator support with input from hardware vendors who participate in OpenMP.
At ISC’12 OpenACC was demonstrated to work on Nvidia, AMD and Intel accelerators, without performance data.
On November 12, 2012, at the SC12 conference, a draft of the OpenACC version 2.0 specification was presented. New suggested capabilities include new controls over data movement (such as better handling of unstructured data and improvements in support for non-contiguous memory), and support for explicit function calls and separate compilation (allowing the creation and reuse of libraries of accelerated code). OpenACC 2.0 was officially released in June 2013.
Version 2.5 of the specification was released in October 2015, while version 2.6 was released in November 2017. Subsequently, version 2.7 was released in November 2018.
The latest version is version 3.3, which was released in November 2022.

## Related

- [[OpenHMPP]]
- [[OpenMP]]
- [[ISP Formal Verification Tool]]
- [[Message Passing Interface]]
- [[OpenCL]]
- [[Portals network programming application programming interface]]
- [[SHMEM]]
- [[Unified Parallel C]]
- [[ABIT BP6]]
- [[Advanced Synchronization Facility]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/OpenACC