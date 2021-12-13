# Building a nix module for MiniMint

**Description:** MiniMint is an experimental implementation of federated e-cash written in rust. One application is anonymous "community banking", where a few community members operate the mint without any single one having full control while the wider community can use it as an anonymous Bitcoin/Lightning wallet provider.

To make deployment easier having a Nix(OS) module allowing to easily set up a federation would be useful. Nix allows to write entire system configurations as a single configuration file and to reproducibly build that system. As such it is well-suited for security-critical applications.

**Expected Outcomes:**
* Basic understanding of federated e-cash and Bitcoin
* Nix expression that builds the project's binary outputs
* Nix module in (a fork of) nix-bitcoin that allows configuration of a MiniMint federation member/server

**Resources:**
* Federated e-cash resources:
    * [Technical Blockstream announcement blog post](https://medium.com/blockstream/blockstream-sponsors-federated-e-cash-as-a-bitcoin-scaling-technology-637ba05de7b3)
    * [fedimint.org](https://fedimint.org/)
    * [Talk at Adopting Bitcoin](https://bitcointv.com/w/kHwmbLTWjsbaDTJpBewUmX)
* [MiniMint git repo](https://github.com/fedimint/minimint/)
* [NixOS](https://nixos.org/)
* [nix-bitcoin](https://github.com/fort-nix/nix-bitcoin)
* [Getting started with rust](https://www.rust-lang.org/learn/get-started)
* [Telegram channel for any MiniMint related questions](https://t.me/+-AsKtcH4Geo2ZTU0)

**Skills Required:**
* Experience with git
* Using linux and the command line
* Some familiarity with rust
* Familiarity with Nix (still learning myself)

**Mentors:** elsirion ([@EricSirion](https://twitter.com/EricSirion))

**Difficulty:** Medium-Hard

**Competency Test (optional):**
* Install rust, and compile, run tests for MiniMint
* Bonus Strech goal: Being able to run a local federation and client as shown in the [README](https://github.com/fedimint/minimint/)
* Having installed and used NixOS
* Writing an example nix derivation compiling a rust hello-world program

**Similar project idea examples from other organizations:**
