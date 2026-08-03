---
title: "Jordan normal form"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Jordan_normal_form"
wikipedia_categories: ["Linear algebra", "Matrix decompositions", "Matrix normal forms", "Matrix theory"]
related: ["[[Weyr canonical form]]", "[[Singular value decomposition]]", "[[Adjugate matrix]]", "[[Amitsur–Levitzki theorem]]", "[[Annihilating polynomial]]", "[[Bendixson's inequality]]", "[[Block LU decomposition]]", "[[Change of basis]]", "[[Computing the permanent]]", "[[Determinant]]"]
---

# Jordan normal form

In linear algebra, a Jordan normal form, also known as a Jordan canonical form,
is an upper triangular matrix of a particular form called a Jordan matrix representing a linear operator on a finite-dimensional vector space with respect to some basis. Such a matrix has each non-zero off-diagonal entry equal to 1, immediately above the main diagonal (on the superdiagonal), and with identical diagonal entries to the left and below them.
Let V be a vector space over a field K. Then a basis with respect to which the matrix representing the operator has the required form exists if and only if all eigenvalues of the operator lie in K, or equivalently if the characteristic polynomial of the operator splits into linear factors over K. This condition is always satisfied if K is algebraically closed (for instance, if it is the field of complex numbers). The diagonal entries of the normal form are the eigenvalues (of the operator), and the number of times each eigenvalue occurs is called the algebraic multiplicity of the eigenvalue.
If the operator is originally given by a square matrix M, then its Jordan normal form is also called the Jordan normal form of M. Any square matrix has a Jordan normal form if the field of coefficients is extended to one containing all the eigenvalues of the matrix. In spite of its name, the normal form for a given M is not entirely unique, as it is a block diagonal matrix formed of Jordan blocks, the order of which is not fixed; it is conventional to group blocks for the same eigenvalue together, but no ordering is imposed among the eigenvalues, nor among the blocks for a given eigenvalue, although the latter could for instance be ordered by weakly decreasing size.
The Jordan–Chevalley decomposition is particularly simple with respect to a basis for which the operator takes its Jordan normal form. The diagonal form for diagonalizable matrices, for instance normal matrices, is a special case of the Jordan normal form.
The Jordan normal form is named after Camille Jordan, who first stated the Jordan decomposition theorem in 1870.

## Related

- [[Weyr canonical form]]
- [[Singular value decomposition]]
- [[Adjugate matrix]]
- [[Amitsur–Levitzki theorem]]
- [[Annihilating polynomial]]
- [[Bendixson's inequality]]
- [[Block LU decomposition]]
- [[Change of basis]]
- [[Computing the permanent]]
- [[Determinant]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Jordan_normal_form