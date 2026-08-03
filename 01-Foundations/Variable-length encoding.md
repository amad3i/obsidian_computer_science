---
title: "Variable-length encoding"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Variable-length_encoding"
wikipedia_categories: ["Coding theory", "Data compression", "Entropy coding"]
related: ["[[Unary coding]]", "[[Canonical Huffman code]]", "[[Grammar-based code]]", "[[Prefix code]]", "[[Recursive indexing]]", "[[Sardinas–Patterson algorithm]]", "[[Shannon's source coding theorem]]", "[[Algebraic geometry code]]", "[[Alternant code]]", "[[Arbitrarily varying channel]]"]
---

# Variable-length encoding

In coding theory, variable-length encoding is a symbol encoding scheme in which codes of differing lengths are used to encode symbols for representation through a communication channel or in a storage medium. The equivalent concept in computer science is bit string. 
Variable-length codes can allow sources to be compressed and decompressed with zero error (lossless data compression) and still be read back symbol by symbol. An independent and identically-distributed source may be compressed almost arbitrarily close to its entropy. This is in contrast to fixed-length coding methods, for which data compression is only possible for large blocks of data, and any compression beyond the logarithm of the total number of possibilities comes with a finite (though perhaps arbitrarily small) probability of failure.
For these reasons, they were sometimes used to pack English text into fewer bytes in adventure games for early microcomputers. However, disks, increases in computer memory, and general purpose compression algorithms have rendered such methods obsolete.
Multibyte encodings are usually the result of a need to increase the number of characters which can be encoded without breaking backward compatibility with an existing constraint. For example, with one byte (8 bits) per character, one can encode 256 possible characters; in order to encode more than 256 characters, the obvious choice would be to use two or more bytes per encoding unit, two bytes (16 bits) would allow 65,536 possible characters, but such a change would break compatibility with existing systems and therefore might not be feasible at all.
Unlikely source symbols can be assigned longer codewords while likely source symbols can be assigned shorter codewords, thus giving a low expected codeword length. Some examples of well-known variable-length coding strategies are Huffman coding, Lempel–Ziv coding, arithmetic coding, and context-adaptive variable-length coding.

## Related

- [[Unary coding]]
- [[Canonical Huffman code]]
- [[Grammar-based code]]
- [[Prefix code]]
- [[Recursive indexing]]
- [[Sardinas–Patterson algorithm]]
- [[Shannon's source coding theorem]]
- [[Algebraic geometry code]]
- [[Alternant code]]
- [[Arbitrarily varying channel]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Variable-length_encoding