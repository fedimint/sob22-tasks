# Federate all the things!

**Description:** MiniMint is an experimental implementation of federated e-cash written in rust. It implements a federated on-chain wallet to hold collateral, an e-cash mint and soon(tm) also a module to trustlessly integrate with the Lightning network (basically specilized smart contracts).

But MiniMint is built to be extensible, so these modules do not have to stay the only ones! Do you have any idea for a service that is currently centralized and could be made into a federated consensus system version? Then that would be the project!

The main challenge would probably be figuring out what kind of threshold crypto systems are needed. Feel free to join this [Telegram channel](https://t.me/+-AsKtcH4Geo2ZTU0) to discuss. Ideas for further consensus modules include:

* Simplicity unchained: implementing general-purpose smart contracting using simplicity in the federation
* Federated marketplaces
* Federated exchanges

The project would be very self-directed and has a lot of uncertainty, but can certainly be fun and could lead to great outcomes if successful.

**Expected Outcomes:**
* Deep understanding of BFT consensus, federated e-cash and Bitcoin
* An additional federation module that implements some interesting functionality
* A client for that federation module

**Resources:**
* Federated e-cash resources:
    * [Technical Blockstream announcement blog post](https://medium.com/blockstream/blockstream-sponsors-federated-e-cash-as-a-bitcoin-scaling-technology-637ba05de7b3)
    * [fedimint.org](https://fedimint.org/)
    * [Talk at Adopting Bitcoin](https://bitcointv.com/w/kHwmbLTWjsbaDTJpBewUmX)
* [Getting started with rust](https://www.rust-lang.org/learn/get-started)
* [MiniMint git repo](https://github.com/fedimint/minimint/)
* [Honey badger BFT used by MiniMint](https://eprint.iacr.org/2016/199.pdf)
* [Telegram channel for any MiniMint related questions](https://t.me/+-AsKtcH4Geo2ZTU0)

**Skills Required:**
* Experience with git
* Using linux and the command line
* Good familiarity with rust
* Familiarity with (asymmetric) cryptography, shamir secret sharing and ideally threshold schemes

**Mentors:** elsirion ([@EricSirion](https://twitter.com/EricSirion))

**Difficulty:** Hard

**Competency Test (optional):**
* Install rust, and compile, run tests for MiniMint
* Bonus Strech goal: Being able to run a local federation and client as shown in the [README](https://github.com/fedimint/minimint/)

**Similar project idea examples from other organizations:**
