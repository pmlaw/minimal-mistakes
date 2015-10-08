title: Thinking
date: 2015-07-10 21:49:09
tags:
---
## On coins (the trouble with analogies)

*For purposes of this article "Bitcoin" when capitalized refers to the network of computers operating the p2p payment network whereas "bitcoin" not capitalized refers to the abstract tokens that are transacted across the p2p network.*

Bitcoin is generally used as an electronic transaction network that is designed to settle payment obligations like physical cash transactions - that is quickly, securely and with finality. Other non-financial uses of the bitcoin blockchain also benefit from these same properties.

In practice Bitcoin settles slower than physical cash but faster than most traditional electronic payment methods like wire transfers, ACH transactions or credit cards. Also, unlike physical cash payment obligations settled on the bitcoin network are met with substantially less risk of fraud, theft or counterfeiting than physical cash. Bitcoin is a gross settlement system where settlement on the network is final once a transaction is recorded on the blockchain and the cost of attacking the security of that finality rises exponentially with the addition of each subsequent block added to the blockchain.

Under a formal approach bitcoin doesn't meet any of the standard definitions of a right or property. It's not a security [cite] or contract right [cite] and it doesn't neatly fit the test for intangible personal property [cite]. And, because bitcoin transactions settle like cash but don't involve legal tender, a formal categorization under commercial statutes like the UCC can be awkward.

Faulty assumptions

- 1:: There are discrete and identifiable "coins" that are transferred across the network from on "account" to another

- 2:: That these "coins" are traceable from transaction to transaction through the blockchain "ledger"

Bitcoin uses terms like "wallets" and "coins" to make the system easier to understand for a lay audience in the consumer marketplace. But these abstractions gloss over some important nuances in how the bitcoin system actually works, and there is a hazard for regulators, policymakers and academics who rely on other peoples abstractions and analogies.

If you rely on other peoples analogies you might miss the nuance that makes or breaks your legal argument.

If I were going to use an analogy to describe what a "bitcoin" is, it wouldn't be money and it wouldn't be land. In many ways a "bitcoin" is like a stock certificate. When ownership of a stock certificate changes you deliver the certificate back to the corporation who then reissues a new certificate.

## 1:: This is a bitcoin (The UTXO set)

This is what a "bitcoin" looks like:

```
Script PubKey
    ```
And this is what it looks like in a block:

```
Block content
  ```

There is a UTXO set for a wallet and the global UTXO set for the bitcoin system. The UTXO set reflects the current state of the "ledger", that is all the UTXOs and the conditions associated with them at the moment. The state of the UTXO set may change after each block is broadcast across the network. UTXOs that have had their condition met are removed from the UTXO set.

In fact the size of the UTXO set can fluctuate depending on how consolidated or dissaggregated the UTXOs are. More contracts == more lines on the ledger and a bigger ledger.

No where does the bitcoin system record prior ownership of the "coins" or UTXOs. When UTXOs are combined and dissaggregated through a series of transactions there is no data created or stored about those UTXOs. Like grain in a silo there's no way to ascertain anything about the UTXOs other than the total amount locked in a transaction. At best, people have tried to make educated guesses based on the probability that a UTXO may have belonged to a prior transaction, this is often referred to as coin tainting and it's expressed in percentages - like there's a 32% chance that some UTXOs may have been part of a specific transaction or series of transactions in the past.

## 2:: "Coin" provenance and equity tracing on the bitcoin blockchain

##This is a wallet

A "wallet" is software that helps you create and send transactions. The software combs the UTXO set for outputs that you can consume based on your specific parameters. Most often this is correlating bitcoin addresses and private keys (although not all bitcoin transactions require private keys)


###Nemo Dat Markets and Negotiable Markets
