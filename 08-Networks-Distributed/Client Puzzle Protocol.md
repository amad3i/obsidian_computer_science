---
title: "Client Puzzle Protocol"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Client_Puzzle_Protocol"
wikipedia_categories: ["Computer network security"]
related: ["[[3-subset meet-in-the-middle attack]]", "[[ACARM-ng]]", "[[Administrative domain]]", "[[AEGIS SecureConnect]]", "[[Anomaly-based intrusion detection system]]", "[[Application Defined Network]]", "[[Application-level gateway]]", "[[Attack tree]]", "[[Authentication server]]", "[[Banner grabbing]]"]
---

# Client Puzzle Protocol

Client Puzzle Protocol (CPP) is a computer algorithm for use in Internet communication, whose goal is to make abuse of server resources infeasible. It is an implementation of a proof-of-work system (PoW).
The idea of the CPP is to require all clients connecting to a server to correctly solve a mathematical puzzle before establishing a connection, if the server is under attack. After solving the puzzle, the client would return the solution to the server, which the server would quickly verify, or reject and drop the connection. The puzzle is made simple and easily solvable but requires at least a minimal amount of computation on the client side.  Legitimate users would experience just a negligible computational cost, but abuse would be deterred:  those clients that try to simultaneously establish a large number of connections would be unable to do so because of the computational cost (time delay).  This method holds promise in fighting some types of spam as well as other attacks like denial-of-service.

## Related

- [[3-subset meet-in-the-middle attack]]
- [[ACARM-ng]]
- [[Administrative domain]]
- [[AEGIS SecureConnect]]
- [[Anomaly-based intrusion detection system]]
- [[Application Defined Network]]
- [[Application-level gateway]]
- [[Attack tree]]
- [[Authentication server]]
- [[Banner grabbing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Client_Puzzle_Protocol