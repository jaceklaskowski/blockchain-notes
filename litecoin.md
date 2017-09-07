# Litecoin Blockchain

1. https://litecoin.com/
1. [litecoin on Reddit](https://www.reddit.com/r/litecoin/)
1. Currency symbols: **LTC** or **XLT**
1. [Direct fork of Bitcoin](https://github.com/litecoin-project/litecoin) and thus similar to Bitcoin
  * full compatibility with the Bitcoin API
1. Experimental digital currency that enables instant payments
1. [Litecoin Core](https://github.com/litecoin-project/litecoin) is the name of an open source project that enables the use of Litecoin currency
  * [Tags](https://github.com/litecoin-project/litecoin/tags) are created regularly to indicate new official, stable release versions of Litecoin Core.
1. Advantages over Bitcoin
  * faster payment transaction confirmation
  * lower transaction costs
1. [SegWit (P2SH) Addresses](https://blog.trezor.io/litecoins-new-p2sh-segwit-addresses-843633e3e707)
  * P2SH stands for "Pay to script hash"
  * Segregated Witness accounts and multisig accounts use these addresses
  * Litecoin changes the format of some of its addresses
  * 3-addresses are deprecated for the possible confusion with Bitcoin’s P2SH addresses
  * The benefit is that you cannot accidentally send litecoins to a Bitcoin address anymore, and vice versa.
  * Instead of beginning with a "3", Litecoin’s P2SH addresses will start with the letter "M".
  * **3-** and **M-** addresses are freely convertible
  * L-addresses are non-P2SH (non-SegWit) addresses and they remain unchanged (Legacy Litecoin accounts)
  * L addresses will always contain non-segwit coins while M addresses will always contain segwit coins.
  * Only M addresses use segwit
  * might take an extended period of time until all vendors, services, merchants, etc. will adjust to this change
  * Some services continue to accept sending transactions to 3-addresses only, while others give you M-addresses and sends only to M-addresses
  * [P2SH Converter](https://litecoin-project.github.io/p2sh-convert/)
1. [Litecoin: Rename mLTC/μLTC to lites/photons](https://github.com/litecoin-project/litecoin/commit/3c0fef0139ba3b5093d1dd66c6bf5c411a41df7a)
  * Units
    * BTC is LTC - Litecoins
    * mBTC is lites - Lites (1 / 1000)
    * uBTC is photons - Photons (1 / 1000000)

## Further Reading and Watching

* [Why would someone invest in Litecoin?](https://www.quora.com/Why-would-someone-invest-in-Litecoin)
