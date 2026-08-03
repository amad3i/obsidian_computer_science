---
title: "Ease (programming language)"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Ease_(programming_language)"
wikipedia_categories: ["Concurrency control", "Concurrent programming languages", "Programming language topic stubs"]
related: ["[[Alef (programming language)]]", "[[JoCaml]]", "[[Joule (programming language)]]", "[[Language of Temporal Ordering Specification]]", "[[Lynx (programming language)]]", "[[MPD (programming language)]]", "[[NESL]]", "[[Newsqueak]]", "[[Occam-π]]", "[[Orc (programming language)]]"]
---

# Ease (programming language)

Ease is a general purpose parallel programming language. It is designed by Steven Ericsson-Zenith, a researcher at Yale University, the Institute for Advanced Science & Engineering in Silicon Valley, California, the Ecole Nationale Supérieure des Mines de Paris, and the Pierre and Marie Curie University, the science department of the Sorbonne.
The book Process Interaction Models is the Ease language specification. Ease combines the process constructs of communicating sequential processes (CSP) with logically shared data structures called contexts. Contexts are parallel data types that are constructed by processes and provide a way for processes to interact.
The language includes two process constructors.
A cooperation includes an explicit barrier synchronization and is written:

  
    
      
        ∥
        P
        )
        ∥
        Q
        )
        ;
      
    
    
  

If one process finishes before the other, then it will wait until the other processes are finished.
A subordination creates a process that shares the contexts that are in scope when created and finishes when complete (it does not wait for other processes) and is written:

  
    
      
        
          
            /
          
        
        
        
        
          /
        
        P
        )
        ;
      
    
    
  

Subordinate processes stop if they attempt to interact with a context that  has completed because the parent process has stopped. This enables speculative processes to be created that will finish if their result is not needed.
Powerful replication syntax allows multiple processes to be created. For example,

  
    
      
        ∥
        
          i
        
        
        
          f
          o
          r
        
        
        
          n
        
        :
        P
        i
        ;
      
    
    
  

creates n synchronized processes each with a local constant i.
Processes cannot share local variables and cooperate in the construction of shared contexts. Certain context types, called resources, ensure call-reply semantics.
There are four functions upon contexts:

read(context, variable) – copies a value from the shared context to the variable.
write(context, expression) – copies the value of expression to the shared context.
put(context, name) – moves the value bound to name to the shared context. The value of name is subsequently undefined.
get(context, name) – moves a value from context and binds it to name. The value is removed from the context.
Context types are Singletons, Bags or Streams and can be subscripted arrays.
Ease has a semiotic definition. This means that it accounts for the effect the language has on the programmer and how they develop algorithms. The language was designed to ease the developing of parallel programs.

## Related

- [[Alef (programming language)]]
- [[JoCaml]]
- [[Joule (programming language)]]
- [[Language of Temporal Ordering Specification]]
- [[Lynx (programming language)]]
- [[MPD (programming language)]]
- [[NESL]]
- [[Newsqueak]]
- [[Occam-π]]
- [[Orc (programming language)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Ease_(programming_language)