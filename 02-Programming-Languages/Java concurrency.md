---
title: "Java concurrency"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Java_concurrency"
wikipedia_categories: ["Concurrent computing", "Java (programming language)", "Sun Microsystems"]
related: ["[[Java (programming language)]]", "[[Actor model]]", "[[AgentSheets]]", "[[Boxing (computer programming)]]", "[[Cache coherence]]", "[[Choreographic programming]]", "[[Communicating sequential processes]]", "[[Computer cluster]]", "[[Computer multitasking]]", "[[Concurrency pattern]]"]
---

# Java concurrency

The Java programming language and the Java virtual machine (JVM) are designed to support concurrent programming. All execution takes place in the context of threads. Objects and resources can be accessed by many separate threads, with each thread with its own path of execution, but with access to any object in the program. Read and write access to objects must be properly coordinated (or "synchronized") between threads. Thread synchronization ensures that objects are modified by only one thread at a time and prevents threads from accessing partially updated objects during modification by another thread.

## Related

- [[Java (programming language)]]
- [[Actor model]]
- [[AgentSheets]]
- [[Boxing (computer programming)]]
- [[Cache coherence]]
- [[Choreographic programming]]
- [[Communicating sequential processes]]
- [[Computer cluster]]
- [[Computer multitasking]]
- [[Concurrency pattern]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Java_concurrency