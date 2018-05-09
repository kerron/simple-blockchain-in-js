# Blockchain in Javascript

## scriptCoin
This is a simple project written in JavaScript to show the fundamental principles behind how Blockchain technology works.

For this tutorial I'll use currency transactions, similar to that of Bitcoin, but called scriptCoin. However, this is only for demonstrative purposes.

_It is important to note that Blockchain is not the same as Bitcoin. Blockchain is one of the architectural principles on which cryptocurrenies, like Bitcoin, are built._


## What is Blockchain

Blockchain is an immutable, unhackable distributed database of digital information.

It is built on a peer-to-peer network which means that anyone can see what's going on, and it requires no centralised governance to authenticate or settle transactions. This decentralised transparency is fundamental to the blockchain's architecture, in that it creates its security and truthfulness.

### Blocks
It uses state-of-the-art cryptography, to keep a log of all records (i.e transactions), that once accepted onto the Blockchain, cannot be changed. To change the truthfulness of an existing block, a new block needs to be created and accepted by all other truth nodes on the system.

A block is a list of newly generated information. Each block has a hash of the new information and that of the previous block. The hash of the previous block is added to the new block creating a link.

Being transparent ensure nodes on the blockchain can reach an ultimate truth as all records can be verified against other nodes, and further verified against past blocks.

There are two types of operations that can be done on a blockchain, read and write.

### Anonymous and Secure
Users on the Blockchain are anonymous. There isn't any need for Person A to know Person B before initiating a transaction or exchanging information. Everything can be verified by looking at previous blocks to draw a conclusion. This makes the blockchain inherently truthful.

Currently, a common use case for Blockchain technology is to facilitate financial transactions. However, it can be used to store information about who married whom, voting records, identities, and just about any other form of information. You can use the Blockchain to create a virtual representation of yourself, which though it's in the open, it cannot be defrauded or forgotten.
