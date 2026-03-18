# Awesome Simplicity [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of resources, tools, libraries, and projects related to [Simplicity](https://github.com/ElementsProject/simplicity) and SimplicityHL — the low-level and high-level blockchain scripting languages designed for safe, expressive smart contracts.

Simplicity is a typed, combinator-based functional language for cryptocurrencies. SimplicityHL is a higher-level language that compiles to Simplicity, making it more accessible to developers.

---

## Contents

- [Official](#official)
- [Documentation](#documentation)
- [Libraries](#libraries)
- [SimplicityHL](#simplicityhl)
- [Simplicity Unchained](#simplicity-unchained)
- [Tools](#tools)
- [Wallets](#wallets)
- [Projects](#projects)
- [Papers & Research](#papers--research)

---

## Official

- [BlockstreamResearch/simplicity](https://github.com/BlockstreamResearch/simplicity) - The canonical Simplicity implementation in Haskell, C, and Coq, by Blockstream/Elements Project.
- [rust-simplicity](https://github.com/BlockstreamResearch/rust-simplicity) - Official Rust implementation of Simplicity, supporting encoding, decoding, type-checking, and execution. Includes `simplicity-sys`, FFI bindings to the C library.

## Documentation

- [SimplicityHL Documentation](https://docs.simplicity-lang.org) - Official language reference and guides for SimplicityHL.



## SimplicityHL

> Higher-level languages and compilers that target Simplicity.

- [BlockstreamResearch/simplicityhl](https://github.com/BlockstreamResearch/simplicityhl) - A high-level language for writing Bitcoin smart contracts that compiles to Simplicity, with Rust-inspired syntax.
- [SimplicityHL Examples](https://github.com/BlockstreamResearch/SimplicityHL/tree/master/examples) - Lots of example programs written in SimplicityHL, including fee bumps, vaults, and covenants.

## Simplicity Unchained

> Simplicity Unchained is an initiative by Blockstream Research to make Simplicity accessible on a public testnet, enabling developers to write, deploy, and experiment with Simplicity smart contracts without running a local node.

- [Simplicity Unchained Testnet](https://testnet.simplicity-unchained.blockstream.com/) - Public testnet for deploying and interacting with Simplicity smart contracts in a live environment.
- [simplicity-unchained](https://github.com/BlockstreamResearch/simplicity-unchained) - Core tooling and infrastructure for the Simplicity Unchained testnet, including node configuration and contract deployment utilities.
- [simplicity-unchained-web-demo](https://github.com/BlockstreamResearch/simplicity-unchained-web-demo) - Browser-based demo for writing and executing Simplicity programs on the testnet, useful for learning and prototyping without a local setup.

## Tools

### Compilers

- [BlockstreamResearch/simplicityhl](https://github.com/BlockstreamResearch/simplicityhl) - Official SimplicityHL compiler, builds projects into Simplicity bytecode.
- [simfony-cli](https://github.com/starkware-bitcoin/stark-symphony/tree/master/simfony-cli) - SimplicityHL compiler by StarkWare. Supports run, build, test, and deploy. (possibly unmaintained)
- [simply](https://github.com/starkware-bitcoin/simply) - Another SimplicityHL compiler by StarkWare. Supports run, build, and deploy.(possibly unmaintained)
- [go-simplicity](https://github.com/0ceanSlim/go-simplicity) - Transpiler that converts Go code into SimplicityHL, letting developers write Bitcoin/Elements smart contracts in idiomatic Go syntax.

### Frameworks & SDKs

- [smplx](https://github.com/BlockstreamResearch/smplx) - A blazingly-fast, UX-first Simplicity development framework in Rust, offering a CLI (`simplex`), SDK, and local Liquid regtest environment for building, testing, and deploying smart contracts on Liquid.

### IDE

- [simplicity-webide](https://ide.simplicity-lang.org/) - Web IDE for SimplicityHL. ([source](https://github.com/BlockstreamResearch/simplicity-webide))

### Helpers

- [simplicity-hal](https://github.com/BlockstreamResearch/hal-simplicity) - Extension of the [hal](https://github.com/stevenroose/hal) CLI tool with Simplicity and Elements support.
- [asdf-simc](https://github.com/stringhandler/asdf-simc) - [asdf](https://asdf-vm.com) plugin for managing SimplicityHL compiler versions.
- [VS Code Extension](https://marketplace.visualstudio.com/items?itemName=Simplicity.simplicityhl) - Syntax highlighting for SimplicityHL in Visual Studio Code. ([source](https://github.com/BlockstreamResearch/SimplicityHL/tree/master/vscode))

## Wallets

- [simfony-wallet](https://github.com/starkware-bitcoin/stark-symphony/tree/master/simfony-wallet) - Liquid Bitcoin wallet with Simplicity support, by StarkWare. (possibly unmaintained)
- [simpiwallet](https://github.com/uncomputable/simpiwallet/) - Liquid Bitcoin wallet with Simplicity support (abandoned).

## Projects

> Applications and protocols built using Simplicity smart contracts.

- [deadcat](https://github.com/Resolvr-io/deadcat) - Desktop app for trading binary prediction markets on the Liquid Network, using Simplicity covenants for on-chain settlement.
- [fadroma](https://github.com/hackbg/fadroma) - Cross-chain dApp development framework with SimplicityHL integration for Bitcoin, Liquid, and Elements, built in TypeScript/Rust on the Deno runtime.
- [simf](https://github.com/hackbg/simf) - Standalone WebAssembly SDK for compiling, deploying, and executing SimplicityHL smart contracts from any JavaScript/TypeScript environment.
- [simf-app](https://github.com/hackbg/simf-app) - Prototype escrow, vault, and oracle application on Elements using SimplicityHL, demonstrating fund locking with conditions tied to external data attestations.
- [stark-symphony / stark101](https://github.com/starkware-bitcoin/stark-symphony/tree/master/stark101) - STARK verifier implemented in SimplicityHL, by StarkWare.
- [stark-symphony / stwo-verifier](https://github.com/starkware-bitcoin/stark-symphony/tree/master/stwo-verifier) - STWO verifier implemented in SimplicityHL, by StarkWare.

## Papers & Research

- [Simplicity: A New Language for Blockchains](https://arxiv.org/abs/1711.03028) - Russell O'Connor's foundational paper (2017).
- [Building STARKs in Simplicity](https://starkware.co/blog/building-starks-in-simplicity/) - StarkWare blog post on implementing STARK proof systems using Simplicity.


---

## Acknowledgements

- [distributed-lab/awesome-simplicity](https://github.com/distributed-lab/awesome-simplicity) - A prior awesome list that informed several entries in this one.

## Contributing

Contributions welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first, or just open a PR with a link and a short description. Items should be actively maintained, notable, or meaningfully useful to the Simplicity ecosystem.
