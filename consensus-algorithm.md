# Consensus Algorithm / Protocol

Every blockchain to function on a global scale with a shared public ledger needs a functional, efficient and secure consensus algorithm.

A **consensus algorithm** (e.g. Bitcoin's Proof of Work) does two things:

1. Ensures that the next block in a blockchain is the one and only version of the truth
1. Keeps powerful adversaries from derailing the system and successfully forking the chain

In [proof of work](./proof-of-work.md), miners compete to add the next block (a set of transactions) in the chain by racing to solve an extremely difficult cryptographic puzzle. The first to solve the puzzle, wins the lottery. As a reward for the efforts, the miner receives 12.5 newly minted bitcoins – and a small transaction fee.

Common criticisms of Proof of Work consensus protocol include:

1. Requires enormous amounts of computational energy
1. Does not scale well (transaction confirmation takes about 10-60 minutes)
1. Majority of mining is centralized in areas of the world where electricity is cheap

## Further Reading

1. Coindesk's [A (Short) Guide to Blockchain Consensus Protocols](https://www.coindesk.com/short-guide-blockchain-consensus-protocols/)
