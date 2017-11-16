# Bitcoin Cash (BCC) Hard Fork

**Bitcoin Cash (BCC)** protocol is a hard fork of the Bitcoin protocol with the following features:

1. The **blocksize** limit has been made adjustable, with an increased default of **8MB**
    * the legacy Bitcoin code had a maximum limit of 1MB of data per block (or about 3 transactions per second) that caused issues with the old Bitcoin network's capacity as the time required to confirm transactions grew too much).
    * See Bitcoin Cash's [New Features](https://www.bitcoincash.org/#features) (with some changes)
    * **Adjustable Blocksize Cap (ABC)** in [Bitcoin ABC](https://github.com/Bitcoin-ABC/bitcoin-abc#what-is-bitcoin-abc) fork
1. A new **SigHash transaction signature hashing algorithm** indicated by the flag **SIGHASH_FORKID**
    * Provides replay protection not valid on the old Bitcoin Legacy network
1. Removes [SegWit](./segwit.md), a code change that might activate on the bitcoin blockchain by the end of August.

## Sources

1. The website: https://www.bitcoincash.org
1. [The bitcoin-ml Archives](https://lists.linuxfoundation.org/pipermail/bitcoin-ml)

As a [fork](./soft-hard-forks.md)...Bitcoin Cash's transaction history would be the same as bitcoin's – at least up until the point of the split.

Quoting [Bitcoin Cash](https://www.bitcoincash.org/#about) (with some changes):

> All Bitcoin holders as of block 478558 (August 1st, 2017 about 13:16 UTC) are also owners of Bitcoin Cash and have the same amount of Bitcoin Cash as they had Bitcoin at that time.

The home page of Bitcoin Cash is https://www.bitcoincash.org

The ticker symbol is **BCC/BCH** (the most popular tickers), but **XBC** is used to meet the International Standard for currency codes (ISO 4217).

Some call Bitcoin Cash an **altcoin**, a term that usually denotes a fork of the software that creates a new cryptocurrency, with its own market. (see [Bitcoin Cash: Why It's Forking the Blockchain And What That Means](https://www.coindesk.com/coindesk-explainer-bitcoin-cash-forking-blockchain/))

[Bitcoin Cash on Reddit](https://www.reddit.com/r/Bitcoincash/)

[BitcoinABC](https://www.bitcoinabc.org/) is the first software to implement the Bitcoin Cash protocol, but the goal is to have more implementations (with [Bitcoin Unlimited](https://www.bitcoinunlimited.info/) and [Bitcoin Classic](https://bitcoinclassic.com/) coming up with compatible implementations).

FIXME: What's SigHash?
