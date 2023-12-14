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

- [Awesome zkEVM](#awesome-zkevm-)
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
    - [Polygon Hermez](#polygon-hermez)
    - [Polygon Zero](#polygon-zero)
    - [zkSync](#zksync)
    - [StarkWare](#starkware)
    - [Zero-Knowledge-Proofs](#zero-knowledge-proofs-1)
    - [Halo2](#halo2-1)
    - [zkp Acceleration](#zkp-acceleration)
    - [zkEVM Applications](#zkevm-applications)
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
* [The different types of ZK-EVMs](https://vitalik.ca/general/2022/08/04/zkevm.html)

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

* [zkEVM-spec](https://github.com/privacy-scaling-explorations/zkevm-specs)
* [zkEVM-circuit](https://github.com/privacy-scaling-explorations/zkevm-circuits)
* [zkEVM-document](https://privacy-scaling-explorations.github.io/zkevm-docs/)
* [Scroll's architecture](https://scroll.mirror.xyz/nDAbJbSIJdQIWqp9kn8J0MVS4s6pYBwHmK7keidQs-k)

### Polygon Hermez

* [Polygon Hermez zkEVM](https://github.com/0xPolygonHermez/zkevm-prover)
* [Hermez document](https://docs.hermez.io/zkEVM/Overview/Overview/)

### Polygon Zero

* [Plonky2](https://github.com/mir-protocol/plonky2)

### zkSync

* [zksync v1](https://github.com/matter-labs/zksync) - zksync v1 source code.
* [compiler-solidity](https://github.com/matter-labs/compiler-solidity) - zkSync v2 compiler.
* [zksync v2 portal](https://portal.zksync.io/) - zksync v2 faucet, Goerli network.

### StarkWare

* [Awesome-starknet](https://github.com/gakonst/awesome-starknet) - A curated list of starkNet resources.
* [Warp:transpile solidity to cairo](https://github.com/NethermindEth/warp)

### Zero-Knowledge-Proofs 

* [Awesome-zkps](https://github.com/matter-labs/awesome-zero-knowledge-proofs) - A curated list of zkps resources.

### Halo2

* [Halo2 repo](https://github.com/zcash/halo2)
* [Halo2 document](https://zcash.github.io/halo2/)
* [Halo2 for PSE and Scroll](https://github.com/privacy-scaling-explorations/halo2)

### zkp Acceleration

* [supranational](https://github.com/supranational)
* [supranational - sppark](https://github.com/supranational/sppark)

### zkEVM Applications

* [light-client](https://github.com/privacy-scaling-explorations/zkevm-circuits/tree/main/light-client-poc)
* [proof-of-exploit](https://github.com/zemse/proof-of-exploit) - Uses PSE/zkEVM to prove knowledge of smart contract vulnerabilities

## Different Solutions

### Native zkEVM

* [PSE (formerly appliedzkp)](https://github.com/privacy-scaling-explorations)
* [Scroll](https://scroll.io/)
* [Polygon Hermez](https://docs.hermez.io/zkEVM/Basic-Concepts/introduction/)
* [Polygon Zero](https://polygon.technology/solutions/polygon-zero/)

### Compiler-Based zkEVM

* [zkSync v2](https://blog.matter-labs.io/zksync-2-0-public-testnet-is-live-de870ba9632a)

### Transpiler-Based zkEVM

* [StarkNet](https://medium.com/starkware/starknet-alpha-2-4aa116f0ecfc)
* [Miden](https://github.com/maticnetwork/miden)

### Other

* [Consensys zkEVM](https://ethresear.ch/t/a-zk-evm-specification/11549)
* [Consensys zkEVM 2.0](https://ethresear.ch/t/a-zk-evm-specification-part-2/13903)

# Contributing

Contributions are very welcome!

Please have a look at [contributing.md](https://github.com/LuozhuZhang/awesome-zkevm/blob/main/contributing.md) for guidelines.
