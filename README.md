# Awesome Simplicity [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of resources, tools, libraries, and projects related to [Simplicity](https://github.com/ElementsProject/simplicity) and SimplicityHL — the low-level and high-level blockchain scripting languages designed for safe, expressive smart contracts.

Simplicity is a typed, combinator-based functional language for cryptocurrencies. SimplicityHL is a higher-level language that compiles to Simplicity, making it more accessible to developers.

---

## Contents

- [Official](#official)
- [SimplicityHL](#simplicityhl)
- [Simplicity Unchained](#simplicity-unchained)
- [Projects](#projects)
- [Papers & Research](#papers--research)

---

## Official

- [BlockstreamResearch/simplicity](https://github.com/BlockstreamResearch/simplicity) - The canonical Simplicity implementation in Haskell and C, by Blockstream/Elements Project.
- [rust-simplicity](https://github.com/BlockstreamResearch/rust-simplicity) - Official Rust implementation of Simplicity, supporting encoding, decoding, type-checking, and execution.

## SimplicityHL

> Higher-level languages and compilers that target Simplicity.

- [BlockstreamResearch/simplicityhl](https://github.com/BlockstreamResearch/simplicityhl) - A high-level language for writing Bitcoin smart contracts that compiles to Simplicity, with Rust-inspired syntax.
- [SimplicityHL Examples](https://github.com/BlockstreamResearch/SimplicityHL/tree/master/examples) - Lots of example programs written in SimplicityHL.



## Simplicity Unchained

> Simplicity Unchained is an initiative by Blockstream Research to make Simplicity accessible on a public testnet, enabling developers to write, deploy, and experiment with Simplicity smart contracts without running a local node.

- [Simplicity Unchained Testnet](https://testnet.simplicity-unchained.blockstream.com/) - Public testnet for deploying and interacting with Simplicity smart contracts in a live environment.
- [simplicity-unchained](https://github.com/BlockstreamResearch/simplicity-unchained) - Core tooling and infrastructure for the Simplicity Unchained testnet, including node configuration and contract deployment utilities.
- [simplicity-unchained-web-demo](https://github.com/BlockstreamResearch/simplicity-unchained-web-demo) - Browser-based demo for writing and executing Simplicity programs on the testnet, useful for learning and prototyping without a local setup.

## Projects

> Applications and protocols built using Simplicity smart contracts in production.

- [deadcat](https://github.com/Resolvr-io/deadcat) - Desktop app for trading binary prediction markets on the Liquid Network, using Simplicity covenants for on-chain settlement.
- [fadroma](https://github.com/hackbg/fadroma) - Cross-chain dApp development framework with SimplicityHL integration for Bitcoin, Liquid, and Elements, built in TypeScript/Rust on the Deno runtime.
- [simf](https://github.com/hackbg/simf) - Standalone WebAssembly SDK for compiling, deploying, and executing SimplicityHL smart contracts from any JavaScript/TypeScript environment.
- [simf-app](https://github.com/hackbg/simf-app) - Prototype escrow, vault, and oracle application on Elements using SimplicityHL, demonstrating fund locking with conditions tied to external data attestations.

## Papers & Research

- [Simplicity: A New Language for Blockchains](https://arxiv.org/abs/1711.03028) - Russell O'Connor's foundational paper (2017).
- [Building STARKs in Simplicity](https://starkware.co/blog/building-starks-in-simplicity/) - StarkWare blog post on implementing STARK proof systems using Simplicity.


---

## Contributing

Contributions welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first, or just open a PR with a link and a short description. Items should be actively maintained, notable, or meaningfully useful to the Simplicity ecosystem.
