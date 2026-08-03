---
title: "Dafny"
tags: ["cs", "programming-languages", "advanced"]
domain: Programming & Languages
level: advanced
source: "https://en.wikipedia.org/wiki/Dafny"
wikipedia_categories: ["Academic programming languages", "Experimental programming languages", "Microsoft Research", "Microsoft free software", "Microsoft programming languages", "Programming languages created in 2009", "Proof assistants", "Software using the MIT license"]
related: ["[[F- (programming language)]]", "[[BitFunnel]]", "[[Orleans (software framework)]]", "[[PowerShell]]", "[[ADO.NET]]", "[[ALF (proof assistant)]]", "[[CoffeeScript]]", "[[Confidential Consortium Framework]]", "[[Curry (programming language)]]", "[[Dryad (programming)]]"]
---

# Dafny

Dafny is an imperative and functional compiled language that compiles to other programming languages, such as C#, Java, JavaScript, Go, and Python. It supports formal specification through preconditions, postconditions, loop invariants, loop variants, termination specifications and read/write framing specifications. The language combines ideas from the functional programming and imperative programming paradigms; it includes support for object-oriented programming. Features include generic classes, dynamic allocation, inductive datatypes and a variation of separation logic known as implicit dynamic frames for reasoning about side effects. Dafny was created by Rustan Leino at Microsoft Research after his prior work on developing ESC/Modula-3, ESC/Java, and Spec#. 
Dafny is regularly featured in software verification competitions (e.g. VSTTE'08, VSCOMP'10, COST'11, and VerifyThis'12).
Dafny was designed as a verification-aware programming language, requiring verification along with code development. It thus fits the Correct by Construction software development paradigm. Verification proofs are supported by a mathematical toolbox that includes mathematical integers and reals, bit-vectors, sequences, sets, multisets, infinite sequences and sets, induction, co-induction, and calculational proofs. Verification obligations are discharged automatically, given sufficient specification. Dafny uses some program analysis to infer many specification assertions, reducing the burden on the user of writing specifications. The general proof framework is that of Hoare logic.
Dafny builds on the Boogie intermediate language which uses the Z3 automated theorem prover for discharging proof obligations.

## Related

- [[F- (programming language)]]
- [[BitFunnel]]
- [[Orleans (software framework)]]
- [[PowerShell]]
- [[ADO.NET]]
- [[ALF (proof assistant)]]
- [[CoffeeScript]]
- [[Confidential Consortium Framework]]
- [[Curry (programming language)]]
- [[Dryad (programming)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Dafny