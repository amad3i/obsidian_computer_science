---
title: "Big O notation"
tags: ["cs", "foundations-math", "core"]
domain: Foundations & Math
level: core
source: "https://en.wikipedia.org/wiki/Big_O_notation"
wikipedia_categories: ["Analysis of algorithms", "Asymptotic analysis", "Mathematical notation"]
related: ["[[Analysis of algorithms]]", "[[Best, worst and average case]]", "[[Big O in probability notation]]", "[[Bra–ket notation]]", "[[Combinatorial search]]", "[[Computational complexity]]", "[[Exponentially equivalent measures]]", "[[External memory algorithm]]", "[[Free variables and bound variables]]", "[[Glossary of mathematical symbols]]"]
---

# Big O notation

Big O notation is a mathematical notation that describes the approximate size of a function on a domain. Big O is a member of a family of notations invented by the German mathematicians Paul Bachmann and Edmund Landau and expanded by others, collectively called Bachmann–Landau notation. The letter O stands for Ordnung, that is, the order of approximation.
In computer science, big O notation is used to classify algorithms by how their run time or space requirements grow with the input. In analytic number theory, big O notation expresses bounds on the growth of an arithmetical function, as for the remainder term in the prime number theorem.
In mathematical analysis, including calculus, Big O notation bounds the error when truncating a power series and expresses the quality
of approximation of a real or complex valued function by a simpler function.
Often, big O notation characterizes functions according to their growth rates as the variable becomes large: different functions with the same asymptotic growth rate may be represented using the same O notation. The letter O is used because the growth rate of a function is also referred to as the order of the function. A description of a function in terms of big O notation only provides an upper bound on the growth rate of the function.
Associated with big O notation are several related notations, using the symbols 
  
    
      
        o
      
    
    
  
, 
  
    
      
        ∼
      
    
    
  
, 
  
    
      
        Ω
      
    
    
  
, 
  
    
      
        ≪
      
    
    
  
, 
  
    
      
        ≫
      
    
    
  
, 
  
    
      
        ≍
      
    
    
  
, 
  
    
      
        ω
      
    
    
  
, and 
  
    
      
        Θ
      
    
    
  
 to describe other kinds of bounds on growth rates. 
Bachmann proposed the notation in 1894 and Landau extended it in 1909. An earlier notation was proposed by Paul du Bois-Reymond in 1870.

== Formal definition ==
Let 
  
    
      
        f
        ,
      
    
    {\textstyle f,}
  
 the function to be estimated, be either a real or complex valued function defined on a domain 
  
    
      
        D
        ,
      
    
    {\textstyle D,}
  
 and let 
  
    
      
        g
        ,
      
    
    {\textstyle g,}
  
 the comparison function, be a non-negative real valued function defined on the same set 
  
    
      
        D
        .
      
    
    {\textstyle D.}
  
 Common choices for the domain are intervals of real numbers, bounded or unbounded, the set of positive integers, the set of complex numbers and tuples of real/complex numbers. With the domain written explicitly or understood implicitly, one writes

  
    
      
        f
        x
        =
        O
        
          
          
        
        g
        x
        
          
          
        
         
      
    
    
  

which is read as  "
  
    
      
        f
        x
      
    
    {\textstyle f(x)}
  
 is big 
  
    
      
        O
      
    
    {\textstyle O}
  
 of 
  
    
      
        g
        x
      
    
    {\textstyle g(x)}
  
"  if there exists a positive real number 
  
    
      
        M
      
    
    {\textstyle M}
  
 such that

  
    
      
        
          |
          
            f
            x
          
          |
        
        ≤
        M
         
        g
        x
        
         
        
          
             
            f
            o
            r
             
            a
            l
            l
             
          
        
         
        
        x
        ∈
        D
        .
      
    
    
  

If 
  
    
      
        g
        x
        >
        0
      
    
    
  
 (i.e. g is also never zero) throughout the domain 
  
    
      
        D
        ,
      
    
    
  
 an equivalent definition is that the ratio 
  
    
      
        
          
            
              f
              x
            
            
              g
              x
            
          
        
      
    
    {\textstyle {\frac {f(x)}{g(x)}}}
  
 is bounded, i.e. there is a positive real number 
  
    
      
        M
      
    
    
  
 so that 
  
    
      
        
          
            |
          
        
        
          
            
              f
              x
            
            
              g
              x
            
          
        
        
          
            |
          
        
        ≤
        M
      
    
    {\textstyle {\Big |}{\frac {f(x)}{g(x)}}{\Big |}\leq M}
  
 for all 
  
    
      
        x
        ∈
        D
        .
      
    
    
  
 These encompass all the uses of  big 
  
    
      
        O
      
    
    {\textstyle O}
  
  in computer science and mathematics, including its use where the domain is finite, infinite, real, complex, single variate, or multivariate. In most applications, one chooses the function 
  
    
      
        g
        x
      
    
    
  
 appearing within the argument of 
  
    
      
        O
        
          
          
        
        ⋅
        
          
          
        
      
    
    {\textstyle O{\bigl (}\cdot {\bigr )}}
  
 to be as simple a form as possible, omitting constant factors and lower order terms. The number 
  
    
      
        M
      
    
    {\textstyle M}
  
 is called the implied constant because it is normally not specified. When using big 
  
    
      
        O
      
    
    {\textstyle O}
  
 notation, what matters is that some finite 
  
    
      
        M
      
    
    
  
 exists, not its specific value. This simplifies the presentation of many analytic inequalities.
For functions defined on positive real numbers or positive integers, a more restrictive and somewhat conflicting definition
is still in common use, especially in computer science. 
When restricted to functions which are eventually positive, the notation

  
    
      
        f
        x
        =
        O
        
          
          
        
        g
        x
        
          
          
        
        
         
        
          
            a
            s
          
        
        
        x
        →
        ∞
      
    
    
  

means that for some real number 
  
    
      
        a
        ,
      
    
    {\textstyle a,}
  
 
  
    
      
        f
        x
        =
        O
        
          
          
        
        g
        x
        
          
          
        
      
    
    {\textstyle f(x)=O{\bigl (}g(x){\bigr )}}
  
 in the domain 
  
    
      
        
          
            a
            ,
            ∞
          
        
        .
      
    
    {\textstyle \left[a,\infty \right).}
  
 Here, the expression 
  
    
      
        x
        →
        ∞
      
    
    {\textstyle x\to \infty }
  
 does not indicate a limit, but the notion that the inequality holds for large enough 
  
    
      
        x
        .
      
    
    {\textstyle x.}
  
 The expression 
  
    
      
        x
        →
        ∞
      
    
    {\textstyle x\to \infty }
  
 often is omitted.
Similarly, for a real number 
  
    
      
        a
        ,
      
    
    {\textstyle a,}
  
 the notation

  
    
      
        f
        x
        =
        O
        
          
          
        
        g
        x
        
          
          
        
        
         
        
           as 
        
         
        x
        →
        a
      
    
    
  

means that for some constant 
  
    
      
        c
        0
        ,
      
    
    {\textstyle c>0,}
  
 
  
    
      
        f
        x
        =
        O
        
          
          
        
        g
        x
        
          
          
        
      
    
    {\textstyle f(x)=O{\bigl (}g(x){\bigr )}}
  
 on the interval 
  
    
      
        
          
            a
            c
            ,
            a
            c
          
        
        ;
      
    
    
  
 that is, in a small neighborhood of 
  
    
      
        a
        .
      
    
    
  

In addition, the notation

  
    
      
         
        f
        x
        =
        h
        x
        +
        O
        
          
          
        
        g
        x
        
          
          
        
         
      
    
    
  

means 
  
    
      
        f
        x
        −
        h
        x
        =
        O
        
          
          
        
        g
        x
        
          
          
        
        .
      
    
    {\textstyle f(x)-h(x)=O{\bigl (}g(x){\bigr )}.}
  
 More complicated expressions are also possible.
Despite the presence of the equal sign (=) as written, the expression 
  
    
      
        f
        x
        =
        O
        
          
          
        
        g
        x
        
          
          
        
      
    
    {\textstyle f(x)=O{\bigl (}g(x){\bigr )}}
  
 does not refer to an equality, but rather to an inequality relating 
  
    
      
        f
      
    
    {\textstyle f}
  
 and 
  
    
      
        g
        .
      
    
    {\textstyle g.}
  

In the 1930s, the Russian number theorist I.M. Vinogradov introduced the notation 
  
    
      
        ≪
        ,
      
    
    
  
 which has been increasingly used in number theory and other branches of mathematics, as an alternative to the 
  
    
      
        O
      
    
    {\textstyle O}
  
 notation. We have

  
    
      
         
        f
        ≪
        g
        
        ⟺
        
        f
        O
        
          
          
        
        g
        
          
          
        
        .
      
    
    
  

Frequently both notations are used in the same work.

=== Set version of big O ===
In computer science it is common to define big 
  
    
      
        O
      
    
    {\textstyle O}
  
 as also defining a set of functions. With the positive (or non-negative) function 
  
    
      
        g
        x
      
    
    
  
 specified, one interprets 
  
    
      
        O
        
          
          
        
        g
        x
        
          
          
        
      
    
    {\textstyle O{\bigl (}g(x){\bigr )}}
  
 as representing the set of all functions 
  
    
      
        
          
            
              f
              ~
            
          
        
      
    
    {\textstyle {\tilde {f}}}
  
 that satisfy 
  
    
      
        
          
            
              f
              ~
            
          
        
        x
        =
        O
        
          
          
        
        g
        x
        
          
          
        
        .
      
    
    {\textstyle {\tilde {f}}(x)=O{\bigl (}g(x){\bigr )}.}
  
 One can then equivalently write 
  
    
      
        f
        x
        ∈
        O
        
          
          
        
        g
        x
        
          
          
        
        ,
      
    
    {\textstyle f(x)\in O{\bigl (}g(x){\bigr )},}
  
 read as "the function 
  
    
      
         
        f
        x
         
      
    
    {\textstyle \ f(x)\ }
  
 is among the set of all functions of order at most 
  
    
      
        g
        x
        .
      
    
    {\textstyle g(x).}
  
"

== Examples with an infinite domain ==
In typical usage the 
  
    
      
        O
      
    
    
  
 notation is applied to an infinite interval of real numbers 
  
    
      
        a
        ,
        ∞
      
    
    
  
 and captures the behavior of the function for very large 
  
    
      
        x
      
    
    
  
. In this setting, the contribution of the terms that grow "most quickly" will eventually make the other ones irrelevant. As a result, the following simplification rules can be applied:

If 
  
    
      
        f
        x
      
    
    
  
 is a sum of several terms, if there is one with largest growth rate, it can be kept, and all others omitted.
If 
  
    
      
        f
        x
      
    
    
  
 is a product of several factors, any constants (factors in the product that do not depend on 
  
    
      
        x
      
    
    
  
) can be omitted.
For example, let 
  
    
      
        f
        x
        =
        6
        
          x
          
            4
          
        
        2
        
          x
          
            3
          
        
        5
      
    
    
  
, and suppose we wish to simplify this function, using 
  
    
      
        O
      
    
    
  
 notation, to describe its growth rate for large 
  
    
      
        x
      
    
    
  
. This function is the sum of three terms: 
  
    
      
        6
        
          x
          
            4
          
        
      
    
    
  
, 
  
    
      
        2
        
          x
          
            3
          
        
      
    
    
  
, and 
  
    
      
        5
      
    
    
  
. Of these three terms, the one with the highest growth rate is the one with the largest exponent as a function of 
  
    
      
        x
      
    
    
  
, namely 
  
    
      
        6
        
          x
          
            4
          
        
      
    
    
  
. Now one may apply the second rule: 
  
    
      
        6
        
          x
          
            4
          
        
      
    
    
  
is a product of 
  
    
      
        6
      
    
    
  
 and 
  
    
      
        
          x
          
            4
          
        
      
    
    
  
 in which the first factor does not depend on 
  
    
      
        x
      
    
    
  
. Omitting this factor results in the simplified form 
  
    
      
        
          x
          
            4
          
        
      
    
    
  
. Thus, we say that 
  
    
      
        f
        x
      
    
    
  
 is a "big O" of 
  
    
      
        
          x
          
            4
          
        
      
    
    
  
. Mathematically, we can write 
  
    
      
        f
        x
        =
        O
        
          x
          
            4
          
        
      
    
    
  
 for all 
  
    
      
        x
        ≥
        1
      
    
    
  
. One may confirm this calculation using the formal definition: let 
  
    
      
        f
        x
        =
        6
        
          x
          
            4
          
        
        2
        
          x
          
            3
          
        
        5
      
    
    
  
 and 
  
    
      
        g
        x
        =
        
          x
          
            4
          
        
      
    
    
  
. Applying the formal definition from above, the statement that 
  
    
      
        f
        x
        =
        O
        
          x
          
            4
          
        
      
    
    
  
 is equivalent to its expansion,

  
    
      
        
          |
        
        f
        x
        
          |
        
        ≤
        M
        
          x
          
            4
          
        
      
    
    
  

for some suitable choice of a positive real number 
  
    
      
        M
      
    
    
  
 and for all 
  
    
      
        x
        ≥
        1
      
    
    
  
. To prove this, let 
  
    
      
        M
        13
      
    
    
  
. Then, for all 
  
    
      
        x
        ≥
        1
      
    
    
  
:

  
    
      
        
          
            
              
                
                  |
                
                6
                
                  x
                  
                    4
                  
                
                2
                
                  x
                  
                    3
                  
                
                5
                
                  |
                
              
              
                
                ≤
                6
                
                  x
                  
                    4
                  
                
                
                  |
                
                2
                
                  x
                  
                    3
                  
                
                
                  |
                
                5
              
            
            
              
              
                
                ≤
                6
                
                  x
                  
                    4
                  
                
                2
                
                  x
                  
                    4
                  
                
                5
                
                  x
                  
                    4
                  
                
              
            
            
              
              
                
                13
                
                  x
                  
                    4
                  
                
              
            
          
        
      
    
    
  

so

  
    
      
        
          |
        
        6
        
          x
          
            4
          
        
        2
        
          x
          
            3
          
        
        5
        
          |
        
        ≤
        13
        
          x
          
            4
          
        
        .
      
    
    
  

While it is also true, by the same argument, that

  
    
      
        f
        x
        =
        O
        
          x
          
            10
          
        
      
    
    
  
, this is a less precise
approximation of the function 
  
    
      
        f
      
    
    
  
.
On the other hand, the statement 
  
    
      
        f
        x
        =
        O
        
          x
          
            3
          
        
      
    
    
  
 is false, because the term 
  
    
      
        6
        
          x
          
            4
          
        
      
    
    
  
 causes

  
    
      
        f
        x
        
          /
        
        
          x
          
            3
          
        
      
    
    
  
 to be unbounded.
When a function 
  
    
      
        T
        n
      
    
    
  
 describes the number
of steps required in an algorithm with input 
  
    
      
        n
      
    
    
  
, an expression such as 

  
    
      
        T
        n
        =
        O
        
          n
          
            2
          
        
      
    
    
  

with the implied domain being the set of positive integers, may be interpreted as saying that the algorithm has at most the order of 
  
    
      
        
          n
          
            2
          
        
      
    
    
  
 time complexity.

== Example with a finite domain ==
Big O can also be used to describe the error term in an approximation to a mathematical function on a finite interval. The most significant terms are written explicitly, and then the least-significant terms are summarized in a single big O term. Consider, for example, the exponential series and two expressions of it that are valid when 
  
    
      
        x
      
    
    
  
 is small:

  
    
      
        
          
            
              
                
                  e
                  
                    x
                  
                
              
              
                
                1
                x
                
                  
                    
                      
                      
                        x
                        
                          2
                        
                      
                       
                    
                    
                      2
                      !
                    
                  
                
                
                  
                    
                      
                      
                        x
                        
                          3
                        
                      
                       
                    
                    
                      3
                      !
                    
                  
                
                
                  
                    
                      
                      
                        x
                        
                          4
                        
                      
                       
                    
                    
                      4
                      !
                    
                  
                
                ⋯
              
              
              
                
                   for all finite 
                
                x
              
            
            
              
              
                
                1
                x
                
                  
                    
                      
                      
                        x
                        
                          2
                        
                      
                       
                    
                    2
                  
                
                O
                
                  |
                
                x
                
                  
                    |
                  
                  
                    3
                  
                
              
              
              
                
                   for all 
                
                
                  |
                
                x
                
                  |
                
                ≤
                1
              
            
            
              
              
                
                1
                x
                O
                
                  x
                  
                    2
                  
                
              
              
              
                
                   for all 
                
                
                  |
                
                x
                
                  |
                
                ≤
                1.
              
            
          
        
      
    
    
  

The middle expression (the line with "
  
    
      
        O
        
          |
        
        
          x
          
            3
          
        
        
          |
        
      
    
    
  
") means the absolute-value of the error 

  
    
      
         
        
          e
          
            x
          
        
        (
        1
        x
        
          
            
              
              
                x
                
                  2
                
              
               
            
            2
          
        
         
      
    
    
  
 is at most some constant times 
  
    
      
         
        
          |
        
        
          x
          
            3
          
        
        
          |
        
         
      
    
    
  
 when 
  
    
      
         
        x
         
      
    
    
  
 is small.
This is an example of the use of Taylor's theorem.
The behavior of a given function may be very different on finite domains than on infinite domains, for example,

  
    
      
        x
        1
        
          
            8
          
        
        
          x
          
            8
          
        
        O
        
          x
          
            7
          
        
        
        
           for 
        
        x
        ≥
        1
      
    
    
  

while

  
    
      
        x
        1
        
          
            8
          
        
        1
        8
        x
        O
        
          x
          
            2
          
        
        
        
           for 
        
        
          |
        
        x
        
          |
        
        ≤
        1.
      
    
    
  

== Multivariate examples ==

  
    
      
        x
         
        y
        O
        x
        
        
           for 
        
        x
        ≥
        1
        ,
        y
        
           any real number
        
      
    
    
  

  
    
      
        3
        
          a
          
            2
          
        
        7
        a
        b
        2
        
          b
          
            2
          
        
        a
        3
        b
        14
        ≪
        
          a
          
            2
          
        
        
          b
          
            2
          
        
        ≪
        
          a
          
            2
          
        
        
        
           for all 
        
        a
        ≥
        b
        ≥
        1
      
    
    
  

  
    
      
        
          
            
              x
              y
            
            
              
                x
                
                  2
                
              
              
                y
                
                  2
                
              
            
          
        
        O
        1
        
        
           for all real 
        
        x
        ,
        y
        
           that are not both 
        
        0
      
    
    
  

  
    
      
        
          x
          
            i
            t
          
        
        O
        1
        
        
           for 
        
        x
        ≠
        0
        ,
        t
        ∈
        
          R
        
        .
      
    
    
  

Here we have a complex variable function of two variables.
In general, any bounded function is 
  
    
      
        O
        1
      
    
    
  
.

  
    
      
        x
        y
        
          
            10
          
        
        O
        
          x
          
            10
          
        
        
        
           for 
        
        x
        ≥
        1
        ,
        2
        ≤
        y
        ≤
        2.
      
    
    
  

The last example illustrates a mixing of finite and infinite domains on the different variables.
In all of these examples, the bound is uniform
in both variables. Sometimes in a multivariate expression, one variable is
more important than others, and one may express
that the implied constant 
  
    
      
        M
      
    
    
  
 depends on one
or more of the variables using subscripts to the big O symbol or the 
  
    
      
        ≪
      
    
    
  
 symbol. For example, consider the expression

  
    
      
        1
        x
        
          
            b
          
        
        1
        
          O
          
            b
          
        
        x
        
        
           for 
        
        0
        ≤
        x
        ≤
        1
        ,
        b
        
           any real number.
        
      
    
    
  

This means that for each real number 
  
    
      
        b
      
    
    
  
, there 
is a constant 
  
    
      
        
          M
          
            b
          
        
      
    
    
  
, which depends on 
  
    
      
        b
      
    
    
  
, so that for all 
  
    
      
        0
        ≤
        x
        ≤
        1
      
    
    
  
,

  
    
      
        
          |
        
        1
        x
        
          
            b
          
        
        1
        
          |
        
        ≤
        
          M
          
            b
          
        
        ⋅
        x
        .
      
    
    
  

This particular statement follows from the general binomial theorem.
Another example, common in the theory of Taylor series, is

  
    
      
        
          e
          
            x
          
        
        1
        x
        
          O
          
            r
          
        
        
          x
          
            2
          
        
        
        
           for all 
        
        
          |
        
        x
        
          |
        
        ≤
        r
        ,
        r
        
           being any real number.
        
      
    
    
  

Here the implied constant depends on the size of the domain.
The subscript convention applies to all of the other
notations in this page.

== Properties ==

=== Product ===

  
    
      
        
          f
          
            1
          
        
        O
        
          g
          
            1
          
        
        
           and 
        
        
          f
          
            2
          
        
        O
        
          g
          
            2
          
        
        ⇒
        
          f
          
            1
          
        
        
          f
          
            2
          
        
        O
        
          g
          
            1
          
        
        
          g
          
            2
          
        
      
    
    
  

  
    
      
        f
        ⋅
        O
        g
        =
        O
        
          |
        
        f
        
          |
        
        g
      
    
    
  

=== Sum ===
If 
  
    
      
        
          f
          
            1
          
        
        O
        
          g
          
            1
          
        
      
    
    
  
 and 
  
    
      
        
          f
          
            2
          
        
        O
        
          g
          
            2
          
        
      
    
    
  
 then 
  
    
      
        
          f
          
            1
          
        
        
          f
          
            2
          
        
        O
        max
        
          g
          
            1
          
        
        ,
        
          g
          
            2
          
        
        )
      
    
    
  
. It follows that if 
  
    
      
        
          f
          
            1
          
        
        O
        g
      
    
    
  
 and 
  
    
      
        
          f
          
            2
          
        
        O
        g
      
    
    
  
 then 
  
    
      
        
          f
          
            1
          
        
        
          f
          
            2
          
        
        O
        g
      
    
    
  
.

=== Multiplication by a constant ===
Let k be a nonzero constant. Then 
  
    
      
        O
        
          |
        
        k
        
          |
        
        ⋅
        g
        =
        O
        g
      
    
    
  
. In other words, if 
  
    
      
        f
        O
        g
      
    
    
  
, then 
  
    
      
        k
        ⋅
        f
        O
        g
        .
      
    
    
  

=== Transitive property ===
If 
  
    
      
        f
        O
        g
      
    
    
  
 and 
  
    
      
        g
        O
        h
      
    
    
  
 then

  
    
      
        f
        O
        h
      
    
    
  
.
If the function 
  
    
      
        f
      
    
    
  
 of a positive integer

  
    
      
        n
      
    
    
  
 can be written as a finite sum of other functions, then the fastest growing one determines the order of 
  
    
      
        f
        n
      
    
    
  
. For example,

  
    
      
        f
        n
        =
        9
         
        n
        5
        log
         
        n
        
          
            4
          
        
        3
        
          n
          
            2
          
        
        2
        
          n
          
            3
          
        
        O
        
          n
          
            3
          
        
        
        
          for 
        
        n
        ≥
        1.
      
    
    
  

Some general rules about growth toward infinity; the 2nd and 3rd property below
can be proved rigorously using L'Hôpital's rule:

=== Large powers dominate small powers ===
For 
  
    
      
        b
        ≥
        a
      
    
    
  
, then

  
    
      
        
          n
          
            a
          
        
        O
        
          n
          
            b
          
        
      
    
    
  

as 
  
    
      
        n
        →
        ∞
      
    
    
  
.

=== Powers dominate logarithms ===
For any positive 
  
    
      
        a
        ,
        b
        ,
      
    
    
  
 

  
    
      
        log
         
        n
        
          
            a
          
        
        
          O
          
            a
            ,
            b
          
        
        
          n
          
            b
          
        
        ,
      
    
    
  

no matter how large 
  
    
      
        a
      
    
    
  
 is and how small

  
    
      
        b
      
    
    
  
 is. Here, the implied constant depends
on both 
  
    
      
        a
      
    
    
  
 and 
  
    
      
        b
      
    
    
  
.

=== Exponentials dominate powers ===
For any positive 
  
    
      
        a
        ,
        b
        ,
      
    
    
  
 

  
    
      
        
          n
          
            a
          
        
        
          O
          
            a
            ,
            b
          
        
        
          e
          
            b
            n
          
        
        ,
      
    
    
  

no matter how large 
  
    
      
        a
      
    
    
  
 is and how small

  
    
      
        b
      
    
    
  
 is.
A function that grows faster than 
  
    
      
        
          n
          
            c
          
        
      
    
    
  
 for any 
  
    
      
        c
      
    
    
  
 is called superpolynomial. One that grows more slowly than any exponential function of the form 
  
    
      
        
          c
          
            n
          
        
      
    
    
  
 with 
  
    
      
        c
        1
      
    
    
  
 is called subexponential. An algorithm can require time that is both superpolynomial and subexponential; examples of this include the fastest known algorithms for integer factorization and the function 
  
    
      
        
          n
          
             
            n
          
        
      
    
    
  
.
We may ignore any powers of 
  
    
      
        n
      
    
    
  
 inside of the logarithms. For any positive 
  
    
      
        c
      
    
    
  
, the notation 
  
    
      
        O
        log
         
        n
      
    
    
  
 means exactly the same thing as 
  
    
      
        O
        log
         
        
          n
          
            c
          
        
        )
      
    
    
  
, since 
  
    
      
         
        
          n
          
            c
          
        
        =
        c
         
        n
      
    
    
  
. Similarly, logs with different constant bases are equivalent with respect to Big O 
notation. On the other hand, exponentials with different bases are not of the same order. For example, 
  
    
      
        
          2
          
            n
          
        
      
    
    
  
 and 
  
    
      
        
          3
          
            n
          
        
      
    
    
  
 are not of the same order.

=== More complicated expressions ===
In more complicated usage, 
  
    
      
        O
        ⋅
      
    
    
  
 can appear in different places in an equation, even several times on each side. For example, the following are true for 
  
    
      
        n
      
    
    
  
 a positive integer:

  
    
      
        
          
            
              
                n
                1
                
                  
                    2
                  
                
              
              
                
                
                  n
                  
                    2
                  
                
                O
                n
                ,
              
            
            
              
                n
                O
                
                  n
                  
                    1
                    
                      /
                    
                    2
                  
                
                )
                ⋅
                n
                O
                log
                 
                n
                
                  
                    2
                  
                
              
              
                
                
                  n
                  
                    3
                  
                
                O
                
                  n
                  
                    5
                    
                      /
                    
                    2
                  
                
                ,
              
            
            
              
                
                  n
                  
                    O
                    1
                  
                
              
              
                
                O
                
                  e
                  
                    n
                  
                
                .
              
            
          
        
      
    
    
  

The meaning of such statements is as follows: for any functions which satisfy each 
  
    
      
        O
        ⋅
      
    
    
  
 on the left side, there are some functions satisfying each 
  
    
      
        O
        ⋅
      
    
    
  
 on the right side, such that substituting all these functions into the equation makes the two sides equal. For example, the third equation above means: "For any function satisfying 
  
    
      
        f
        n
        =
        O
        1
      
    
    
  
, there is some function 
  
    
      
        g
        n
        =
        O
        
          e
          
            n
          
        
      
    
    
  
 such that 
  
    
      
        
          n
          
            f
            n
          
        
        g
        n
      
    
    
  
". The implied constant in the statement "
  
    
      
        g
        n
        =
        O
        
          e
          
            n
          
        
      
    
    
  
" may
depend on the implied constant in the expression
"
  
    
      
        f
        n
        =
        O
        1
      
    
    
  
".
Some further examples:

  
    
      
        
          
            
              
                f
                O
                g
                
              
              
                
                ⇒
                
                
                  ∫
                  
                    a
                  
                  
                    b
                  
                
                f
                O
                
                  
                  
                
                
                  ∫
                  
                    a
                  
                  
                    b
                  
                
                g
                
                  
                  
                
              
            
            
              
                f
                x
                =
                g
                x
                +
                O
                1
                
              
              
                
                ⇒
                
                
                  e
                  
                    f
                    x
                  
                
                O
                
                  e
                  
                    g
                    x
                  
                
              
            
            
              
                1
                O
                1
                
                  /
                
                x
                
                  
                    O
                    x
                  
                
              
              
                
                O
                1
                
                
                   for 
                
                x
                0
              
            
            
              
                 
                x
              
              
                
                O
                
                  |
                
                x
                
                  |
                
                
                
                   for all real 
                
                x
                .
              
            
          
        
      
    
    
  

=== Vinogradov's ≫ and Knuth's big Ω ===
When 
  
    
      
        f
        ,
        g
      
    
    
  
 are both positive functions,
Vinogradov introduced the notation 
  
    
      
        f
        x
        ≫
        g
        x
      
    
    
  
, which means the same as 
  
    
      
        g
        x
        =
        O
        f
        x
        )
      
    
    
  
. Vinogradov's two notations enjoy visual symmetry, as
for positive functions 
  
    
      
        f
        ,
        g
      
    
    
  
, we have

  
    
      
        f
        x
        ≪
        g
        x
        ⟺
        g
        x
        ≫
        f
        x
        .
      
    
    
  

In 1976, Donald Knuth
defined

  
    
      
        f
        x
        =
        Ω
        g
        x
        )
        ⟺
        g
        x
        =
        O
        f
        x
        )
      
    
    
  

which has the same meaning as Vinogradov's 
  
    
      
        f
        x
        ≫
        g
        x
      
    
    
  
.
However, much earlier, Hardy and Littlewood had defined 
  
    
      
        Ω
      
    
    
  
 differently, and their notation enjoys widespread use today in analytic number theory.
Justifying his use of the 
  
    
      
        Ω
      
    
    
  
-symbol to describe a stronger property, Knuth wrote: "For all the applications I have seen so far in computer science, a stronger requirement ... is much more appropriate". Knuth further wrote, "Although I have changed Hardy and Littlewood's definition of 
  
    
      
        Ω
      
    
    
  
, I feel justified in doing so because their definition is by no means in wide use, and because there are other ways to say what they want to say in the comparatively rare cases when their definition applies." Knuth's big 
  
    
      
        Ω
      
    
    
  
 enjoys widespread use today
in computer science and combinatorics.

=== Hardy's ≍ and Knuth's big Θ ===
In analytic number theory, the
notation 
  
    
      
        f
        x
        ≍
        g
        x
      
    
    
  
 means both

  
    
      
        f
        x
        =
        O
        g
        x
        )
      
    
    
  
 and 
  
    
      
        g
        x
        =
        O
        f
        x
        )
      
    
    
  
. This notation is originally due to Hardy. Knuth's notation for the same notion 
is 
  
    
      
        f
        x
        =
        Θ
        g
        x
        )
      
    
    
  
. Roughly speaking, these statements assert that 
  
    
      
        f
        x
      
    
    
  
 and 
  
    
      
        g
        x
      
    
    
  
 have the same order. These notations mean that there are 
positive constants 
  
    
      
        M
        ,
        N
      
    
    
  

so that 

  
    
      
        N
        g
        x
        ≤
        f
        x
        ≤
        M
        g
        x
      
    
    
  

for all 
  
    
      
        x
      
    
    
  
 in the common domain of 

  
    
      
        f
        ,
        g
      
    
    
  
. When the functions are defined on the positive integers or positive real numbers, as with big O, writers oftentimes interpret statements

  
    
      
        f
        x
        =
        Ω
        g
        x
        )
      
    
    
  
 and 
  
    
      
        f
        x
        =
        Θ
        g
        x
        )
      
    
    
  
 as holding for all sufficiently large 
  
    
      
        x
      
    
    
  
, that is, for all 
  
    
      
        x
      
    
    
  
 beyond some point 
  
    
      
        
          x
          
            0
          
        
      
    
    
  
. Sometimes this is indicated by appending 
  
    
      
        x
        →
        ∞
      
    
    
  
 to the statement. For example,

  
    
      
        2
        
          n
          
            2
          
        
        10
        n
        Θ
        
          n
          
            2
          
        
      
    
    
  

is true for the domain 
  
    
      
        n
        ≥
        6
      
    
    
  
 but false if the
domain is all positive integers, since the function is zero at 
  
    
      
        n
        5
      
    
    
  
.

==== Further examples ====

  
    
      
        
          n
          
            3
          
        
        20
        
          n
          
            2
          
        
        n
        12
        ≍
        
          n
          
            3
          
        
        
        
           for all 
        
        n
        ≥
        1.
      
    
    
  

  
    
      
        1
        x
        
          
            8
          
        
        
          x
          
            8
          
        
        Θ
        
          x
          
            7
          
        
        
        
           for all 
        
        x
        ≥
        1.
      
    
    
  

The notation

  
    
      
        f
        n
        =
        
          e
          
            Ω
            n
          
        
        
        
           for all 
        
        n
        ≥
        1
        ,
      
    
    
  

means that there is a positive constant 
  
    
      
        M
      
    
    
  

so that 
  
    
      
        f
        n
        ≥
        
          e
          
            M
            n
          
        
      
    
    
  
 for all 
  
    
      
        n
        ≥
        1
      
    
    
  
. By contrast,

  
    
      
        f
        n
        =
        
          e
          
            O
            n
          
        
        
        
           for all 
        
        n
        ≥
        1
        ,
      
    
    
  

means that there is a positive constant 
  
    
      
        M
      
    
    
  

so that 
  
    
      
        f
        n
        ≥
        
          e
          
            M
            n
          
        
      
    
    
  
 for all 
  
    
      
        n
        ≥
        1
      
    
    
  
 and

  
    
      
        f
        n
        =
        
          e
          
            Θ
            n
          
        
        
        
           for all 
        
        n
        ≥
        1
        ,
      
    
    
  

means that there are positive constants 
  
    
      
        M
        ,
        N
      
    
    
  

so that 
  
    
      
        
          e
          
            M
            n
          
        
        ≤
        f
        n
        ≤
        
          e
          
            N
            n
          
        
      
    
    
  
 for all 
  
    
      
        n
        ≥
        1
      
    
    
  
.
For any domain 
  
    
      
        D
      
    
    
  
,

  
    
      
        f
        x
        =
        g
        x
        +
        O
        1
        ⟺
        
          e
          
            f
            x
          
        
        ≍
        
          e
          
            g
            x
          
        
        ,
      
    
    
  

each statement being for all 
  
    
      
        x
      
    
    
  
 in 
  
    
      
        D
      
    
    
  
.

== Orders of common functions ==

Here is a list of classes of functions that are commonly encountered when analyzing the running time of an algorithm. In each case, c is a positive constant and n increases without bound. The slower-growing functions are generally listed first.

The statement 
  
    
      
        f
        n
        =
        O
        n
        !
      
    
    
  
 is sometimes weakened to 
  
    
      
        f
        n
        =
        O
        
          
            n
            
              n
            
          
        
      
    
    
  
 to derive simpler formulas for asymptotic complexity.
In many of these examples, the running time is
actually 
  
    
      
        Θ
        g
        n
        )
      
    
    
  
, which conveys more
precision.

== Little-o notation ==

For real or complex-valued functions of a real variable

  
    
      
        x
      
    
    
  
 with 
  
    
      
        g
        x
        >
        0
      
    
    
  
 for sufficiently large 
  
    
      
        x
      
    
    
  
, one writes
 

  
    
      
        f
        x
        =
        o
        g
        x
        )
        
        
           as 
        
        x
        →
        ∞
      
    
    
  

if 

  
    
      
        
          
            x
            →
            ∞
          
        
        
          
            
              f
              x
            
            
              g
              x
            
          
        
        0.
      
    
    
  

That is, for every positive constant ε there exists a constant 
  
    
      
        
          x
          
            0
          
        
      
    
    
  
 such that

  
    
      
        
          |
        
        f
        x
        
          |
        
        ≤
        ε
        g
        x
        
        
           for all 
        
        x
        ≥
        
          x
          
            0
          
        
        .
      
    
    
  

Intuitively, this means that 
  
    
      
        g
        x
      
    
    
  
 grows much faster than 
  
    
      
        f
        x
      
    
    
  
, or equivalently 
  
    
      
        f
        x
      
    
    
  
 grows much slower than 

  
    
      
        g
        x
      
    
    
  
.
For example, one has

  
    
      
        200
        x
        o
        
          x
          
            2
          
        
      
    
    
  
 and 
  
    
      
        1
        
          /
        
        x
        o
        1
        ,
      
    
    
  
     both as 
  
    
      
        x
        →
        ∞
        .
      
    
    
  

When one is interested in the behavior of a function for large values of 
  
    
      
        x
      
    
    
  
, little-o notation makes a stronger statement than the corresponding big-O notation: every function that is little-o of 
  
    
      
        g
      
    
    
  
 is also big-O of 
  
    
      
        g
      
    
    
  
 on some interval 
  
    
      
        a
        ,
        ∞
      
    
    
  
, but not every function that is big-O of 
  
    
      
        g
      
    
    
  
 is little-o of 
  
    
      
        g
      
    
    
  
. For example, 
  
    
      
        2
        
          x
          
            2
          
        
        O
        
          x
          
            2
          
        
      
    
    
  
 but 
  
    
      
        2
        
          x
          
            2
          
        
        ≠
        o
        
          x
          
            2
          
        
      
    
    
  
 for 
  
    
      
        x
        ≥
        1
      
    
    
  
.
Little-o respects a number of arithmetic operations. For example,

if 
  
    
      
        c
      
    
    
  
 is a nonzero constant and 
  
    
      
        f
        o
        g
      
    
    
  
 then 
  
    
      
        c
        ⋅
        f
        o
        g
      
    
    
  
, and
if 
  
    
      
        f
        o
        F
      
    
    
  
 and 
  
    
      
        g
        o
        G
      
    
    
  
 then 
  
    
      
        f
        ⋅
        g
        o
        F
        ⋅
        G
        .
      
    
    
  

if 
  
    
      
        f
        o
        F
      
    
    
  
 and 
  
    
      
        g
        o
        G
      
    
    
  
 then 
  
    
      
        f
        g
        o
        F
        G
      
    
    
  

It also satisfies a transitivity relation:

if 
  
    
      
        f
        o
        g
      
    
    
  
 and 
  
    
      
        g
        o
        h
      
    
    
  
 then 
  
    
      
        f
        o
        h
        .
      
    
    
  

Little-o can also be generalized to the finite case:

  
    
      
        f
        x
        =
        o
        g
        x
        )
        
        
           as 
        
        x
        →
        
          x
          
            0
          
        
      
    
    
  
 if 

  
    
      
        
          
            x
            →
            
              x
              
                0
              
            
          
        
        
          
            
              f
              x
            
            
              g
              x
            
          
        
        0.
      
    
    
  

In other words,

  
    
      
        f
        x
        =
        α
        x
        g
        x
      
    
    
  
 for some 
  
    
      
        α
        x
      
    
    
  
 with 
  
    
      
        
          
            x
            →
            
              x
              
                0
              
            
          
        
        α
        x
        =
        0
      
    
    
  
.
This definition is especially useful in the computation of limits using Taylor series. For example:

  
    
      
         
        x
        x
        
          
            
              x
              
                3
              
            
            
              3
              !
            
          
        
        …
        x
        o
        
          x
          
            2
          
        
        
           as 
        
        x
        →
        0
      
    
    
  
, so 
  
    
      
        
          
            x
            →
            0
          
        
        
          
            
               
              x
            
            x
          
        
        
          
            x
            →
            0
          
        
        
          
            
              x
              o
              
                x
                
                  2
                
              
            
            x
          
        
        
          
            x
            →
            0
          
        
        1
        o
        x
        =
        1
      
    
    
  

=== Asymptotic notation ===
A relation related to little-o is the asymptotic notation

  
    
      
        ∼
      
    
    
  
.
For real valued functions 
  
    
      
        f
        ,
        g
      
    
    
  
, the expression 
  
    
      
        f
        x
        ∼
        g
        x
        
        
           as 
        
        x
        →
        ∞
      
    
    
  

means 

  
    
      
        
          
            x
            →
            ∞
          
        
        
          
            
              f
              x
            
            
              g
              x
            
          
        
        1.
      
    
    
  

One can connect this to little-o by observing that

  
    
      
        f
        x
        ∼
        g
        x
      
    
    
  
 is also equivalent to

  
    
      
        f
        x
        =
        1
        o
        1
        )
        g
        x
      
    
    
  
. Here 
  
    
      
        o
        1
      
    
    
  
 refers to a function tending to zero as 
  
    
      
        x
        →
        ∞
      
    
    
  
. One reads this as
"
  
    
      
        f
        x
      
    
    
  
 is asymptotic to 
  
    
      
        g
        x
      
    
    
  
". For nonzero functions on the same (finite or infinite) domain, 
  
    
      
        ∼
      
    
    
  
 forms an
equivalence relation.
One of the most famous theorems using the notation 

  
    
      
        ∼
      
    
    
  
 is Stirling's formula

  
    
      
        n
        !
        ∼
        
          
          
        
        
          
            n
            e
          
        
        
          
            
            
          
          
            n
          
        
        
          
            2
            π
            n
          
        
        
        
           as 
        
        n
        →
        ∞
        .
      
    
    
  

In number theory, the famous prime number theorem states that

  
    
      
        π
        x
        ∼
        
          
            x
            
               
              x
            
          
        
        
        
           as 
        
        x
        →
        ∞
        ,
      
    
    
  

where 
  
    
      
        π
        x
      
    
    
  
 is the number of primes which
are at most 
  
    
      
        x
      
    
    
  
 and 
  
    
      
      
    
    
  
 is the
natural logarithm of 
  
    
      
        x
      
    
    
  
.
As with little-o, there is a version with finite limits (two-sided or one-sided) as well, for example 

  
    
      
         
        x
        ∼
        x
        
        
           as 
        
        x
        →
        0.
      
    
    
  

Further examples:

  
    
      
        
          x
          
            a
          
        
        
          o
          
            a
            ,
            b
          
        
        
          e
          
            b
            x
          
        
        
        
           as 
        
        x
        →
        ∞
        ,
        
           for any positive constants 
        
        a
        ,
        b
        ,
      
    
    
  

  
    
      
        f
        x
        =
        g
        x
        +
        o
        1
        
        ⟺
        
        
          e
          
            f
            x
          
        
        ∼
        
          e
          
            g
            x
          
        
        
        x
        →
        ∞
        .
      
    
    
  

  
    
      
        
          ∑
          
            n
            1
          
          
            ∞
          
        
        
          
            1
            
              n
              
                s
              
            
          
        
        ∼
        
          
            1
            
              s
              1
            
          
        
        
        s
        →
        
          1
          
          
        
        .
      
    
    
  

The last asymptotic is a basic property of the
Riemann zeta function.

=== Knuth's little 𝜔 ===
For eventually positive, real valued functions 
  
    
      
        f
        ,
        g
        ,
      
    
    
  
 the notation

  
    
      
        f
        x
        =
        ω
        g
        x
        )
        
        
           as 
        
        x
        →
        ∞
      
    
    
  

means 

  
    
      
        
          
            x
            →
            ∞
          
        
        
          
            
              f
              x
            
            
              g
              x
            
          
        
        ∞
        .
      
    
    
  

In other words, 
  
    
      
        g
        x
        =
        o
        f
        x
        )
      
    
    
  
.
Roughly speaking, this means that 
  
    
      
        f
        x
      
    
    
  

grows much faster than does 
  
    
      
        g
        x
      
    
    
  
.

=== The Hardy–Littlewood Ω notation ===
In 1914 G. H. Hardy and J. E. Littlewood introduced the new symbol 
  
    
      
         
        Ω
        ,
      
    
    
  
 which is defined as follows:

  
    
      
        f
        x
        =
        Ω
        g
        x
        )
        
      
    
    
  
 as 
  
    
      
        
        x
        →
        ∞
        
      
    
    
  
 if 
  
    
      
        
        
          lim sup
          
            x
            →
            ∞
          
        
         
        
          |
          
            
              
                 
                f
                x
                 
              
              
                g
                x
              
            
          
          |
        
        0
         
        .
      
    
    
  

Thus 
  
    
      
         
        f
        x
        =
        Ω
        g
        x
        )
         
      
    
    
  
 is the negation of 
  
    
      
         
        f
        x
        =
        o
        g
        x
        )
         
        .
      
    
    
  

In 1916 the same authors introduced the two new symbols 
  
    
      
         
        
          Ω
          
            R
          
        
         
      
    
    
  
 and 
  
    
      
         
        
          Ω
          
            L
          
        
         
        ,
      
    
    
  
 defined as:

  
    
      
        f
        x
        =
        
          Ω
          
            R
          
        
        g
        x
        )
        
      
    
    
  
 as 
  
    
      
        
        x
        →
        ∞
        
      
    
    
  
 if 
  
    
      
        
        
          lim sup
          
            x
            →
            ∞
          
        
         
        
          
            
               
              f
              x
               
            
            
              g
              x
            
          
        
        0
         
        ;
      
    
    
  

  
    
      
        f
        x
        =
        
          Ω
          
            L
          
        
        g
        x
        )
        
      
    
    
  
 as 
  
    
      
        
        x
        →
        ∞
        
      
    
    
  
 if 
  
    
      
        
         
        
          lim inf
          
            x
            →
            ∞
          
        
         
        
          
            
               
              f
              x
               
            
            
              g
              x
            
          
        
        0
         
        .
      
    
    
  

These symbols were used by E. Landau, with the same meanings, in 1924. Authors that followed Landau, however, use a different notation for the same definitions: The symbol 
  
    
      
         
        
          Ω
          
            R
          
        
         
      
    
    
  
 has been replaced by the current notation 
  
    
      
         
        
          Ω
          
          
        
         
      
    
    
  
 with the same definition, and 
  
    
      
         
        
          Ω
          
            L
          
        
         
      
    
    
  
 became 
  
    
      
         
        
          Ω
          
          
        
         
        .
      
    
    
  

These three symbols 
  
    
      
         
        Ω
         
        ,
        
          Ω
          
          
        
         
        ,
        
          Ω
          
          
        
         
        ,
      
    
    
  
 as well as 
  
    
      
         
        f
        x
        =
        
          Ω
          
            ±
          
        
        g
        x
        )
         
      
    
    
  
 (meaning that 
  
    
      
         
        f
        x
        =
        
          Ω
          
          
        
        g
        x
        )
         
      
    
    
  
 and 
  
    
      
         
        f
        x
        =
        
          Ω
          
          
        
        g
        x
        )
         
      
    
    
  
 are both satisfied), are now currently used in analytic number theory.

==== Simple examples ====
We have

  
    
      
         
        x
        Ω
        1
        
      
    
    
  
 as 
  
    
      
        
        x
        →
        ∞
         
        ,
      
    
    
  

and more precisely

  
    
      
         
        x
        
          Ω
          
            ±
          
        
        1
        
      
    
    
  
 as 
  
    
      
        
        x
        →
        ∞
        ,
         
      
    
    
  

where 
  
    
      
        
          Ω
          
            ±
          
        
      
    
    
  
 means that the left side is both 
  
    
      
        
          Ω
          
          
        
        1
      
    
    
  
 and 
  
    
      
        
          Ω
          
          
        
        1
      
    
    
  
,
We have

  
    
      
        1
        sin
         
        x
        Ω
        1
        
      
    
    
  
 as 
  
    
      
        
        x
        →
        ∞
         
        ,
      
    
    
  

and more precisely

  
    
      
        1
        sin
         
        x
        
          Ω
          
          
        
        1
        
      
    
    
  
 as 
  
    
      
        
        x
        →
        ∞
         
        ;
      
    
    
  

however

  
    
      
        1
        sin
         
        x
        ≠
        
          Ω
          
          
        
        1
        
      
    
    
  
 as 
  
    
      
        
        x
        →
        ∞
         
        .
      
    
    
  

=== Family of Bachmann–Landau notations ===
For understanding the formal definitions, consult the
list of logic symbols used in mathematics.

The limit definitions assume 
  
    
      
        g
        n
        >
        0
      
    
    
  
 for

  
    
      
        n
      
    
    
  
 in a neighborhood of the limit; when the
limit is 
  
    
      
        ∞
      
    
    
  
, this means that 
  
    
      
        g
        n
        >
        0
      
    
    
  
 for sufficiently large 
  
    
      
        n
      
    
    
  
.
Computer science and combinatorics use the big 
  
    
      
        O
      
    
    
  
, big Theta 
  
    
      
        Θ
      
    
    
  
, little 
  
    
      
        o
      
    
    
  
, little omega 
  
    
      
        ω
      
    
    
  
 and Knuth's big Omega 
  
    
      
        Ω
      
    
    
  
 notations.
 
Analytic number theory often uses the big 
  
    
      
        O
      
    
    
  
, small 
  
    
      
        o
      
    
    
  
, Hardy's 
  
    
      
        ≍
      
    
    
  
,
Hardy–Littlewood's big Omega 
  
    
      
        Ω
      
    
    
  
 (with or without the +, − or ± subscripts), Vinogradov's 
  
    
      
        ≪
      
    
    
  
 and 
  
    
      
        ≫
      
    
    
  
 notations and 
  
    
      
        ∼
      
    
    
  
 notations.
 

 
The small omega 
  
    
      
        ω
      
    
    
  
 notation is not used as often in analysis or in number theory.

=== Quality of approximations using different notation ===

Informally, especially in computer science, the big 
  
    
      
        O
      
    
    
  
 notation often can be used somewhat differently to describe an asymptotic tight bound where using big Theta 
  
    
      
        Θ
      
    
    
  
 notation might be more factually appropriate in a given context
.
For example, when considering a function 
  
    
      
        T
        n
        =
        73
        
          n
          
            3
          
        
        22
        
          n
          
            2
          
        
        58
      
    
    
  
, all of the following are generally acceptable, but tighter bounds (such as numbers 2,3 and 4 below) are usually strongly preferred over looser bounds (such as number 1 below).

  
    
      
        T
        n
        =
        O
        
          n
          
            100
          
        
      
    
    
  

  
    
      
        T
        n
        =
        O
        
          n
          
            3
          
        
      
    
    
  

  
    
      
        T
        n
        =
        Θ
        
          n
          
            3
          
        
      
    
    
  

  
    
      
        T
        n
        ∼
        73
        
          n
          
            3
          
        
      
    
    
  
 as 
  
    
      
        n
        →
        ∞
      
    
    
  
.
While all three statements are true, progressively more information is contained in each. In some fields, however, the big O notation (number 2 in the lists above) would be used more commonly than the big Theta notation (items numbered 3 in the lists above). For example, if 
  
    
      
        T
        n
      
    
    
  
 represents the running time of a newly developed algorithm for input size 
  
    
      
        n
      
    
    
  
, the inventors and users of the algorithm might be more inclined to put an upper bound on how long it will take to run without making an explicit statement about the lower bound or asymptotic behavior.

=== Extensions to the Bachmann–Landau notations ===
Another notation sometimes used in computer science is 
  
    
      
        
          
            
              O
              ~
            
          
        
      
    
    
  
 (read soft-O), which hides polylogarithmic factors. There are two definitions in use: some authors use 
  
    
      
        f
        n
        =
        
          
            
              O
              ~
            
          
        
        g
        n
        )
      
    
    
  
 as shorthand for 
  
    
      
        f
        n
        =
        O
        g
        n
        
          
            k
          
        
         
        n
      
    
    
  
 for some 
  
    
      
        k
      
    
    
  
, while others use it as shorthand for 
  
    
      
        f
        n
        =
        O
        g
        n
        
          
            k
          
        
         
        g
        n
        )
      
    
    
  

.
When 
  
    
      
        g
        n
      
    
    
  
 is polynomial in 
  
    
      
        n
      
    
    
  
, there is no difference; however, the latter definition allows one to say, e.g. that 
  
    
      
        n
        
          2
          
            n
          
        
        
          
            
              O
              ~
            
          
        
        
          2
          
            n
          
        
      
    
    
  
 while the former definition allows for 
  
    
      
        
          
            k
          
        
         
        n
        
          
            
              O
              ~
            
          
        
        1
      
    
    
  
 for any constant 
  
    
      
        k
      
    
    
  
. Some authors write O* for the same purpose as the latter definition. Essentially, it is less precise version of the big O notation, ignoring logarithmic factors in the growth-rate of the function.  Since 
  
    
      
        
          
            k
          
        
         
        n
        o
        
          n
          
            ε
          
        
      
    
    
  

for any constant 
  
    
      
        k
      
    
    
  
 and any 

  
    
      
        ε
        0
      
    
    
  
, logarithmic factors are far less significant than powers of 
  
    
      
        n
      
    
    
  
 and even more insignificant compared with exponentials.
Also, the L notation, defined as

  
    
      
        
          L
          
            n
          
        
        α
        ,
        c
        =
        
          e
          
            c
            o
            1
            )
            ln
             
            n
            
              
                α
              
            
            ln
             
             
            n
            
              
                1
                α
              
            
          
        
        ,
      
    
    
  

is convenient for functions that are between polynomial and exponential in terms of 
  
    
      
         
        n
      
    
    
  
.

== Generalizations and related usages ==
The generalization to functions taking values in any normed vector space is straightforward (replacing absolute values by norms), where 
  
    
      
        f
      
    
    
  
 and 
  
    
      
        g
      
    
    
  
 need not take their values in the same space. A generalization to functions 
  
    
      
        g
      
    
    
  
 taking values in any topological group is also possible.
The "limiting process" 
  
    
      
        x
        →
        
          x
          
            0
          
        
      
    
    
  
 can also be generalized by introducing an arbitrary filter base, i.e. to directed nets 
  
    
      
        f
      
    
    
  
 and 
  
    
      
        g
      
    
    
  
. The 
  
    
      
        o
      
    
    
  
 notation can be used to define derivatives and differentiability in quite general spaces, and also (asymptotical) equivalence of functions,

  
    
      
        f
        ∼
        g
        
        ⟺
        
        f
        g
        ∈
        o
        g
      
    
    
  

which is an equivalence relation and a more restrictive notion than the relationship "
  
    
      
        f
      
    
    
  
 is 
  
    
      
        Θ
        g
      
    
    
  
" from above. (It reduces to 
  
    
      
        f
        
          /
        
        g
        1
      
    
    
  
 if 
  
    
      
        f
      
    
    
  
 and 
  
    
      
        g
      
    
    
  
 are positive real valued functions.) For example, 
  
    
      
        2
        x
        Θ
        x
      
    
    
  
 is, but 

  
    
      
        2
        x
        x
        ≠
        o
        x
      
    
    
  
.

== History ==
In 1870, Paul du Bois-Reymond 
defined 
  
    
      
        f
        x
        ≻
        ϕ
        x
      
    
    
  
, 
  
    
      
        f
        x
        ∼
        ϕ
        x
      
    
    
  
 and 
  
    
      
        f
        x
        ≺
        ϕ
        x
      
    
    
  

to mean, respectively,

  
    
      
        
          
            x
            →
            ∞
          
        
        
          
            
              f
              x
            
            
              ϕ
              x
            
          
        
        ∞
        ,
        
        
          
            x
            →
            ∞
          
        
        
          
            
              f
              x
            
            
              ϕ
              x
            
          
        
        0
        ,
        
        
          
            x
            →
            ∞
          
        
        
          
            
              f
              x
            
            
              ϕ
              x
            
          
        
        0.
      
    
    
  

These were not widely adopted and are not used today.
The first and third are symmetric: 
  
    
      
        f
        x
        ≺
        ϕ
        x
      
    
    
  
 means the same as 
  
    
      
        ϕ
        x
        ≻
        f
        x
      
    
    
  
. Landau later adopted 
  
    
      
        ∼
      
    
    
  
 with the narrower definition that the limit of 
  
    
      
        f
        x
        
          /
        
        ϕ
        x
      
    
    
  
 equals 1.
The symbol O was first introduced by the number theorist Paul Bachmann in 1894, in the second volume of his book Analytische Zahlentheorie ("analytic number theory"). The number theorist Edmund Landau adopted it, and was thus inspired to introduce in 1909 the notation o; hence both are now called Landau symbols. These notations were used in applied mathematics during the 1950s for asymptotic analysis.
The symbol 
  
    
      
        Ω
      
    
    
  
 (in the sense "is not little o of") was introduced in 1914 by Hardy and Littlewood. Hardy and Littlewood also introduced in 1916 the left and right 
  
    
      
        Ω
      
    
    
  
 symbols 
  
    
      
        
          Ω
          
            R
          
        
      
    
    
  
, 
  
    
      
        
          Ω
          
            L
          
        
      
    
    
  
 (now commonly denoted 
  
    
      
        
          Ω
          
          
        
        ,
        
          Ω
          
          
        
      
    
    
  
). This 
  
    
      
        Ω
      
    
    
  
 notation has been commonly used in number theory since the 1950s.
Hardy introduced the symbols 
  
    
      
        ≼
      
    
    
  
 and advocated for Bois-Reymond's 
  
    
      
        ≺
      
    
    
  
 (as well as the already mentioned other symbols) in his 1910 tract "Orders of Infinity", but made use of them only in three papers (1910–1913). In his nearly 400 remaining papers and books he consistently used the Landau symbols O and o.
Hardy's symbols 
  
    
      
        ≼
      
    
    
  
 and 
  
    
      
        
          
          ≍
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
        
      
    
    
  
 are not used any more.
The symbol 
  
    
      
        ∼
      
    
    
  
, although it had been used before with different meanings, was given its modern definition by Landau in 1909 and by Hardy in 1910. On the same page, Hardy defined the symbol 
  
    
      
        ≍
      
    
    
  
, where 
  
    
      
        f
        x
        ≍
        g
        x
      
    
    
  
 means that both 
  
    
      
        f
        x
        =
        O
        g
        x
        )
      
    
    
  
 and 
  
    
      
        g
        x
        =
        O
        f
        x
        )
      
    
    
  
 are satisfied. The notation is still used in analytic number theory.
 
Hardy also proposed the symbol 
  
    
      
        
          
          ≍
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
        
      
    
    
  
, where 
  
    
      
        f
        
          
          ≍
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
        
        g
      
    
    
  
 means that 
  
    
      
        f
        ∼
        K
        g
      
    
    
  
 for some constant 
  
    
      
        K
        ≠
        0
      
    
    
  
 (this 
corresponds to Bois-Reymond's notation 
  
    
      
        f
        ∼
        g
      
    
    
  
).
In the 1930s, Vinogradov popularized the notation 
  
    
      
        f
        x
        ≪
        g
        x
      
    
    
  

and 
  
    
      
        g
        x
        ≫
        f
        x
      
    
    
  
, both of which mean

  
    
      
        f
        x
        =
        O
        g
        x
        )
      
    
    
  
. This notation became standard in analytic number theory.
In the 1970s, big O was popularized in computer science by Donald Knuth, who proposed the different notation 
  
    
      
        f
        x
        =
        Θ
        g
        x
        )
      
    
    
  
 for Hardy's 
  
    
      
        f
        x
        ≍
        g
        x
      
    
    
  
, and proposed a different definition for the Hardy and Littlewood Omega notation.

== Matters of notation ==

=== Arrows ===
In mathematics, an expression such as 
  
    
      
        x
        →
        ∞
      
    
    
  
 indicates the presence of a limit. In big-O notation and related notations

  
    
      
        Ω
        ,
        Θ
        ,
        ≫
        ,
        ≪
        ,
        ≍
      
    
    
  
, there is no implied limit, in contrast with little-o,

  
    
      
        ∼
      
    
    
  
 and 
  
    
      
        ω
      
    
    
  
 notations.
Notation such as 
  
    
      
        f
        x
        =
        O
        g
        x
        )
        
        
        x
        →
        ∞
      
    
    
  
 can be considered an abuse of notation.

=== Equals sign ===
Some consider 
  
    
      
        f
        x
        =
        O
        g
        x
        )
      
    
    
  
 to also be an abuse of notation, since the use of the equals sign could be misleading as it suggests a symmetry that this statement does not have. As de Bruijn says, 
  
    
      
        O
        x
        =
        O
        
          x
          
            2
          
        
      
    
    
  
 is true but 
  
    
      
        O
        
          x
          
            2
          
        
        =
        O
        x
      
    
    
  
 is not. Knuth describes such statements as "one-way equalities", since if the sides could be reversed, "we could deduce ridiculous things like 

  
    
      
        n
        
          n
          
            2
          
        
      
    
    
  
 from the identities 
  
    
      
        n
        O
        
          n
          
            2
          
        
      
    
    
  
 and 
  
    
      
        
          n
          
            2
          
        
        O
        
          n
          
            2
          
        
      
    
    
  
. In another letter, Knuth also pointed out that

the equality sign is not symmetric with respect to such notations [as, in this notation,] mathematicians customarily use the '=' sign as they use the word 'is' in English: Aristotle is a man, but a man isn't necessarily Aristotle.
For these reasons, some advocate for using set notation and write 
  
    
      
        f
        x
        ∈
        O
        g
        x
        )
      
    
    
  
,
read as "
  
    
      
        f
        x
      
    
    
  
 is an element of 

  
    
      
        O
        g
        x
        )
      
    
    
  
", or "
  
    
      
        f
        x
      
    
    
  
 is in the set 

  
    
      
        O
        g
        x
        )
      
    
    
  
" –  thinking of 

  
    
      
        O
        g
        x
        )
      
    
    
  
 as the class of all functions 

  
    
      
        h
        x
      
    
    
  
 such that 
  
    
      
        h
        x
        =
        O
        g
        x
        )
      
    
    
  
. However, the use of the equals sign is customary.
and is more convenient in more complex expressions of the form

  
    
      
        f
        x
        =
        g
        x
        +
        O
        h
        x
        )
        O
        k
        x
        )
        .
      
    
    
  

The Vinogradov notations 
  
    
      
        ≪
      
    
    
  
 and 
  
    
      
        ≫
      
    
    
  
, which are widely used in number theory

do not suffer from this defect, as they more clearly indicate that big-O indicates an inequality rather than an equality. They also enjoy a symmetry that big-O notation lacks: 
  
    
      
        f
        x
        ≪
        g
        x
      
    
    
  
 
means the same as 
  
    
      
        g
        x
        ≫
        f
        x
      
    
    
  
. 
In combinatorics and computer science, these notations
are rarely seen.

=== Typesetting ===
Big O is typeset as an italicized uppercase "O", as in the following example: 
  
    
      
        O
        
          n
          
            2
          
        
      
    
    
  
. In TeX, it is produced by simply typing 'O' inside math mode. Unlike Greek-named Bachmann–Landau notations, it needs no special symbol. However, some authors use the calligraphic variant 
  
    
      
        
          
            O
          
        
      
    
    
  
 instead.
The big-O originally stands for "order of" ("Ordnung", Bachmann 1894), and is thus a Latin letter. Neither Bachmann nor Landau ever call it "Omicron". The symbol was much later on (1976) viewed by Knuth as a capital omicron, probably in reference to his definition of the symbol Omega. The digit zero should not be used.

== See also ==
Asymptotic computational complexity
Asymptotic expansion: Approximation of functions by a series, generalizing Taylor's formula
Asymptotically optimal algorithm: A phrase frequently used to describe an algorithm that has an upper bound asymptotically within a constant of a lower bound for the problem
Big O in probability notation: Op, op
Limit inferior and limit superior: An explanation of some of the limit notation used in this article
Master theorem (analysis of algorithms): For analyzing divide-and-conquer recursive algorithms using big O notation
Nachbin's theorem: A precise method of bounding complex analytic functions so that the domain of convergence of integral transforms can be stated
Order of approximation
Order of accuracy
Computational complexity of mathematical operations

== References and notes ==

=== Notes ===

== Further reading ==
Knuth, Donald (1997). "1.2.11: Asymptotic Representations". Fundamental Algorithms. The Art of Computer Programming. Vol. 1 (3rd ed.). Addison-Wesley. ISBN 978-0-201-89683-1.
Sipser, Michael (1997). Introduction to the Theory of Computation. PWS Publishing. pp. 226–228. ISBN 978-0-534-94728-6.
Avigad, Jeremy; Donnelly, Kevin (2004). Formalizing O notation in Isabelle/HOL (PDF). International Joint Conference on Automated Reasoning. doi:10.1007/978-3-540-25984-8_27.
Black, Paul E. (11 March 2005). Black, Paul E. (ed.). "big-O notation". Dictionary of Algorithms and Data Structures. U.S. National Institute of Standards and Technology. Retrieved December 16, 2006.
Black, Paul E. (17 December 2004). Black, Paul E. (ed.). "little-o notation". Dictionary of Algorithms and Data Structures. U.S. National Institute of Standards and Technology. Retrieved December 16, 2006.
Black, Paul E. (17 December 2004). Black, Paul E. (ed.). "Ω". Dictionary of Algorithms and Data Structures. U.S. National Institute of Standards and Technology. Retrieved December 16, 2006.
Black, Paul E. (17 December 2004). Black, Paul E. (ed.). "ω". Dictionary of Algorithms and Data Structures. U.S. National Institute of Standards and Technology. Retrieved December 16, 2006.
Black, Paul E. (17 December 2004). Black, Paul E. (ed.). "Θ". Dictionary of Algorithms and Data Structures. U.S. National Institute of Standards and Technology. Retrieved December 16, 2006.

== External links ==

Growth of sequences — OEIS (Online Encyclopedia of Integer Sequences) Wiki
Introduction to Asymptotic Notations
Big-O Notation – What is it good for
An example of Big O in accuracy of central divided difference scheme for first derivative
A Gentle Introduction to Algorithm Complexity Analysis

*(note truncated for size; full article at the source link below)*

## Related

- [[Analysis of algorithms]]
- [[Best, worst and average case]]
- [[Big O in probability notation]]
- [[Bra–ket notation]]
- [[Combinatorial search]]
- [[Computational complexity]]
- [[Exponentially equivalent measures]]
- [[External memory algorithm]]
- [[Free variables and bound variables]]
- [[Glossary of mathematical symbols]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Big_O_notation