---
title: "C++ AMP"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/C++_AMP"
wikipedia_categories: ["C++ libraries", "GPGPU libraries", "Parallel computing"]
related: ["[[Algorithmic skeleton]]", "[[CUDA]]", "[[HPX]]", "[[OpenCL]]", "[[ABIT BP6]]", "[[Advanced Synchronization Facility]]", "[[Aiyara cluster]]", "[[Alewife (multiprocessor)]]", "[[All nearest smaller values]]", "[[All-to-all (parallel pattern)]]"]
---

# C++ AMP

C++ Accelerated Massive Parallelism (C++ AMP) is a native programming model that contains elements that span the C++ programming language and its runtime library. It provides an easy way to write programs that compile and execute on data-parallel hardware, such as graphics cards and graphics processing units (GPUs).
Starting in Visual Studio 2022 (version 17.0), C++ AMP is declared as deprecated, indicating its end of support beyond Visual Studio 2022.
C++ AMP is a library implemented on DirectX 11 and an open specification from Microsoft for implementing data parallelism directly in C++. It is intended to make programming GPUs easy for the developer by supporting a range of expertise from none (in which case the system does its best) to being more finely controllable, but still portable. In Microsoft's implementation, code that cannot be run on GPUs will fall back onto one or more CPUs instead and use SSE instructions. The Microsoft implementation is included in Visual Studio 2012, including debugger and profiler support.
The initial C++ AMP release from Microsoft requires at least Windows 7 or Windows Server 2008 R2. As C++ AMP is an open specification, in time, implementations outside Microsoft should appear. One early example of this is Shevlin Park, Intel's experimental implementation of C++ AMP on Clang–LLVM and Open Computing Language (OpenCL).
On November 12, 2013 the HSA Foundation announced a C++ AMP compiler that outputs to OpenCL, Standard Portable Intermediate Representation (SPIR), and HSA Intermediate Language (HSAIL) supporting the current C++ AMP specification. The source is available at https://github.com/RadeonOpenCompute/hcc. C++ AMP support is considered obsolete and the current ROCm 1.9 series will be the last to support it.
The basic concepts behind C++AMP, like using C++ classes to express parallel and heterogeneous programming features, have been inspirational to the SYCL standard.

## Related

- [[Algorithmic skeleton]]
- [[CUDA]]
- [[HPX]]
- [[OpenCL]]
- [[ABIT BP6]]
- [[Advanced Synchronization Facility]]
- [[Aiyara cluster]]
- [[Alewife (multiprocessor)]]
- [[All nearest smaller values]]
- [[All-to-all (parallel pattern)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/C++_AMP