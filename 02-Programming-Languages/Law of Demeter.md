---
title: "Law of Demeter"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Law_of_Demeter"
wikipedia_categories: ["Object-oriented programming", "Programming principles"]
related: ["[[Command–query separation]]", "[[Coupling (computer programming)]]", "[[Encapsulation (computer programming)]]", "[[Information hiding]]", "[[Interface segregation principle]]", "[[Liskov substitution principle]]", "[[Open–closed principle]]", "[[SOLID]]", "[[Abstraction (computer science)]]", "[[Ambiguous viewpoint]]"]
---

# Law of Demeter

The Law of Demeter (LoD) or principle of least knowledge is a design guideline for developing software, particularly object-oriented programs. In its general form, the LoD is a specific case of loose coupling. The guideline was proposed by Ian Holland at Northeastern University towards the end of 1987, and the following three recommendations serve as a succinct summary:

Each unit should have only limited knowledge about other units: only units "closely" related to the current unit.
Each unit should only talk to its friends; don't talk to strangers.
Only talk to your immediate friends.
The fundamental notion is that a given object should assume as little as possible about the structure or properties of anything else (including its subcomponents), in accordance with the principle of "information hiding". It may be viewed as a corollary to the principle of least privilege, which dictates that a module possess only the information and resources necessary for its legitimate purpose.
It is so named for its origin in the Demeter Project, an adaptive programming and aspect-oriented programming effort. The project was named in honor of Demeter, "distribution-mother" and the Greek goddess of agriculture, to signify a bottom-up philosophy of programming which is also embodied in the law itself.

## Related

- [[Command–query separation]]
- [[Coupling (computer programming)]]
- [[Encapsulation (computer programming)]]
- [[Information hiding]]
- [[Interface segregation principle]]
- [[Liskov substitution principle]]
- [[Open–closed principle]]
- [[SOLID]]
- [[Abstraction (computer science)]]
- [[Ambiguous viewpoint]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Law_of_Demeter