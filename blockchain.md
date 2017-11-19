# Blockchain

From [Wikipedia](https://en.wikipedia.org/wiki/Blockchain):

> A **blockchain** is a continuously growing list of records, called **blocks**, which are linked and secured using cryptography. Each block contains typically a hash pointer as a link to a previous block, a timestamp and transaction data.

Blockchain can serve as a large world-wide distributed database with no central authority (i.e. decentralized and therefore no single point of failure).

Implementations of Blockchain include [Bitcoin](./bitcoin.md), [Ethereum](./ethereum.md) or [Litecoin](./litecoin.md) with their own **digital currencies**, i.e. BTC, ETH and LTC, respectively.

Earning digital currencies requires that (in technical terms) you have either mined or bought them.

A blockchain acts like a **distributed ledger** that records transactions of any kind (provided it can be described in digital form).

The original white paper [Bitcoin: A Peer-to-Peer Electronic Cash System](https://bitcoin.org/bitcoin.pdf) by **Satoshi Nakamoto** was published on 31 October 2008. It described the Bitcoin network protocol and the distributed architecture, and the reference implementation a year later.

The first well-known blockchain was the Bitcoin blockchain, which is also the name of the first widely-used, decentralised cryptocurrency. Bitcoin also refers to the network protocol underlying the cryptocurrency.

NOTE: The Bitcoin blockchain is often referred as "the Blockchain" but there are other
blockchains such as the [Ethereum blockchain](./ethereum.md).

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
1. the way the blockchain resolves this is with a [consensus algorithm](./consensus-algorithm.md), where eventually there is a majority agreement on which forks should be dropped:
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
    * A [consensus formation algorithm](./consensus-algorithm.md). Note that many enterprise blockchains will not use mining (like Bitcoin) for consensus
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

### European Commission's Blockchain in Education

From the European Commission's [Blockchain in Education](http://publications.jrc.ec.europa.eu/repository/bitstream/JRC108255/jrc108255_blockchain_in_education(1).pdf) document:

1. **Ledgers** are tools by which one can **determine the ownership of an asset at any
point in time**. They perform this function by serving as a **central authoritative list of
transfers of the asset** in question.

1. In a system or society that has agreed to **use a ledger to determine ownership of an asset**, all that is required to transfer ownership between two parties, is to
**make an entry in the ledger indicating that this has happened**.

1. From a technical perspective, a **ledger** is a **list of sequential, time-stamped
transaction entries**, i.e. records.

1. The person or organisation that physically owns or controls a **public ledger** (including the server where the ledger resides, in the case of an online public ledger) is in a position of significant power and influence.
    * decide whether to record a transaction, which in turn provides this person with the
ability to **impose conditions for individuals to have their transactions recorded**
    * decide on the system of controls to be applied to **check the accuracy of those
transactions**
    * **modify or delete transactions** already in the ledger
    * **destroy the ledger** entirely, or allow it to be destroyed

1. Since under such a system, writing, modifying or deleting a transaction in the ledger also changes the ownership of the object, the person or organisation controlling such ledgers also wields significant influence by effectively controlling who owns what - simply by being the custodian of the list of transactions.

1. The responsibility of keeping accurate ledgers has traditionally been assigned to a variety of institutions:
    * governments control ownership of land by controlling ledgers of property
    * banks control the world's monetary system by holding the ledgers for currency
    * stock exchanges control large shares of the business world by holding ledgers for business-ownership.

1. Since capitalist societies are built around the concepts of sale and
ownership (the transfer and accumulation of capital), there are great responsibilities associated with the custodianship of ledgers.

1. Specifically, these central authorities are trusted to:
    * **provide witness** – that is, to certify identity and ensure that the persons being recorded
in the ledger are who they say they are, and that the assets being transferred exist;
    * **be honest and transparent in all transactions** – that is, not to divest users of their assets by creating fake transactions or illegitimately modifying transactions after they have been created;
    * **be secure** – that is, ensure that unauthorized third parties cannot read or write to the ledger (hacking)
    * **not abuse** their monopoly by imposing unfair/exceptional costs on their services
    * **allow persons to transact** – that is, give access to everyone with a legitimate interest to conduct transactions by listing them on the ledger.

1. The corollary is that these institutions may individually or collectively cause significant harm or even social chaos by abusing the trust placed in them to accurately keep and maintain these ledgers. The inference is that these institutions have the power to use or abuse their control over the ledgers and exert significant control over individuals and societies within their immediate remit.

#### Blockchains as Public Ledgers

1. The most widely-known application of a blockchain is as a public ledger of transactions for cryptocurrencies, such as Bitcoin and Ether. As in the case of other public ledgers, the blockchain ledger provides the record of the provenance and transfer of ownership of an asset. The transactional structure of blockchain protocols facilitate not only the transfer of cryptocurrency, but of other digital assets. An asset can be tangible, such as a house, a car, cash, land, or intangible like intellectual property, such as patents, copyrights, or
branding. Virtually anything of value can be tracked and traded on a blockchain network, reducing risk and cutting costs for all involved. Since they are designed to record and preserve transactions, all blockchains have traditionally had a digital currency of some kind associated with them as the most basic asset transacted across the network. This has also incentivized the adoption of that blockchain's protocol by paying
contributors to the network in its own cryptocurrency.

1. Blockchains are therefore ledgers recording groups of transactions, otherwise known as blocks, which are linked together cryptographically in a linear temporal sequence. Other key properties associated with a blockchain - security, immutability, programmability -
depend on the architecture of the blockchain and the character of the [consensus protocol](./consensus-algorithm.md) it runs by that blockchain. Some blockchains are structured to facilitate peer-to-peer transactions across non-hierarchical nodes; this is known as a "“"distributed" network structure. Some blockchains, like the Bitcoin blockchain, also ensure the immutability of their ledgers through their unique consensus protocol.

1. To identify who owns a specific asset, a party needs simply to consult the ledger to check who is its most recent owner.

1. The cryptography at the core of blockchain technology promises to address identity lacunae and "wrestle" the ownership and control of personal data back to the individual user. People, businesses and institutions can store their own identity data on their own devices, and provide it efficiently to those who need to validate it, without relying on a central repository of identity data. Blockchain technology does not just provide a new way of digitising bits of paper which have an intrinsic value, such as our credentials – it provides us with the means to take control of our identity online and manage it appropriately.

1. Blockchain technology might provide a viable alternative to the current procedural, organisational, and technological infrastructure required to create institutionalised trust. The improved trust between stakeholders is associated with the use of decentralised
public ledgers as well as cryptographic algorithms that can guarantee approved transactions cannot be altered after being validated. The distributed ledgers contribute to trust by establishing a fact at a given point in time, which can then be trusted. They achieve this by automating the three roles of the trusted third-party: a) validating; b) safe guarding transactions; and c) then preserving them.

1. Blockchain technology provides an indisputable mechanism to verify that the data of a transaction has existed at a specific time. Moreover, because each block in the chain contains information about the previous block, the history, position and ownership of
each block are automatically authenticated, and cannot be altered. A single, shared ledger provides one place to go to determine the ownership of an asset or the completion of a transaction.

1. An immutable record is an unchangeable record whose state cannot be modified after it is created.

1. Blockchains are typically used to store records of:
  1. asset transactions
  1. smart contracts
  1. digital signatures and certificates

1. Records of transactions of assets typically take two forms:
  — **Money**, expressed in **units of a currency**: each single unit of the same currency has an identical value as every other single unit at any one time. Currencies are also intra-convertible at an exchange rate. The most common form of currency built using blockchain technology is Bitcoin.
  - Documentary evidence of ownership rights, legally known as **title deeds**. These are commonly used to represent immovable property such as land, or intangible property such as intellectual property rights.

1. **Smart contracts** are effectively small computer programmes stored on a blockchain, which will perform a transaction under specified conditions. Thus, a smart contract is typically a declaration such as “transfer X to Y if Z occurs”. Unlike a regular contract where after reaching an agreement, parties must execute the contract for it to take place, a smart contract is self-executing - that is, once the instructions are written to a blockchain, the transaction will take place automatically when the appropriate conditions are detected, with no further actions required by the parties to the transaction or other third parties.

1. Blockchains can be used to either store cryptographic hashes (“digital fingerprints”) of the certificates, or to store the claims themselves. Thus, a blockchain can take on the function of a public certificate registry.

#### High-Level Overview of Blockchain Architecture

A blockchain is a ledger linking sequential “blocks” of transactions whereby:
1. Every person who wishes to trade any asset across a private or public network requires access to the network. This access occurs via a software application that mediates between user and blockchain. The software application, often called a “wallet,” can be installed directly on a device or accessed via a web browser. Depending on how it is designed, a blockchain wallet can be used to send and/or receive digital assets. Some wallets allow for direct transacting without a mediating third-party, while other wallets are run by third parties who maintain custodianship of users' digital assets on their behalf.
1. Those users wishing to participate in validating transactions through consensus must generally to install the blockchain software on their device. This is used to write to the ledger, store an entire copy of the entire ledger and keep all the copies of the ledger perfectly synchronised. Because public blockchains allow anyone to install the software and have a copy of the entire ledger, anyone can transact directly on the Blockchain within the network, and no third parties can impose conditions for access.
    * In permissioned blockchains, a centralized authority determines who has access to run a node and participate in the consensus process.
1. The transaction-records, or blocks, in a blockchain are linked together cryptographically, rendering them tamper-proof. Unlike records in digital databases, which can be altered, once a transaction is recorded and time-stamped on the Blockchain, it is impossible to alter it, or delete it.
1. The blockchain records the fact of the transaction, that is, what has been transferred, the parties involved, as well as structured information (metadata) related to the transaction and a cryptographic hash (“digital fingerprint”) of transaction content. This unique signature is used to verify transactions later: if someone alters the transaction content, its resulting unique code no longer matches the version that is on the chain, and the blockchain software will highlight the discrepancy.
1. All parties involved in a transaction, and only those parties, must provide their consensus before a new transaction record is added to the network. All other nodes in the network will only verify that the two parties have the appropriate capacity to enter into the transaction. Thus, as soon as one party agrees to send the asset, and the other party agrees to receive the asset, and the nodes verify that each party has the capacity to conduct the transaction, it is completed.
1. All computers in the network continually and mathematically verify that their copy of the blockchain is identical to all the other copies on the network. The version running on the majority of computers is assumed to be the ‘real’ version, so the only way to ‘hack’ the records would be to take control of over half of the computers on the network. For a blockchain running on thousands (or even, in the future, millions) of computers, as public blockchains like Bitcoin and Ethereum do, this would-be a near-impossible task. Destroying the ledger entirely would require deleting every copy of it in the world.
