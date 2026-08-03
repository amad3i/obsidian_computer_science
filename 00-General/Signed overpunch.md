---
title: "Signed overpunch"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Signed_overpunch"
wikipedia_categories: ["Computer data", "Computer programming", "History of software", "Punched card"]
related: ["[[Computer programming in the punched card era]]", "[[Garbage (computer science)]]", "[[Nesting (computing)]]", "[[Agnostic (data)]]", "[[AI winter]]", "[[Algorave]]", "[[Asynchronous procedure call]]", "[[Asynchrony (computer programming)]]", "[[Backup]]", "[[Bare machine]]"]
---

# Signed overpunch

In computing, a signed overpunch is a coding scheme which stores the sign of a number by changing (usually) the last digit. It is used in character data on IBM mainframes by languages such as COBOL, PL/I, and RPG. Its purpose is to save a character that would otherwise be used by the sign digit.  The code is derived from the Hollerith Punched Card Code, where both a digit and a sign can be entered in the same card column. It is called an overpunch because the digit in that column has a 12-punch or an 11-punch above it to indicate the sign. The top three rows of the card are called zone punches, and so numeric character data which may contain overpunches is called zoned decimal.
In IBM terminology, the low-order four bits of a byte in storage are called the digit, and the high-order four bits are the zone. The digit bits contain the numeric value 0–9. The zone bits contain either 'F'x, forming the characters 0–9, or the character position containing the overpunch contains a hexadecimal value indicating a positive or negative value, forming a different set of characters. (A, C, E, and F zones indicate positive values, B and D negative).
The PACK instruction on IBM System/360 architecture machines converts the sign of a zoned decimal number when converting to packed decimal,
and the corresponding UNPK instruction will set the correct overpunched sign of its zoned decimal output.

## Related

- [[Computer programming in the punched card era]]
- [[Garbage (computer science)]]
- [[Nesting (computing)]]
- [[Agnostic (data)]]
- [[AI winter]]
- [[Algorave]]
- [[Asynchronous procedure call]]
- [[Asynchrony (computer programming)]]
- [[Backup]]
- [[Bare machine]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Signed_overpunch