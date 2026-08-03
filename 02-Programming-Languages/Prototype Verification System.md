---
title: "Prototype Verification System"
tags: ["cs", "programming-languages", "advanced"]
domain: Programming & Languages
level: advanced
source: "https://en.wikipedia.org/wiki/Prototype_Verification_System"
wikipedia_categories: ["Common Lisp (programming language) software", "Dependently typed languages", "Formal specification languages", "Free software programmed in Lisp", "Free theorem provers", "Lisp (programming language)", "Logic stubs", "Programming language topic stubs"]
related: ["[[ACL2]]", "[[Language of Temporal Ordering Specification]]", "[[Lean (proof assistant)]]", "[[Matita]]", "[[NESL]]", "[[OBJ (programming language)]]", "[[Object-Z]]", "[[Rocq]]", "[[-Lisp]]", "[[A-normal form]]"]
---

# Prototype Verification System

The Prototype Verification System (PVS) is a specification language integrated with support tools and an automated theorem prover, developed at the Computer Science Laboratory of SRI International in Menlo Park, California. 
PVS is based on a kernel consisting of an extension of Church's theory of types with dependent types, and is fundamentally a classical typed higher-order logic. The base types include uninterpreted types that may be introduced by the user, and built-in types such as the booleans, integers, reals, and the ordinals.  Type-constructors include functions, sets, tuples, records, enumerations, and abstract data types. Predicate subtypes and dependent types can be used to introduce constraints; these constrained types may incur proof obligations (called type-correctness conditions or TCCs) during typechecking.  PVS specifications are organized into parameterized theories.
The system is implemented in Common Lisp, and is released under the GNU General Public License (GPL).

## Related

- [[ACL2]]
- [[Language of Temporal Ordering Specification]]
- [[Lean (proof assistant)]]
- [[Matita]]
- [[NESL]]
- [[OBJ (programming language)]]
- [[Object-Z]]
- [[Rocq]]
- [[-Lisp]]
- [[A-normal form]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Prototype_Verification_System