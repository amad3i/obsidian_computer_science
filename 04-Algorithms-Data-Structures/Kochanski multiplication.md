---
title: "Kochanski multiplication"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Kochanski_multiplication"
wikipedia_categories: ["Cryptographic algorithms", "Modular arithmetic"]
related: ["[[Modular exponentiation]]", "[[Montgomery modular multiplication]]", "[[Automorphic number]]", "[[B92 protocol]]", "[[Bach's algorithm]]", "[[BB84]]", "[[Beaufort cipher]]", "[[Block cipher mode of operation]]", "[[CDMF]]", "[[Ciphertext stealing]]"]
---

# Kochanski multiplication

Kochanski multiplication is an algorithm that allows modular arithmetic (multiplication or operations based on it, such as exponentiation) to be performed efficiently when the modulus is large (typically several hundred bits). This has particular application in number theory and in cryptography: for example, in the RSA cryptosystem and Diffie–Hellman key exchange.
The most common way of implementing large-integer multiplication in hardware is to express the multiplier in binary and enumerate its bits, one bit at a time, starting with the most significant bit, perform the following operations on an accumulator:

Double the contents of the accumulator (if the accumulator stores numbers in binary, as is usually the case, this is a simple "shift left" that requires no actual computation).
If the current bit of the multiplier is 1, add the multiplicand into the accumulator; if it is 0, do nothing.
For an n-bit multiplier, this will take n clock cycles (where each cycle does either a shift or a shift-and-add).
To convert this into an algorithm for modular multiplication, with a modulus r, it is necessary to subtract r conditionally at each stage:

Double the contents of the accumulator.
If the result is greater than or equal to r, subtract r. (Equivalently, subtract r from the accumulator and store the result back into the accumulator if and only if it is non-negative).
If the current bit of the multiplier is 1, add the multiplicand into the accumulator; if it is 0, do nothing.
If the result of the addition is greater than or equal to r, subtract r. If no addition took place, do nothing.
This algorithm works. However, it is critically dependent on the speed of addition.
Addition of long integers suffers from the problem that carries have to be propagated from right to left and the final result is not known until this process has been completed. Carry propagation can be speeded up with carry look-ahead logic, but this still makes addition very much slower than it needs to be (for 512-bit addition, addition with carry look-ahead is 32 times slower than addition without carries at all).
Non-modular multiplication can make use of carry-save adders, which save time by storing the carries from each digit position and using them later: for example, by computing 111111111111+000000000010 as 111111111121 instead of waiting for the carry to propagate through the whole number to yield the true binary value 1000000000001. That final propagation still has to be done to yield a binary result but this only needs to be done once at the very end of the multiplication.
Unfortunately, the modular multiplication method outlined above needs to know the magnitude of the accumulated value at every step, in order to decide whether to subtract r: for example, if it needs to know whether the value in the accumulator is greater than 1000000000000, the carry-save representation 111111111121 is useless and needs to be converted to its true binary value for the comparison to be made.
It therefore seems that one can have either the speed of carry-save or modular multiplication, but not both.

## Related

- [[Modular exponentiation]]
- [[Montgomery modular multiplication]]
- [[Automorphic number]]
- [[B92 protocol]]
- [[Bach's algorithm]]
- [[BB84]]
- [[Beaufort cipher]]
- [[Block cipher mode of operation]]
- [[CDMF]]
- [[Ciphertext stealing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Kochanski_multiplication