---
title: "Singular value decomposition"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Singular_value_decomposition"
wikipedia_categories: ["Functional analysis", "Linear algebra", "Matrix decompositions", "Matrix theory", "Numerical linear algebra", "Singular value decomposition"]
related: ["[[Eigenvalues and eigenvectors]]", "[[Jordan normal form]]", "[[Kernel (linear algebra)]]", "[[Orthogonal Procrustes problem]]", "[[Spectral theorem]]", "[[Weyr canonical form]]", "[[Adjugate matrix]]", "[[Amitsur–Levitzki theorem]]", "[[Annihilating polynomial]]", "[[Antiunitary operator]]"]
---

# Singular value decomposition

In linear algebra, the singular value decomposition (SVD) is a factorization of a real or complex matrix into a rotation, followed by a scaling, followed by another rotation. It generalizes the eigendecomposition of a square normal matrix with an orthonormal eigenbasis to any ⁠
  
    
      
        m
        n
      
    
    
  
⁠ matrix. It is related to the polar decomposition, and is a common means for implementing low-rank approximation for matrices.
Specifically, the singular value decomposition of an 
  
    
      
        m
        n
      
    
    
  
 complex matrix ⁠
  
    
      
        
          M
        
      
    
    
  
⁠ is a factorization of the form ⁠
  
    
      
        
          M
        
        
          U
        
        
          Σ
        
        
          
            V
          
          
          
        
      
    
    
  
⁠, where ⁠
  
    
      
        
          U
        
      
    
    
  
⁠ is an ⁠
  
    
      
        m
        m
      
    
    
  
⁠ complex unitary matrix, 
  
    
      
        
          Σ
        
      
    
    
  
 is an 
  
    
      
        m
        n
      
    
    
  
 rectangular diagonal matrix with non-negative real numbers on the diagonal, ⁠
  
    
      
        
          V
        
      
    
    
  
⁠ is an 
  
    
      
        n
        n
      
    
    
  
 complex unitary matrix, and ⁠
  
    
      
        
          
            V
          
          
          
        
      
    
    
  
⁠ is the conjugate transpose of ⁠
  
    
      
        
          V
        
      
    
    
  
⁠. Such decompositions always exist for any complex matrix. If ⁠
  
    
      
        
          M
        
      
    
    
  
⁠ is real, then some ⁠
  
    
      
        
          U
        
      
    
    
  
⁠ and ⁠
  
    
      
        
          V
        
      
    
    
  
⁠ can be found which are real (orthogonal) matrices; a real-valued SVD is often denoted ⁠
  
    
      
        
          U
        
        
          Σ
        
        
          
            V
          
          
            
              T
            
          
        
      
    
    
  
⁠, where ⁠
  
    
      
        
          
            V
          
          
            
              T
            
          
        
      
    
    
  
⁠ is the transpose of ⁠
  
    
      
        
          V
        
      
    
    
  
⁠.
The diagonal entries 
  
    
      
        
          σ
          
            i
          
        
        
          
            Σ
          
          
            i
            ,
            i
          
        
      
    
    
  
 of 
  
    
      
        
          Σ
        
      
    
    
  
 are uniquely determined by ⁠
  
    
      
        
          M
        
      
    
    
  
⁠, up to reordering, and are known as the singular values of ⁠
  
    
      
        
          M
        
      
    
    
  
⁠. Conventionally they are arranged in descending order (from largest to smallest), which uniquely determines ⁠
  
    
      
        
          Σ
        
      
    
    
  
⁠. The number of non-zero singular values, allowing repetitions, is equal to ⁠
  
    
      
        r
      
    
    
  
⁠, the rank of ⁠
  
    
      
        
          M
        
      
    
    
  
⁠.
The columns of ⁠
  
    
      
        
          U
        
      
    
    
  
⁠ and the columns of ⁠
  
    
      
        
          V
        
      
    
    
  
⁠ are called left-singular vectors and right-singular vectors of ⁠
  
    
      
        
          M
        
      
    
    
  
⁠, respectively. They form two orthonormal bases, ⁠
  
    
      
        
          
            u
          
          
            1
          
        
        ,
        …
        ,
        
          
            u
          
          
            m
          
        
      
    
    
  
⁠ and ⁠
  
    
      
        
          
            v
          
          
            1
          
        
        ,
        …
        ,
        
          
            v
          
          
            n
          
        
      
    
    
  
⁠. In general the SVD is not unique, with certain unitary transformations of ⁠
  
    
      
        
          U
        
      
    
    
  
⁠ and ⁠
  
    
      
        
          V
        
      
    
    
  
⁠ producing valid alternative decompositions.
The term SVD sometimes refers to the compact SVD, a similar decomposition ⁠
  
    
      
        
          M
        
        
          
            U
          
          
            r
          
        
        
          
            Σ
          
          
            r
          
        
        
          
            V
          
          
            r
          
          
          
        
      
    
    
  
⁠, in which ⁠
  
    
      
        
          
            Σ
          
          
            r
          
        
      
    
    
  
⁠ is an ⁠
  
    
      
        r
        r
      
    
    
  
⁠ matrix with only the non-zero singular values (allowing repetitions) on its main diagonal. In this variant, ⁠
  
    
      
        
          
            U
          
          
            r
          
        
      
    
    
  
⁠ is an ⁠
  
    
      
        m
        r
      
    
    
  
⁠ semi-unitary matrix whose columns ⁠
  
    
      
        
          
            u
          
          
            1
          
        
        ,
        …
        ,
        
          
            u
          
          
            r
          
        
      
    
    
  
⁠ span the columns of ⁠
  
    
      
        
          M
        
      
    
    
  
⁠, and 
  
    
      
        
          
            V
          
          
            r
          
        
      
    
    
  
 is an ⁠
  
    
      
        n
        r
      
    
    
  
⁠ semi-unitary matrix whose columns ⁠
  
    
      
        
          
            v
          
          
            1
          
        
        ,
        …
        ,
        
          
            v
          
          
            r
          
        
      
    
    
  
⁠ span the columns of ⁠
  
    
      
        
          
            M
          
          
          
        
        
      
    
    
  
⁠.
The SVD (with sorted singular values) splits ⁠
  
    
      
        
          M
        
      
    
    
  
⁠ into a sum of ⁠
  
    
      
        r
      
    
    
  
⁠ rank-⁠
  
    
      
        1
      
    
    
  
⁠ matrices, 
  
    
      
        
          
            M
          
          
            σ
            
              1
            
          
          
            
              u
            
            
              1
            
          
          
            
              v
            
            
              1
            
            
            
          
          
            σ
            
              2
            
          
          
            
              u
            
            
              2
            
          
          
            
              v
            
            
              2
            
            
            
          
          ⋯
          
            σ
            
              r
            
          
          
            
              u
            
            
              r
            
          
          
            
              v
            
            
              r
            
            
            
          
          
        
      
    
    
  
.
Mathematical applications of the SVD include computing the pseudoinverse, matrix approximation, and determining the rank, range, and null space of a matrix. The SVD is also extremely useful in many areas of science, engineering, and statistics, such as signal processing, least squares fitting of data, and process control.

*(note truncated for size; full article at the source link below)*

## Related

- [[Eigenvalues and eigenvectors]]
- [[Jordan normal form]]
- [[Kernel (linear algebra)]]
- [[Orthogonal Procrustes problem]]
- [[Spectral theorem]]
- [[Weyr canonical form]]
- [[Adjugate matrix]]
- [[Amitsur–Levitzki theorem]]
- [[Annihilating polynomial]]
- [[Antiunitary operator]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Singular_value_decomposition