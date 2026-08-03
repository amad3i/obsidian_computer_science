---
title: "Multiprocessing"
tags: ["cs", "hpc-parallel", "intermediate"]
domain: HPC & Parallel
level: intermediate
source: "https://en.wikipedia.org/wiki/Multiprocessing"
wikipedia_categories: ["Classes of computers", "Computing terminology", "Parallel computing"]
related: ["[[Amorphous computing]]", "[[Asymmetric multiprocessing]]", "[[Cellular architecture]]", "[[Computer cluster]]", "[[Fifth Generation Computer Systems]]", "[[Locale (computer hardware)]]", "[[Multiple instruction, multiple data]]", "[[Multiple instruction, single data]]", "[[Multiprocessor system architecture]]", "[[Single instruction, multiple data]]"]
---

# Multiprocessing

Multiprocessing (MP) is the use of two or more central processing units (CPUs) within one computer system. The term also refers to the ability of a system to support more than one processor or the ability to allocate tasks between them. Many variants of this basic theme exist, and the definition of multiprocessing can vary with context, mostly as a function of how a processor is defined (multi-core processors (multiple cores) on one die, multiple dies in one chip carrier (package), multiple packages in one computer case (system unit), etc.).
A multiprocessor is a computer system having two or more CPUs (processors: multiple processors) each sharing main memory and peripherals, to simultaneously process programs. A 2009 textbook defined multiprocessor system similarly, but noted that the processors may share "some or all of the system's memory and I/O facilities"; it also gave tightly coupled system as a synonymous term.
At the operating system level, multiprocessing is sometimes used to refer to the execution of multiple concurrent processes in a system, with each process running on a separate CPU or core, in contrast to one process at any one instant. When used with this definition, multiprocessing is sometimes contrasted with multitasking, which may use only one processor but switch it in time slices between tasks (i.e., a time-sharing system). In contrast, multiprocessing means true parallel execution of multiple processes using more than one processor. Multiprocessing doesn't necessarily mean that one process or task uses more than one processor simultaneously; the term parallel processing is generally used to denote that practice. Other authors prefer to refer to the operating system techniques as multiprogramming and reserve the term multiprocessing for the hardware aspect of having more than one processor. The remainder of this article discusses multiprocessing only in this hardware sense.
In Flynn's taxonomy, multiprocessors as defined above are Multiple instruction, multiple data (MIMD) machines. As the term "multiprocessor" normally refers to tightly coupled systems in which all processors share memory, multiprocessors are not the entire class of MIMD machines, which also contains message passing multicomputer systems.

## Related

- [[Amorphous computing]]
- [[Asymmetric multiprocessing]]
- [[Cellular architecture]]
- [[Computer cluster]]
- [[Fifth Generation Computer Systems]]
- [[Locale (computer hardware)]]
- [[Multiple instruction, multiple data]]
- [[Multiple instruction, single data]]
- [[Multiprocessor system architecture]]
- [[Single instruction, multiple data]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Multiprocessing