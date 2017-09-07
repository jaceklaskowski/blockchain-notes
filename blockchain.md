# Blockchain

A **blockchain** is a peer-to-peer distributed software network that acts like a large world-wide database with no central authority (thus no single point of failure).

Managing transactions and issuing money are carried out collectively by the network

  * a protocol and ledger for building an immutable historical record of transactions
  * a data structure which serves as the distributed back-end database
  * Makes use of cryptography to securely host applications, store data, and easily transfer digital instruments of value that represent real-world money.
  * a network database that can reconcile the order of transactions (even when a few nodes on the network receive transactions in various order due to network latency)
  * a system with **asymmetric cryptography** to create a set of credentials for your account, to ensure that only you can transfer your tokens
  * a system with **cryptographic hashing** = a small, unique "fingerprint" for any data, allowing quick comparison of large datasets and a secure way to verify that data has not been altered
      * in both Bitcoin and Ethereum, the Merkle tree data structure is used to record the canonical order of transactions
      * **Merkle tree** = hashes of hashes = tree of hashes
  * creating applications enabling users to make transactions
  * gives you the chance to create decentralized networks

1. Implementations of Blockchain: Bitcoin, Ethereum, Hyperledger Fabric, Corda, Ripple, Openchain...
1. digital currencies (custom blockchains) such as **bitcoin**, **ethereum** or **litecoin**
1. Participants: users, miners, and investors
    * miners = verify transactions on the network
1. [Hard Fork](http://www.investopedia.com/terms/h/hard-fork.asp) (of a protocol)
    * "a new version of the network with different rules than the original"
    * "a permanent divergence from the previous version of the blockchain, and nodes running previous versions will no longer be accepted by the newest version."
    * "a radical change to the protocol that makes previously invalid blocks/transactions valid (or vice-versa), and as such requires all nodes or users to upgrade to the latest version of the protocol software"
    * "A hard fork can be implemented to correct important security risks found in older versions of the software, to add new functionality, or to reverse transactions (as in the case with the hard fork to reverse the hack on the DAO (decentralized autonomous organization) in the Ethereum blockchain)."
    * hard fork is a change of the Bitcoin protocol that is not backwards-compatible
    * a hard fork requires all the digital currency's miners to move to a new blockchain, or version of its transaction history.
1. Whilst the blockchain is an immutable series of blocks, it's still possible for each peer to build up a different set of transaction histories. This divergence is known as **forking**, and is the cause of the consistency problem.
1. the way the blockchain resolves this is with a consensus algorithm, where eventually there is a majority agreement on which forks should be dropped:
1. **Altcoin** (meaning "Bitcoin Alternatives") -- another alternative for financial transactions
    * Bitcoin copycats that use the Bitcoin codebase
1. Blockchain enables the creation of a secure, trusted, peer-to-peer network between partners or public users to build any kind of distributed business application.
1. A blockchain implementation means:
    * Ledgers record transactions – the passing of value from owner to owner
    * Transactions are time based
    * Once a Transaction is recorded you cannot alter it
    * You need to be able to detect if your ledger has been altered
1. **A cryptographic token**, e.g. the Bitcoin (BTC) in the Bitcoin protocol or ether (ETH) for Ethereum
1. Applications deployed to a blockchain consist of a self-executing contract and a client-side application that interfaces with the network through an SDK or API.
1. Components:
    * A data structure called the blockchain which serves as the distributed back-end database
    * A cryptographic token, e.g. the Bitcoin (BTC) in the Bitcoin protocol or ether (ETH) for Ethereum
    * A peer-to-peer network for discovery and communications
    * A consensus formation algorithm. Note that many enterprise blockchains will not use mining (like Bitcoin) for consensus
    * A virtual machine that enables programmable money in Bitcoin and decentralized applications in Ethereum
1. Two popular open blockchain frameworks
    * Both frameworks have different ideas, analogous to the differences between IaaS and PaaS technologies
    * [Hyperledger](https://www.hyperledger.org/) - a collaborative effort created to advance blockchain technology by identifying and addressing important features for a cross-industry open standard for distributed ledgers that can transform the way business transactions are conducted globally. more an Infrastructure as a Service, like Amazon Web Services (AWS) in the public cloud or OpenStack on premise.
    * [Ethereum](https://www.ethereum.org/) - a decentralized platform that runs smart contracts: applications that run exactly as programmed without any possibility of downtime, censorship, fraud or third party interference. ConsenSys is the main company behind Ethereum. more a Platform as a Service, like CloudFoundry or OpenShift.
1. Blockchain-as-a-Service (BaaS) with IBM and Microsoft taking a leading role
1. [Monax](https://monax.io/platform/) (formerly **Eris**)
    * "As of 2017, our platform has been renamed to Monax."
    * "an open platform for developers and devops to build, ship, and run blockchain-based applications for business ecosystems."
    * a Docker-based, blockchain-backed application platform supporting different blockchain frameworks
1. A blockchain infrastructure is its own independent peer-to-peer network without a central backbone
1. **decentralized autonomous companies** (DAOs or DACs)
    * decentralized organization or DO
1. Because a distributed system has no single owner, machines are free to join the Ethereum network at will and begin validating transactions - **mining**
    * Mining nodes confer to arrive at a consensus about the order of transactions across the system, which is necessary to tabulate everyone’s account balances on the fly, even as many transactions pass through the network. This process consumes electricity, which costs money, and so miners are paid a reward for each block they mine: about 5 ether.
    * Miners are paid this ether for mining, and also for running scripts on the network in the form of **gas**
1. **censorship resistance**
1. **cryptoeconomics**
1. "Just as the command line eventually led to a GUI and now virtual reality (VR) applications, it’s up to you to decide what to create with Ethereum."
1. In order to trade dollars for ether, you need to join a cryptocurrency exchange, or buy from a commercial money transmitter such as Coinbase. Most people simply buy bitcoins (which are more widely available in ATM form, and also through the LocalBitcoins.com cash dealer network) and convert them to ether via an exchange or via a cryptomoney-changing service such as ShapeShift.io.
