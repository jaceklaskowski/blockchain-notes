## Ethereum Blockchain

* Ethereum's [White Paper](https://github.com/ethereum/wiki/wiki/White-Paper)
* Ethereum is a blockchain where Dapps, tokens or coins can be built upon
* Dapps (Decentralized Applications)
* **ether** - the token / digital currency that powers the ethereum blockchain and is needed to "pay" for blockchain transactions
* alternative asset protocol (to Bitcoin)
* On Ethereum, you develop a so-called Dapp (decentralized app), which consists of two parts: a frontend (written in HTML as web app or any other client using a supported programming language), and a backend (think of it as the ‘database’ for your frontend). A frontend can be a full blockchain peer communicating directly with the backend. The huge benefit here is that every client is a full member of the trusted blockchain network. This is the ideal blockchain world.

1. Ethereum is...
    * http://eth.guide/
    * a single public blockchain, and a protocol for the creation of many blockchains
    * similar to Bitcoin (and often dubbed as _Bitcoin of DAP platforms_)
    * supports **smart contracts**
        * agreements / financial contracts written in computer code that execute automatically when certain conditions are met.
        * some business logic that runs on the network, semi-autonomously moving value and enforcing payment agreements between parties
    * a Turing-complete blockchain = a data structure + [Solidity](./ethereum-solidity.md) built-in programming language
    * The term "Ethereum" can refer to: the **Ethereum protocol**, the **Ethereum network** created by computers using the protocol, and the **Ethereum project** funding development of the aforementioned two.
    * open source blockchain network
    * building economic systems in pure software
    * The Ethereum network functions as one large computer which executes programs in lockstep; it is a machine which is "virtualized" by a network of other machines. Being composed of many private computers, the Ethereum Virtual Machine (EVM) itself can be said to be a shared computer which is ownerless.
    * Changes to the EVM are achieved through hard forking: persuading the entire community of node operators to upgrade to a new version of the Ethereum software.
    * building economic systems in pure software
1. All transactions in Ethereum are stored on the blockchain, a canonical history of state changes stored on every single Ethereum node.
    * When you pay for computing time on the Ethereum network, this includes the cost of running the transaction and for storage of the data included in your smart contract.
    * Because the Ethereum network requires all nodes to keep a full state database of all contracts, any node can query the database locally.
1. **Mist**
    * native Ethereum browser
    * a wallet = holds your ether
    * https://github.com/ethereum/mist
    * With Mist and the Ethereum command-line tools, sample contracts can be tested with fake ether to ensure that you don’t lose any real money while debugging.
1. **Web3.js** - software library
1. **Ethereum protocol** was derived from Bitcoin, and extended
1. [Create your own crypto-currency](https://www.ethereum.org/token)
1. [How to create a Dapp from scratch on Ethereum?](https://ethereum.stackexchange.com/q/122/2491)
1. [Dan's Intro to How Ethereum Works](https://youtu.be/-SMliFtoPn8)
   * Merkle tree used in git
   * Blockchain is an ever-growing Merkle tree
1. [The Ethereum Blockchain Explorer](https://etherchain.org/)
1. [Etherscan is a Block Explorer and Analytics Platform for Ethereum](https://etherscan.io/)
1. [State of the DApps](https://www.stateofthedapps.com/) is a not-for-profit curated directory of Decentralized Applications, also called DApps (pronounced D-Apps) on the Ethereum Blockchain.
   * The video on [State Of The DApps - Joris Bontje, EtherCasts](https://youtu.be/iqBNPh5IMqM)

From [Why I’m short Ethereum (and long Bitcoin)](https://medium.com/@tuurdemeester/why-im-short-ethereum-and-long-bitcoin-aee5b1c198fd):

> The idea behind Ethereum is to move way past digital cash that simply registers transactions in an immutable ledger, such as is the case with Bitcoin. Ethereum’s vision is to build a Virtual Machine, a cloud based decentralized computer. Interfacing with that machine, people can then create strings of code called “smart contracts” or “decentralized applications” and publish these on the Ethereum network. In exchange for a fee, the network will then execute the code for anyone calling on it.

## Platform Updates / Releases

Ethereum is more and more difficult to mine due to planned updates to continue growth and improvement of Ethereum Platform.

1. Frontier
1. Homestead
1. Metropolis
    * includes a hardfork with proof of stake consensus (leaving proof of work consensus)
1. Serenity
