---
title: "Orthogonal diagonalization"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Orthogonal_diagonalization"
wikipedia_categories: ["Linear algebra", "Linear algebra stubs"]
related: ["[[Asymmetric norm]]", "[[Eigengap]]", "[[Hamming space]]", "[[Independent equation]]", "[[K-frame]]", "[[Lapped transform]]", "[[Liouville space]]", "[[Locally finite operator]]", "[[Matrix pencil]]", "[[Mixed linear complementarity problem]]"]
---

# Orthogonal diagonalization

In linear algebra, an orthogonal diagonalization of a normal matrix (e.g. a symmetric matrix) is a diagonalization by means of an orthogonal change of coordinates.
The following is an orthogonal diagonalization algorithm that diagonalizes a quadratic form q(x) on Rn by means of an orthogonal change of coordinates X = PY.

Step 1: Find the symmetric matrix A that represents q and find its characteristic polynomial Δ(t).
Step 2: Find the eigenvalues of A, which are the roots of Δ(t).
Step 3: For each eigenvalue λ of A from step 2, find an orthogonal basis of its eigenspace.
Step 4: Normalize all eigenvectors in step 3, which then form an orthonormal basis of Rn.
Step 5: Let P be the matrix whose columns are the normalized eigenvectors in step 4.
Then X = PY is the required orthogonal change of coordinates, and the diagonal entries of PTA‍P will be the eigenvalues λ1, ..., λn that correspond to the columns of P.
Such decomposition exists by the spectral theorem.

## Related

- [[Asymmetric norm]]
- [[Eigengap]]
- [[Hamming space]]
- [[Independent equation]]
- [[K-frame]]
- [[Lapped transform]]
- [[Liouville space]]
- [[Locally finite operator]]
- [[Matrix pencil]]
- [[Mixed linear complementarity problem]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Orthogonal_diagonalization