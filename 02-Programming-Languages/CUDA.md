---
title: "CUDA"
tags: ["cs", "programming-languages", "core"]
domain: Programming & Languages
level: core
source: "https://en.wikipedia.org/wiki/CUDA"
wikipedia_categories: ["Computer physics engines", "GPGPU", "GPGPU libraries", "Graphics cards", "Graphics hardware", "Nvidia software", "Parallel computing", "Programming languages created in 2007"]
related: ["[[General-purpose computing on graphics processing units]]", "[[ROCm]]", "[[Nvidia Tesla]]", "[[OpenCL]]", "[[Tesla (microarchitecture)]]", "[[AMD Instinct]]", "[[C++ AMP]]", "[[Graphics Core Next]]", "[[Graphics processing unit]]", "[[IWOCL]]"]
---

# CUDA

CUDA (Compute Unified Device Architecture) is a proprietary parallel computing platform and application programming interface (API) developed by Nvidia that allows software to use certain types of graphics processing units (GPUs) for accelerated general-purpose processing, significantly broadening their utility in artificial intelligence, scientific and high-performance computing. CUDA was created in 2004 and was officially released in 2007. When introduced, the name was an acronym for Compute Unified Device Architecture, but Nvidia later dropped the initial meaning of the acronym and now rarely expands it.
CUDA is both a software layer that manages data, giving direct access to the GPU and CPU as necessary, and a library of APIs that enable parallel computation. In addition to drivers and runtime kernels, the CUDA platform includes compilers, libraries and developer tools to help programmers.
CUDA is written in the C programming language, but is designed to work with other programming languages including C++, Fortran, Python and Julia. This accessibility makes it easier for specialists in parallel programming to use GPU resources, in contrast to prior APIs like Direct3D and OpenGL, which require advanced skills in graphics programming. CUDA-powered GPUs support programming frameworks such as OpenMP, OpenACC and OpenCL.

== Graphics processing unit ==

The graphics processing unit (GPU) is a specialized processor. It addresses the demands of real-time high-resolution, compute-intensive tasks such as 3D graphics. By 2012, GPUs had evolved into highly parallel multi-core systems allowing efficient manipulation of large blocks of data. This design is more effective than general-purpose central processing unit (CPUs) for algorithms in situations where processing large blocks of data is done in parallel, such as:

cryptographic hash functions
machine learning
molecular dynamics simulations
physics engines

== History ==
CUDA traces to the early 2000s, when Ian Buck, a computer science PhD student at Stanford University, began experimenting with using GPUs for purposes beyond rendering graphics. Buck had become interested in GPUs during his undergraduate studies at Princeton University, initially through video gaming. After graduation, he interned at Nvidia, gaining deeper exposure to GPU architecture. At Stanford, he built an 8K gaming rig using 32 GeForce graphics cards, originally to push the limits of graphics performance in games like Quake and Doom. However, his interests shifted toward exploring the potential of GPUs for general-purpose parallel computing.
To that end, Buck developed Brook, a programming language designed to enable general-purpose computing on GPUs. His work attracted support from Nvidia and the Defense Advanced Research Projects Agency (DARPA). In 2004, Nvidia hired Buck and paired him with John Nickolls, then director of architecture for GPU computing. Together, they began transforming Brook into CUDA. CUDA was officially released in 2007.
CUDA became central to the company's strategy of positioning GPUs as versatile hardware for scientific applications. By 2015, CUDA's development increasingly focused on accelerating machine learning and artificial neural network workloads.

== Ontology ==
The following table offers an approximate summary of the CUDA ontology.

== Programming abilities ==

The CUDA platform is accessible to software developers through CUDA-accelerated libraries, compiler directives such as OpenACC, and extensions to industry-standard programming languages including C, C++, Fortran and Python. C/C++ programmers can use 'CUDA C/C++', compiled to PTX with nvcc (Nvidia's LLVM-based C/C++ compiler) or by clang itself. Fortran programmers can use 'CUDA Fortran', compiled with the PGI CUDA Fortran compiler from The Portland Group. Python programmers can use the cuPyNumeric library to accelerate applications on Nvidia GPUs.
In addition to libraries, compiler directives, CUDA C/C++ and CUDA Fortran, the CUDA platform supports other computational interfaces, including the Khronos Group's OpenCL, Microsoft's DirectCompute, OpenGL Compute Shader and C++ AMP. Third party wrappers are also available for Python, Perl, Fortran, Java, Ruby, Lua, Common Lisp, Haskell, R, MATLAB, IDL, Julia, and native support in Mathematica.
In the computer game industry, GPUs are used for graphics rendering, and for game physics calculations (physical effects such as debris, smoke, fire, fluids); examples include PhysX and Bullet. CUDA has also been used to accelerate non-graphical applications in computational biology, cryptography and other fields by an order of magnitude or more.
CUDA provides both a low level API (CUDA Driver API, non single-source) and a higher level API (CUDA Runtime API, single-source). The initial CUDA SDK was made public on 15 February 2007, for Microsoft Windows and Linux. Mac OS X support was later added in version 2.0, which supersedes the beta released February 14, 2008. CUDA works with all Nvidia GPUs from the G8x series onwards, including GeForce, Quadro and the Tesla line. CUDA is compatible with most standard operating systems.
CUDA 8.0 comes with the following libraries (for compilation & runtime, in alphabetical order):

cuBLAS – CUDA Basic Linear Algebra Subroutines library
CUDART – CUDA Runtime library
cuFFT – CUDA Fast Fourier Transform library
cuRAND – CUDA Random Number Generation library
cuSOLVER – CUDA based collection of dense and sparse direct solvers
cuSPARSE – CUDA Sparse Matrix library
NPP – NVIDIA Performance Primitives library
nvGRAPH – NVIDIA Graph Analytics library
NVML – NVIDIA Management Library
NVRTC – NVIDIA Runtime Compilation library for CUDA C++
CUDA 8.0 comes with these other software components:

nView – NVIDIA nView Desktop Management Software
NVWMI – NVIDIA Enterprise Management Toolkit
GameWorks PhysX – is a multi-platform game physics engine
CUDA 9.0–9.2 comes with these other components:

CUTLASS 1.0 – custom linear algebra algorithms,
NVIDIA Video Decoder was deprecated in CUDA 9.2; it is now available in NVIDIA Video Codec SDK
CUDA 10 comes with these other components:

nvJPEG – Hybrid (CPU and GPU) JPEG processing
CUDA 11.0–11.8 comes with these other components:

CUB is new one of more supported C++ libraries
MIG multi instance GPU support
nvJPEG2000 – JPEG 2000 encoder and decoder

== Advantages ==
CUDA has several advantages over traditional general-purpose computation on GPUs (GPGPU) using graphics APIs:

Scattered reads – code can read from arbitrary addresses in memory
Unified virtual memory (CUDA 4.0 and above)
Unified memory (CUDA 6.0 and above)
Shared memory – CUDA exposes a fast shared memory region that can be shared among threads. This can be used as a user-managed cache, enabling higher bandwidth than is possible using texture lookups.
Faster downloads and readbacks to and from the GPU
Full support for integer and bitwise operations, including integer texture lookups

== Limitations ==
Whether for the host computer or the GPU device, all CUDA source code is now processed according to C++ syntax rules. This was not always the case. Earlier versions of CUDA were based on C syntax rules. As with the more general case of compiling C code with a C++ compiler, it is therefore possible that old C-style CUDA source code will either fail to compile or will not behave as originally intended.
Interoperability with rendering languages such as OpenGL is one-way, with OpenGL having access to registered CUDA memory but CUDA not having access to OpenGL memory.
Copying between host and device memory may incur a performance hit due to system bus bandwidth and latency (this can be partly alleviated with asynchronous memory transfers, handled by the GPU's DMA engine).
Threads should be running in groups of at least 32 for best performance, with total number of threads numbering in the thousands. Branches in the program code do not affect performance significantly, provided that each of 32 threads takes the same execution path; the SIMD execution model becomes a significant limitation for any inherently divergent task (e.g. traversing a space partitioning data structure during ray tracing).
No emulation or fallback functionality is available for modern revisions.
Valid C++ may sometimes be flagged and prevent compilation due to the way the compiler approaches optimization for target GPU device limitations.
C++ run-time type information (RTTI) and C++-style exception handling are only supported in host code, not in device code.
In single-precision on first generation CUDA compute capability 1.x devices, denormal numbers are unsupported and are instead flushed to zero, and the precision of both the division and square root operations are slightly lower than IEEE 754-compliant single precision math. Devices that support compute capability 2.0 and above support denormal numbers, and the division and square root operations are IEEE 754 compliant by default. Howeve

*(note truncated for size; full article at the source link below)*

## Related

- [[General-purpose computing on graphics processing units]]
- [[ROCm]]
- [[Nvidia Tesla]]
- [[OpenCL]]
- [[Tesla (microarchitecture)]]
- [[AMD Instinct]]
- [[C++ AMP]]
- [[Graphics Core Next]]
- [[Graphics processing unit]]
- [[IWOCL]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/CUDA