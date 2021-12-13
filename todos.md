# Fixing TODOs and FIXMEs in MiniMint
**Description:** MiniMint is an experimental implementation of federated e-cash written in rust. One application is anonymous "community banking", where a few community members operate the mint without any single one having full control while the wider community can use it as an anonymous Bitcoin/Lightning wallet provider.

So far it has been developed as a prototype, with many rough edges marked by `TODO` and `FIXME` comments. To get closer to a production-ready version at least some of these need fixing. The project would be choosing appropriate ones, discussing the problem and solution space and implementing solutions to these.

**Expected Outcomes:**
* Deep understanding of MiniMint and good understanding of Bitcoin and Lightning
* Having fewer `TODO` and `FIXME` comments than before because problems were solved

**Resources:**
* Federated e-cash resources:
    * [Technical Blockstream announcement blog post](https://medium.com/blockstream/blockstream-sponsors-federated-e-cash-as-a-bitcoin-scaling-technology-637ba05de7b3)
    * [fedimint.org](https://fedimint.org/)
    * [Talk at Adopting Bitcoin](https://bitcointv.com/w/kHwmbLTWjsbaDTJpBewUmX)
* [Getting started with rust](https://www.rust-lang.org/learn/get-started)
* [MiniMint git repo](https://github.com/fedimint/minimint/)
* [`TODO`s](https://github.com/search?q=org%3Afedimint+TODO&type=code) and [`FIXME`s](https://github.com/search?q=org%3Afedimint+FIXME&type=code)
* [Honey badger BFT used by MiniMint](https://eprint.iacr.org/2016/199.pdf)
* [Telegram channel for any MiniMint related questions](https://t.me/+-AsKtcH4Geo2ZTU0)

**Skills Required:**
* Experience with git
* Using linux and the command line
* Good familiarity with rust, ideally including async (or interest in learning async rust).

**Mentors:** elsirion ([@EricSirion](https://twitter.com/EricSirion))

**Difficulty:** Medium-Hard (depending on chosen issues)

**Competency Test (optional):**
* Install rust, and compile, run tests for MiniMint
* Bonus Strech goal: Being able to run a local federation and client as shown in the [README](https://github.com/fedimint/minimint/)

**Similar project idea examples from other organizations:**
