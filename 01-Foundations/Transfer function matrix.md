---
title: "Transfer function matrix"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Transfer_function_matrix"
wikipedia_categories: ["Automation", "Control engineering", "Control theory", "Frequency-domain analysis", "Matrices (mathematics)", "Signal processing", "Systems engineering", "Systems theory"]
related: ["[[Control system]]", "[[Sampled data system]]", "[[Cross Gramian]]", "[[Masreliez's theorem]]", "[[Ackermann's formula]]", "[[American Automatic Control Council]]", "[[Anticausal system]]", "[[Asymptotic gain model]]", "[[Bartels–Stewart algorithm]]", "[[Blackman's theorem]]"]
---

# Transfer function matrix

In control system theory, and various branches of engineering, a transfer function matrix, or just transfer matrix is a generalisation of the transfer functions of single-input single-output (SISO) systems to multiple-input and multiple-output (MIMO) systems.  The matrix relates the outputs of the system to its inputs.  It is a particularly useful construction for linear time-invariant (LTI) systems because it can be expressed in terms of the s-plane.
In some systems, especially ones consisting entirely of passive components, it can be ambiguous which variables are inputs and which are outputs.  In electrical engineering, a common scheme is to gather all the voltage variables on one side and all the current variables on the other regardless of which are inputs or outputs.  This results in all the elements of the transfer matrix being in units of impedance.  The concept of impedance (and hence impedance matrices) has been borrowed into other energy domains by analogy, especially mechanics and acoustics.
Many control systems span several different energy domains.  This requires transfer matrices with elements in mixed units.  This is needed both to describe transducers that make connections between domains and to describe the system as a whole.  If the matrix is to properly model energy flows in the system, compatible variables must be chosen to allow this.

## Related

- [[Control system]]
- [[Sampled data system]]
- [[Cross Gramian]]
- [[Masreliez's theorem]]
- [[Ackermann's formula]]
- [[American Automatic Control Council]]
- [[Anticausal system]]
- [[Asymptotic gain model]]
- [[Bartels–Stewart algorithm]]
- [[Blackman's theorem]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Transfer_function_matrix