# Litecoin Blockchain

1. https://litecoin.com/
1. Litecoin's currency symbols **LTC** or **XLT**
1. Direct fork of Bitcoin and thus similar to Bitcoin
   * full compatibility with the Bitcoin API
1. **Segregated Witness (SegWit)**
   * https://segwit.org/
   * [Understanding Segregated Witness](https://segwit.org/understanding-segregated-witness-905cc712c692)
      * Interestingly, while a signature on a physical check takes up maybe 10% of the check, a digital signature in bitcoin takes up more like 50% of the digital check.
      * The first would be to make the box sizes bigger. The second would be to create a new type of check and only give bigger boxes to those who request them.
      * Bitcoin Cash is essentially using this solution by lifting the 1MB block size limit and implementing an 8MB block size instead.
      * SegWit cuts the checks in half and sends everything but the signature to everyone that’s accepting the old, smaller box. We send the larger boxes to everyone that’s accepting the new, larger box.
   * increases the capacity of the blockchain, thereby allowing faster processing of payments, called lightning fast payments
   * http://www.investopedia.com/terms/s/segwit-segregated-witness.asp
      * the digital signature needs to be segregated from the transactions data
1. Advantages over Bitcoin
   * faster payment transaction confirmation
   * lower transaction costs
1. [Why would someone invest in Litecoin?](https://www.quora.com/Why-would-someone-invest-in-Litecoin)
1. [Lightning Network](https://lightning.network/)
   * Lightning is a decentralized network using smart contract functionality in the blockchain to enable instant payments across a network of participants.
   * [The Lightning Network Explained (Litecoin/Bitcoin)](https://youtu.be/MpfvhiqFw7A)
