# Awesome zkEVM [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

zkEVM is a Fully EVM equivalent and zk friendly virtual machine.

<div align="center">
  <a href="https://www.artstation.com/artwork/9mEx8a/">
    <img alt="zkevm" src="https://cdna.artstation.com/p/assets/images/images/029/062/442/4k/t-x-7.jpg?1596346307" >
  </a>
  <p align="center">
    <a href="https://github.com/sindresorhus/awesome">
      <img alt="awesome" src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg">
    </a>
    <a href="https://github.com/LuozhuZhang/awesome-zkevm/graphs/contributors">
      <img alt="GitHub contributors" src="https://img.shields.io/github/contributors/LuozhuZhang/awesome-zkevm">
    </a>
    <a href="http://makeapullrequest.com">
      <img alt="pull requests welcome badge" src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat">
    </a>
    <a href="https://twitter.com/LuozhuZhang">
      <img alt="Twitter" src="https://img.shields.io/twitter/url/https/twitter.com/LuozhuZhang.svg?style=social&label=Follow%20%40LuozhuZhang">
    </a>
  </p>
</div>

## Contents

- [Awesome zkEVM ![Awesome](https://github.com/sindresorhus/awesome)](#awesome-zkevm-)
  - [Contents](#contents)
  - [Article - Video](#article---video)
    - [Rollup](#rollup)
    - [zkEVM](#zkevm)
    - [zk-hardware](#zk-hardware)
    - [Zero-Knowledge-Proofs](#zero-knowledge-proofs)
      - [zk-SNARK](#zk-snark)
      - [Plonk](#plonk)
      - [Halo2](#halo2)
  - [Resources - libraries, tools](#resources---libraries-tools)
    - [Early Rollup](#early-rollup)
    - [Scroll and Appliedzkp(PSE)](#scroll-and-appliedzkppse)
    - [Hermez](#hermez)
    - [zkSync](#zksync)
    - [StarkWare](#starkware)
    - [Zero-Knowledge-Proofs](#zero-knowledge-proofs-1)
    - [Halo2](#halo2-1)
    - [zkp Acceleration](#zkp-acceleration)
  - [Different Solutions](#different-solutions)
    - [Native zkEVM](#native-zkevm)
    - [Compiler-Based zkEVM](#compiler-based-zkevm)
    - [Transpiler-Based zkEVM](#transpiler-based-zkevm)
    - [Other](#other)
- [Contributing](#contributing)

## Article - Video

### Rollup

* [An Incomplete Guide to Rollups](https://vitalik.ca/general/2021/01/05/rollup.html) - vitalik, Introducing Rollup.

* [A rollup-centric ethereum roadmap](https://ethereum-magicians.org/t/a-rollup-centric-ethereum-roadmap/4698) - vitalik, rollup-centric ethereum roadmap.

* [How Zk-Rollups Work](https://medium.com/fcats-blockchain-incubator/how-zk-rollups-work-8ac4d7155b0e) - How barry whiteHat's rollup works.

### zkEVM

* [zkEVM](https://hackmd.io/@yezhang/S1_KMMbGt) - Scroll zkEVM.

* [zkEVM Architecture](https://twitter.com/LuozhuZhang/status/1538166119785111552?s=20&t=o9hnHeP1na00u6gldaxnCw) - Scroll & EF zkEVM Architecture.

* [ZKVerse: Deep Dive Into Polygon Hermez 2.0](https://blog.polygon.technology/zkverse-deep-dive-into-polygon-hermez-2-0/) - Deep into zkEVM of polygon hermez.

* [zkEVM circuit arithmetization](https://www.youtube.com/watch?v=DT8g3veR17k&t=910s) - zkEVM circuits and EVM circuit, yezhang.

### zk-hardware

* [Hardware Acceleration for Zero Knowledge Proofs](https://www.paradigm.xyz/2022/04/zk-hardware) - Hardware for ZKPs.

### Zero-Knowledge-Proofs 

#### zk-SNARK

* [Introduction to zk-SNARKs with Examples](https://media.consensys.net/introduction-to-zksnarks-with-examples-3283b554fc3b) - Get started to learn zk-SNARK by example.

* [Why and How zk-SNARK Works](https://medium.com/@imolfar/why-and-how-zk-snark-works-1-introduction-the-medium-of-a-proof-d946e931160) - In-depth SNARK mechanism and understanding.

#### Plonk

* [Understanding PLONK](https://vitalik.ca/general/2019/09/22/plonk.html)

* [ZK Study Club - Plonk with Zac Williamson](https://www.youtube.com/watch?v=NqrVcDuQ8hM)

* [Multiset checks in PLONK and Plookup](https://hackmd.io/@arielg/ByFgSDA7D)

#### Halo2

* [Halo and more: exploring incremental verification and SNARKs without pairings](https://vitalik.ca/general/2021/11/05/halo.html)

## Resources - libraries, tools

### Early Rollup

* [idn3 rollup](https://github.com/iden3/rollup) - iden3 rollup implement.

* [barryWhiteHat rollup](https://github.com/barryWhiteHat/roll_up) - First rollup implemented by [barryWhiteHat](https://github.com/barryWhiteHat).

### Scroll and Appliedzkp(PSE)

* [zkEVM-circuit](https://github.com/appliedzkp/zkevm-circuits) - zkEVM circuit implement.

* [zkEVM-spec](https://github.com/appliedzkp/zkevm-specs) - zkEVM design.

* [zkEVM-document](https://appliedzkp.github.io/zkevm-docs/) - zkEVM (Community Edition) Documentation.

* [zkEVM-chain](https://github.com/appliedzkp/zkevm-chain) - appliedzkp(PSE) L1 contract.

### Hermez

* [Hermez Github](https://github.com/orgs/hermeznetwork/repositories)

### zkSync

* [zksync v1](https://github.com/matter-labs/zksync) - zksync v1 source code.

* [compiler-solidity](https://github.com/matter-labs/compiler-solidity) - zkSync v2 compiler.

* [zksync v2 portal](https://portal.zksync.io/) - zksync v2 faucet, Goerli network.

### StarkWare

* [Awesome-starknet](https://github.com/gakonst/awesome-starknet) - A curated list of starkNet resources.

### Zero-Knowledge-Proofs 

* [Awesome-zkps](https://github.com/matter-labs/awesome-zero-knowledge-proofs) - A curated list of zkps resources.

### Halo2

* [Halo2 repo](https://github.com/zcash/halo2)

* [Halo2 document](https://zcash.github.io/halo2/)

* [Halo2 for PSE and Scroll](https://github.com/privacy-scaling-explorations/halo2)

### zkp Acceleration

* [supranational](https://github.com/supranational)

* [supranational - sppark](https://github.com/supranational/sppark)

## Different Solutions

### Native zkEVM

* [PSE (formerly appliedzkp)](https://github.com/privacy-scaling-explorations)

* [Scroll](https://scroll.io/)

* [Polygon Hermez](https://docs.hermez.io/zkEVM/Basic-Concepts/introduction/)

### Compiler-Based zkEVM

* [zkSync v2](https://blog.matter-labs.io/zksync-2-0-public-testnet-is-live-de870ba9632a)

### Transpiler-Based zkEVM

* [StarkNet](https://medium.com/starkware/starknet-alpha-2-4aa116f0ecfc)

* [Miden](https://github.com/maticnetwork/miden)

### Other

* [Consensys](https://ethresear.ch/t/a-zk-evm-specification/11549)

# Contributing

Contributions are very welcome!

Please have a look at [contributing.md](https://github.com/LuozhuZhang/awesome-zkevm/blob/main/contributing.md) for guidelines.
