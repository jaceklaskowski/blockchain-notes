# Segregated Witness (SegWit)

[Segregated Witness (SegWit)](https://segwit.org/) is a technology designed to increase the capacity of the blockchain (i.e. the amount of transactions that can be made over the network), thereby allowing faster processing of payments, called lightning fast payments.

Quoting Bitcoin Cash's [Frequently Asked Questions](https://www.bitcoincash.org/#faq):

> Segregated Witness or "SegWit" is an unacceptable substitute for increasing the blocksize for several reasons.

> even if used in 100% of transactions, the increase would equate to 1.7MB blocks. Thus, it is a small capacity increase at best.

> the soft fork implementation results in discardable signatures

> it makes future capacity increases more difficult due to bandwidth inefficiency and quadratic hashing attacks which SegWit doesn't solve since an attacker isn't forced to use it.

> For those (and other) reasons, Bitcoin Cash was necessary as a pre-SegWit fork. Segwit will not be adopted.

SegWit has also been supposed to increase the security of the Bitcoin network (but as Bitcoin Cash has showed there was no consensus and [hence the hard fork](./soft-hard-forks.md)).

* [Understanding Segregated Witness](https://segwit.org/understanding-segregated-witness-905cc712c692)
  * Interestingly, while a signature on a physical check takes up maybe 10% of the check, a digital signature in bitcoin takes up more like 50% of the digital check.
  * The first would be to make the box sizes bigger. The second would be to create a new type of check and only give bigger boxes to those who request them.
  * Bitcoin Cash is essentially using this solution by lifting the 1MB block size limit and implementing an 8MB block size instead.
  * SegWit cuts the checks in half and sends everything but the signature to everyone that’s accepting the old, smaller box. We send the larger boxes to everyone that’s accepting the new, larger box.
* http://www.investopedia.com/terms/s/segwit-segregated-witness.asp
  * the digital signature needs to be segregated from the transactions data

## Further Reading and Watching

* [Segregated Witness Explained [Segwit] (Litecoin/Bitcoin)](https://youtu.be/DzBAG2Jp4bg)
