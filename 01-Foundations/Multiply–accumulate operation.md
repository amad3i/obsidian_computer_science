---
title: "Multiply–accumulate operation"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Multiply–accumulate_operation"
wikipedia_categories: ["Computer arithmetic", "Digital signal processing"]
related: ["[[Logarithmic number system]]", "[[2D adaptive filters]]", "[[2D Z-transform]]", "[[2Sum]]", "[[Adaptive equalizer]]", "[[Adaptive filter]]", "[[Adaptive predictive coding]]", "[[Adaptive-additive algorithm]]", "[[Adjoint filter]]", "[[Advanced process control]]"]
---

# Multiply–accumulate operation

In computing, especially digital signal processing, the multiply–accumulate (MAC) or multiply–add (MAD) operation is a common step that computes the product of two numbers and adds that product to an accumulator.  The hardware unit that performs the operation is known as a multiplier–accumulator (MAC unit); the operation itself is also often called a MAC or a MAD operation.  The MAC operation modifies an accumulator a:

  
    
      
        a
        ←
        a
        (
        b
        c
      
    
    
  

When done with floating-point numbers, it might be performed with two roundings (typical in many DSPs), or with a single rounding.  When performed with a single rounding, it is called a fused multiply–add (FMA) or fused multiply–accumulate (FMAC).
Modern computers may contain a dedicated MAC, consisting of a multiplier implemented in combinational logic followed by an adder and an accumulator register that stores the result. The output of the register is fed back to one input of the adder, so that on each clock cycle, the output of the multiplier is added to the register. Combinational multipliers require a large amount of logic, but can compute a product much more quickly than the method of shifting and adding typical of earlier computers. Percy Ludgate was the first to conceive a MAC in his Analytical Machine of 1909, and the first to exploit a MAC for division (using multiplication seeded by reciprocal, via the convergent series (1+x)−1). The first modern processors to be equipped with MAC units were digital signal processors, but the technique is now also common in general-purpose processors.

## Related

- [[Logarithmic number system]]
- [[2D adaptive filters]]
- [[2D Z-transform]]
- [[2Sum]]
- [[Adaptive equalizer]]
- [[Adaptive filter]]
- [[Adaptive predictive coding]]
- [[Adaptive-additive algorithm]]
- [[Adjoint filter]]
- [[Advanced process control]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Multiply–accumulate_operation