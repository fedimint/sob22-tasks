# Secure and Reliable Tor Network Layer for MiniMint
**Description:** MiniMint is an experimental implementation of federated e-cash written in rust. A federation consists of multiple members that run a BFT consensus protocol between each other and is designed to withstand a fraction of the members being malicious. To hide their location from each other (to avoid attacks on peers by malicious members) all communication should happen over an anonymization network. Furthermore, the BFT consensus expects reliable message transmission and failing/rejoining a peer is expensive, thus intermittent loss of connectivity should be handled gracefully by buffering not yet acknowledged messages.

At the moment Tor seems most suitable network, but having an abstraction that could be used to plug in other transport layers like Nym eventually would be nice. The goal of the project is to implement the Tor network layer and as a stretch goal to define a versatile enough interface that can integrate with other anonymization networks.

**Expected Outcomes:**
* General understanding of BFT consensus and federated e-cash
* Creating a Tor network stack inside MiniMint, that
  * gracefully handles disconnects
  * automatically connects/reconnects to peers
  * buffers messages for retransmission
  * Is as low-latency as possible (e.g. intelligent use of sliding window protcol)
  * Stretch goal: measure performance of BFT consensus with Tor
* Stretch goal: define versatile but also maintainable interface for different transport layers

**Resources:**
* Federated e-cash resources:
    * [Technical Blockstream announcement blog post](https://medium.com/blockstream/blockstream-sponsors-federated-e-cash-as-a-bitcoin-scaling-technology-637ba05de7b3)
    * [fedimint.org](https://fedimint.org/)
    * [Talk at Adopting Bitcoin](https://bitcointv.com/w/kHwmbLTWjsbaDTJpBewUmX)
* [Getting started with rust](https://www.rust-lang.org/learn/get-started)
* [MiniMint git repo](https://github.com/fedimint/minimint/)
* [Tor network stack issue](https://github.com/fedimint/minimint/issues/15)
* [Current “network stack” for local testing](https://github.com/fedimint/minimint/blob/master/minimint/src/net/connect.rs#L121)
* [Honey badger BFT used by MiniMint](https://eprint.iacr.org/2016/199.pdf)
* [Telegram channel for any MiniMint related questions](https://t.me/+-AsKtcH4Geo2ZTU0)

**Skills Required:**
* Experience with git
* Using linux and the command line
* Good familiarity with rust, ideally including async (or interest in learning async rust).
* Basic understanding of computer networks and network protocols like TCP/IP, Tor protocol

**Mentors:** elsirion ([@EricSirion](https://twitter.com/EricSirion))

**Difficulty:** Medium-Hard

**Competency Test (optional):**
* Install rust, and compile, run tests for MiniMint
* Bonus Strech goal: Being able to run a local federation and client as shown in the [README](https://github.com/fedimint/minimint/)

**Similar project idea examples from other organizations:**
