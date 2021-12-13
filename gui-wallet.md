# Graphical Wallet for MiniMint using WASM

**Description:** MiniMint is an experimental implementation of federated e-cash written in rust. It allows users to eachange Bitcoin (both Lightning and on-chain) for e-cash notes, the BTC representing the notes are stored in the federation’s multisig wallet. E-cash notes are fully anonymous and can be in turn transferred or exchanged for on-chain Bitcoin or payments of Lightning inovices. In short, it is a new Layer 2 on Bitcoin with a novel privacy/trust trade-off.

For a user to interact with a federation they need a client (wallet). Currently, there is only a CLI client, which is rather inconvenient. The project is to compile the client library to WASM and building a web wallet using it. Stretch goal: make it work as an android app.

**Expected Outcomes:**
* General understanding of federated e-cash, Bitcoin and Lightning
* Creating a graphical Wallet for MiniMint using WASM, that
  * lets the user select a federation to connect to
  * can scan QR codes containing Lightning invoices
  * allows the user to send Lightning payments
  * allows creating Lightning invoices and displaying them as QR codes
  * shows the user’s balance
* stretch goal: package as APK

**Resources:**
* Federated e-cash resources:
  * [Technical Blockstream announcement blog post](https://medium.com/blockstream/blockstream-sponsors-federated-e-cash-as-a-bitcoin-scaling-technology-637ba05de7b3)
  * [fedimint.org](https://fedimint.org/)
  * [Talk at Adopting Bitcoin](https://bitcointv.com/w/kHwmbLTWjsbaDTJpBewUmX)
* [Getting started with rust](https://www.rust-lang.org/learn/get-started)
* [Rust WASM tutorial](https://rustwasm.github.io/docs/book/introduction.html)
* [MiniMint git repo](https://github.com/fedimint/minimint/)
* [Telegram channel for any MiniMint related questions](https://t.me/+-AsKtcH4Geo2ZTU0)

**Skills Required:**
* Experience with git
* Using linux and the command line
* Good familiarity with rust, ideally including WASM bindings (or interest in learning to use rust with WASM).
* Familiarity with any web stack that allows building GUIs and integrating with WASM (can’t really help with that)

**Mentors:** elsirion ([@EricSirion](https://twitter.com/EricSirion))

**Difficulty:** Medium

**Competency Test (optional):**
* Install rust, and compile, run tests for MiniMint
* Bonus Strech goal: Being able to run a local federation and client as shown in the [README](https://github.com/fedimint/minimint/)
* Integrating an example rust function (anything really) with your web stack of choice using WASM

**Similar project idea examples from other organizations:**
