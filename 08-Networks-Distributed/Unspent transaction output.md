---
title: "Unspent transaction output"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Unspent_transaction_output"
wikipedia_categories: ["Computer security", "Cryptocurrencies", "Distributed computing"]
related: ["[[Hedera (distributed ledger)]]", "[[2018 Google data breach]]", "[[2024 National Public Data breach]]", "[[ActivityPub]]", "[[Adrozek]]", "[[Adversarial machine learning]]", "[[Airdrop (cryptocurrency)]]", "[[Algorand]]", "[[Algorithmic Contract Types Unified Standards]]", "[[AmbaCoin]]"]
---

# Unspent transaction output

In cryptocurrencies, an unspent transaction output (UTXO, often capitalized as UTxO) is a distinctive element in a subset of digital currency models. A UTXO represents a certain amount of cryptocurrency that has been authorized by a sender and is available to be spent by a recipient. The utilization of UTXOs in transaction processes is a key feature of many cryptocurrencies, but it primarily characterizes those implementing the UTXO model.
UTXOs employ public key cryptography to ascertain and transfer ownership. More specifically, the recipient's public key is formatted into the UTXO, thereby limiting the capability to spend the UTXO to the account that can demonstrate ownership of the corresponding private key. A valid digital signature associated with the public key must be included for the UTXO to be spent.
In the UTXO model, each unit of currency is treated as a discrete object. The history of a UTXO is documented only within the blocks where it is transferred. To ascertain the total balance of an account, one must scan each block to find the latest UTXOs linked to that account. While all nodes within a blockchain network must consent to the block history, the blocks relevant to an account's balance are unique to that account.
UTXOs constitute a chain of ownership depicted as a series of digital signatures dating back to the coin's inception, regardless of whether the coin was minted via mining, staking, or another procedure determined by the cryptocurrency protocol.
The UTXO model was invented for Bitcoin. Cardano uses an extended version of the UTXO model known as EUTXO.

## Related

- [[Hedera (distributed ledger)]]
- [[2018 Google data breach]]
- [[2024 National Public Data breach]]
- [[ActivityPub]]
- [[Adrozek]]
- [[Adversarial machine learning]]
- [[Airdrop (cryptocurrency)]]
- [[Algorand]]
- [[Algorithmic Contract Types Unified Standards]]
- [[AmbaCoin]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Unspent_transaction_output