# Improving MiniMint's test coverage

**Description:** MiniMint is an experimental implementation of federated e-cash written in rust. A federation consists of multiple members that run a BFT consensus protocol between each other and is designed to withstand a fraction of the members being malicious. This means that it has to withstand faulty inputs from malicious peers.

Since MiniMint has been mostly a prototype, test coverage is poor. Ideally there would be unit, integration and fuzz tests for federation modules (wallet, mint), and more complex test setups consisting of an entire federation and clients (there is currently one run in CI). For some of these goals interfaces need to be more clearly defined to properly mock out parts of the stack. The project would include any subset of these things you feel comfortable with and can be adapted as we go.

**Expected Outcomes:**
* Deep understanding of federated e-cash, general understanding of Bitcoin
* Extended test coverage of MiniMint
* Stretch goal: increasing testability through improved interfaces (=use of traits)
* Stretch goal: fuzz testing of federation modules

**Resources:**
* Federated e-cash resources:
    * [Technical Blockstream announcement blog post](https://medium.com/blockstream/blockstream-sponsors-federated-e-cash-as-a-bitcoin-scaling-technology-637ba05de7b3)
    * [fedimint.org](https://fedimint.org/)
    * [Talk at Adopting Bitcoin](https://bitcointv.com/w/kHwmbLTWjsbaDTJpBewUmX)
* [Getting started with rust](https://www.rust-lang.org/learn/get-started)
* [MiniMint git repo](https://github.com/fedimint/minimint/)
* [Current only real integration test](https://github.com/fedimint/minimint/blob/master/scripts/integrationtest.sh)
* [Telegram channel for any MiniMint related questions](https://t.me/+-AsKtcH4Geo2ZTU0)

**Skills Required:**
* Experience with git
* Using linux and the command line
* Familiarity with rust, ideally including async (or interest in learning async rust).

**Mentors:** elsirion ([@EricSirion](https://twitter.com/EricSirion))

**Difficulty:** Easy-Hard (depending on scope)

**Competency Test (optional):**
* Install rust, and compile, run tests for MiniMint
* Bonus Strech goal: Being able to run a local federation and client as shown in the [README](https://github.com/fedimint/minimint/)

**Similar project idea examples from other organizations:**
