# Protocol versions (changelog)

Peercoin protocol versions do not represent Peercoin client versions, however client hosted at www.github.com/peercoin/peercoin is considered Peercoin reference implementation.
Peercoin protocol version are marked using the following format:

`v{major_version}.{minor_version}`

where:

* v is prefix (stands for "version")
* major_version is for capital improvements to the core concepts or complete redesigns
* minor_version is for evolutions of the protocol defined in the original whitepaper

## v0.6

> released: 25.10.2017

> type: softfork

 - BIP34: block height in coinbase
 - BIP65: OP_CHECKLOCKTIMEVERIFY


## v0.7

> relased: 22.01.2019

> type: hardfork

* [rfc-0007](https://github.com/peercoin/rfcs/blob/master/text/0007-round-transaction-fees-up-to-0.001/0007-round-transaction-fees-up-to-0.001.md)
* [rfc-0008](https://github.com/peercoin/rfcs/blob/master/text/0008-increase-op-return-size-limit/0008-increase-op-return-size-limit.md)


## v0.8

> relased: 29.07.2019

> type: hardfork

* rebase to bitcoin-core 0.16.3
* Compact blocks support (BIP152) with upgraded protocol version to 70015
* HD wallet support (BIP32)
* [rfc-0006](https://github.com/peercoin/rfcs/blob/master/text/0006-remove-pow-block-signature/0006-remove-pow-block-signature.md)
* mainnet fork is scheduled for 1st of October 2019, activating BIPS 62, 68, 112, 113 and 141