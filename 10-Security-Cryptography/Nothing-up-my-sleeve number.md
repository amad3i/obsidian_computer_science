---
title: "Nothing-up-my-sleeve number"
tags: ["cs", "security-cryptography", "intermediate"]
domain: Security & Cryptography
level: intermediate
source: "https://en.wikipedia.org/wiki/Nothing-up-my-sleeve_number"
wikipedia_categories: ["Cryptography", "Random number generation", "Transparency (behavior)"]
related: ["[[Hardware random number generator]]", "[[Non-physical true random number generator]]", "[[123 Reg]]", "[[Accumulator (cryptography)]]", "[[Adaptive redaction]]", "[[Advanced Encryption Standard]]", "[[Algorithmic transparency]]", "[[Alice and Bob]]", "[[Anonymous matching]]", "[[Anonymous remailer]]"]
---

# Nothing-up-my-sleeve number

In cryptography, nothing-up-my-sleeve numbers are any numbers which, by their construction, are above suspicion of hidden properties. They are used in creating cryptographic functions such as hashes and ciphers.  These algorithms often need randomized constants for mixing or initialization purposes. The cryptographer may wish to pick these values in a way that demonstrates the constants were not selected for a nefarious purpose, for example, to create a backdoor to the algorithm. These fears can be allayed by using numbers created in a way that leaves little room for adjustment.  An example would be the use of initial digits from the number π as the constants. Using digits of π millions of places after the decimal point would not be considered trustworthy because the algorithm designer might have selected that starting point because it created a secret weakness the designer could later exploit—though even with natural-seeming selections, enough entropy exists in the possible choices that the utility of these numbers has been questioned.
Digits in the positional representations of real numbers such as π, e, and irrational roots are believed to appear with equal frequency (see normal number). Such numbers can be viewed as the opposite extreme of Chaitin–Kolmogorov random numbers in that they appear random but have very low information entropy. Their use is motivated by early controversy over the U.S. Government's 1975 Data Encryption Standard, which came under criticism because no explanation was supplied for the constants used in its S-box (though they were later found to have been carefully selected to protect against the then-classified technique of differential cryptanalysis). Thus a need was felt for a more transparent way to generate constants used in cryptography.

"Nothing up my sleeve" is a phrase associated with magicians, who sometimes preface a magic trick by holding open their sleeves to show they have no objects hidden inside.

## Related

- [[Hardware random number generator]]
- [[Non-physical true random number generator]]
- [[123 Reg]]
- [[Accumulator (cryptography)]]
- [[Adaptive redaction]]
- [[Advanced Encryption Standard]]
- [[Algorithmic transparency]]
- [[Alice and Bob]]
- [[Anonymous matching]]
- [[Anonymous remailer]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Nothing-up-my-sleeve_number