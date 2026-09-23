# Awesome zkEVM [![Awesome](https://awesome.re/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of zkEVM projects, research, libraries, and tools.

A zkEVM proves Ethereum Virtual Machine execution using zero-knowledge proof systems. Implementations make different trade-offs in Ethereum compatibility, performance, and proving architecture; not every ZK rollup or zkVM is a zkEVM.

Ecosystem and link maintenance: **September 23, 2026**. Historical resources are labeled below.

<div align="center">
  <a href="https://www.artstation.com/artwork/9mEx8a/">
    <img alt="zkevm" src="https://cdna.artstation.com/p/assets/images/images/029/062/442/4k/t-x-7.jpg?1596346307" >
  </a>
  <p align="center">
    <a href="https://github.com/sindresorhus/awesome">
      <img alt="awesome" src="https://awesome.re/badge.svg">
    </a>
    <a href="https://github.com/LuozhuZhang/awesome-zkevm/graphs/contributors">
      <img alt="GitHub contributors" src="https://img.shields.io/github/contributors/LuozhuZhang/awesome-zkevm">
    </a>
    <a href="contributing.md">
      <img alt="pull requests welcome badge" src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat">
    </a>
    <a href="https://twitter.com/LuozhuZhang">
      <img alt="Twitter" src="https://img.shields.io/twitter/url/https/twitter.com/LuozhuZhang.svg?style=social&label=Follow%20%40LuozhuZhang">
    </a>
  </p>
</div>

## Contents

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
  - [Scroll](#scroll)
  - [Linea](#linea)
  - [Taiko](#taiko)
  - [ZKsync](#zksync)
  - [PSE zkEVM - Historical](#pse-zkevm---historical)
  - [Polygon zkEVM - Historical](#polygon-zkevm---historical)
  - [Polygon Zero and Plonky](#polygon-zero-and-plonky)
  - [Related Non-EVM Systems](#related-non-evm-systems)
  - [Zero-Knowledge-Proofs](#zero-knowledge-proofs-1)
  - [Halo2](#halo2-1)
  - [zkp Acceleration](#zkp-acceleration)
  - [zkEVM Applications](#zkevm-applications)
- [Benchmarks](#benchmarks)
- [Compatibility Guide](#compatibility-guide)
- [Referenced By](#referenced-by)
  - [Official and Project Documentation](#official-and-project-documentation)
  - [Education and Learning Resources](#education-and-learning-resources)
  - [Community Collections and Publications](#community-collections-and-publications)
- [Contributing](#contributing)
- [License](#license)
- [Maintenance](#maintenance)

## Article - Video

### Rollup

* [An Incomplete Guide to Rollups](https://vitalik.eth.limo/general/2021/01/05/rollup.html) - vitalik, Introducing Rollup.
* [A rollup-centric ethereum roadmap](https://ethereum-magicians.org/t/a-rollup-centric-ethereum-roadmap/4698) - vitalik, rollup-centric ethereum roadmap.
* [How Zk-Rollups Work](https://medium.com/fcats-blockchain-incubator/how-zk-rollups-work-8ac4d7155b0e) - How barry whiteHat's rollup works.

### zkEVM

* [zkEVM](https://hackmd.io/@yezhang/S1_KMMbGt) - Historical introduction to Scroll's circuit-based zkEVM.
* [zkEVM Architecture](https://x.com/LuozhuZhang/status/1538166119785111552) - Historical Scroll & EF zkEVM architecture thread.
* [zkEVM circuit arithmetization](https://www.youtube.com/watch?v=DT8g3veR17k&t=910s) - Ye Zhang's explanation of zkEVM circuits and the EVM circuit.
* [The different types of ZK-EVMs](https://vitalik.eth.limo/general/2022/08/04/zkevm.html) - Vitalik Buterin's compatibility taxonomy; project examples reflect 2022.
* [Euclid Upgrade](https://docs.scroll.io/en/technology/overview/scroll-upgrades/euclid-upgrade/) - Scroll's migration from Halo2 circuits to an OpenVM-based prover in 2025.

### zk-hardware

* [Hardware Acceleration for Zero Knowledge Proofs](https://www.paradigm.xyz/writing/zk-hardware) - Hardware for ZKPs.

### Zero-Knowledge-Proofs

#### zk-SNARK

* [An approximate introduction to how zk-SNARKs are possible](https://vitalik.eth.limo/general/2021/01/26/snarks.html) - Vitalik Buterin's introduction to the ideas behind SNARKs.
* [Why and How zk-SNARK Works](https://medium.com/@imolfar/why-and-how-zk-snark-works-1-introduction-the-medium-of-a-proof-d946e931160) - In-depth SNARK mechanism and understanding.

#### Plonk

* [Understanding PLONK](https://vitalik.eth.limo/general/2019/09/22/plonk.html)
* [ZK Study Club - Plonk with Zac Williamson](https://www.youtube.com/watch?v=NqrVcDuQ8hM)
* [Multiset checks in PLONK and Plookup](https://hackmd.io/Iuu9P7S5Sca0TCoYJ-sFdA)

#### Halo2

* [Halo and more: exploring incremental verification and SNARKs without pairings](https://vitalik.eth.limo/general/2021/11/05/halo.html)

## Resources - libraries, tools

### Early Rollup

* [iden3 rollup](https://github.com/iden3/rollup) - Historical rollup implementation by iden3.
* [barryWhiteHat rollup](https://github.com/barryWhiteHat/roll_up) - Early rollup prototype by [barryWhiteHat](https://github.com/barryWhiteHat).

### Scroll

* [Scroll Documentation](https://docs.scroll.io/) - Developer guides and protocol documentation.
* [Scroll zkVM Prover](https://github.com/scroll-tech/zkvm-prover) - Guest programs and prover SDK for Scroll's OpenVM-based proving architecture.
* [OpenVM](https://github.com/openvm-org/openvm) - Modular zkVM framework used by Scroll's prover.

### Linea

* [Linea Documentation](https://docs.linea.build/) - Developer and protocol documentation for the Linea zkEVM network and its underlying Lineth stack.
* [Lineth Monorepo](https://github.com/LFDT-Lineth/lineth-monorepo) - Source for the stack powering Linea, formerly the Linea Stack.

### Taiko

* [Taiko Documentation](https://docs.taiko.xyz/) - Guides and protocol references for Taiko's Ethereum-equivalent based rollup.
* [Taiko Monorepo](https://github.com/taikoxyz/taiko-mono) - Protocol contracts, clients, and supporting tools.

### ZKsync

* [ZKsync Documentation](https://docs.zksync.io/) - Documentation for ZKsync Era, ZK Stack, and ZKsync OS.
* [ZKsync Era](https://github.com/matter-labs/zksync-era) - Source for the EraVM-based ZKsync stack.
* [Era Solidity Compiler](https://github.com/matter-labs/era-compiler-solidity) - Solidity compiler targeting EraVM.
* [EVM Bytecode Interpreter](https://docs.zksync.io/zksync-protocol/era-vm/evm-interpreter/overview) - EVM bytecode execution on EraVM; distinct from compiling Solidity to EraVM bytecode.
* [ZKsync OS](https://github.com/matter-labs/zksync-os) - State-transition implementation with RISC-V proving; see the [Developer Preview documentation](https://docs.zksync.io/zksync-network/zksync-os) for the EVM environment and network status.
* [ZKsync Era Network Details](https://docs.zksync.io/zksync-network/zksync-era/network-details) - Mainnet and Sepolia configuration, replacing the old Goerli faucet entry.
* [ZKsync Lite](https://github.com/matter-labs/zksync) - Historical, non-general-purpose ZK rollup, formerly ZKsync v1; upstream marks it as deprecated.

### PSE zkEVM - Historical

The former AppliedZKP / Privacy & Scaling Explorations repositories below now live under `privacy-ethereum` and are archived. They remain useful for studying the original circuit-based design.

* [zkEVM Specifications](https://github.com/privacy-ethereum/zkevm-specs) - Archived Python specifications.
* [zkEVM Circuits](https://github.com/privacy-ethereum/zkevm-circuits) - Archived Halo2 circuits.
* [zkEVM Documentation Source](https://github.com/privacy-ethereum/zkevm-docs) - Archived documentation source, replacing the unavailable GitHub Pages site.

### Polygon zkEVM - Historical

* [Polygon zkEVM Sunset Status](https://polygon.technology/polygon-zkevm) - Polygon reports that its zkEVM Mainnet Beta sequencer was sunset on July 3, 2026 and the network no longer produces blocks. This status concerns Polygon zkEVM, not Polygon PoS.
* [Polygon zkEVM Prover](https://github.com/0xPolygon/zkevm-prover) - Prover implementation from the former Polygon Hermez stack, retained as a technical reference.

### Polygon Zero and Plonky

* [Polygon Zero zkEVM](https://github.com/0xPolygonZero/zk_evm) - Libraries for proving Ethereum blocks using the Plonky2-based Type 1 zkEVM.
* [Plonky2](https://github.com/0xPolygonZero/plonky2) - Recursive proof library; upstream marks it as deprecated and recommends Plonky3.
* [Plonky3](https://github.com/Plonky3/Plonky3) - Polynomial IOP toolkit for building proof systems; not a complete zkEVM.

### Related Non-EVM Systems

These systems are relevant to ZK research but use their own virtual machines rather than implementing the EVM.

* [Cairo VM](https://github.com/starkware-libs/cairo-vm) - Rust implementation of the Cairo VM used in the Starknet ecosystem.
* [Awesome Starknet](https://github.com/keep-starknet-strange/awesome-starknet) - Curated Starknet resources, libraries, and tools.
* [Warp](https://github.com/NethermindEth/warp) - Archived Solidity-to-Cairo compiler; historical research rather than a maintained integration path.
* [Miden VM](https://github.com/0xMiden/miden-vm) - STARK-based virtual machine, formerly hosted under `maticnetwork/miden`.

### Zero-Knowledge-Proofs

* [Awesome-zkps](https://github.com/matter-labs/awesome-zero-knowledge-proofs) - A curated list of zkps resources.

### Halo2

* [Halo2 repo](https://github.com/zcash/halo2)
* [Halo2 document](https://zcash.github.io/halo2/)
* [PSE Halo2 Fork](https://github.com/privacy-ethereum/halo2) - Archived fork used by the historical PSE / Scroll circuit work.

### zkp Acceleration

* [supranational](https://github.com/supranational)
* [supranational - sppark](https://github.com/supranational/sppark)

### zkEVM Applications

* [Light Client Proof of Concept](https://github.com/privacy-ethereum/zkevm-circuits/tree/8ba838b21ce6164cc2132664f4cd65439f87deb0/light-client-poc) - Historical experiment, pinned to the version before its removal from the PSE repository.
* [Proof of Exploit](https://github.com/proof-of-exploit/cli) - Archived application using PSE zkEVM to prove knowledge of smart-contract vulnerabilities.

## Benchmarks

* [OpenChainBench](https://openchainbench.com/) - Community-run infrastructure benchmarks, including ZKsync Era RPC latency. Check each benchmark's methodology, coverage, and observation date; RPC latency is not proof-generation performance.

## Compatibility Guide

Use [the ZK-EVM compatibility taxonomy](https://vitalik.eth.limo/general/2022/08/04/zkevm.html) together with each project's current documentation. Compatibility and proving backends can evolve independently.

| Area | Resources | What to distinguish |
| --- | --- | --- |
| EVM execution and proving | [Scroll](#scroll), [Linea](#linea), [Taiko](#taiko) | Review each implementation's supported Ethereum behavior and current proving architecture. |
| EraVM and EVM execution | [ZKsync](#zksync) | Solidity-to-EraVM compilation, the EVM interpreter, and ZKsync OS are different execution paths. |
| Historical implementations | [PSE zkEVM](#pse-zkevm---historical), [Polygon zkEVM](#polygon-zkevm---historical) | Archived source or a sunset network can remain useful for research without being a current deployment option. |
| Non-EVM ZK systems | [Cairo / Starknet and Miden](#related-non-evm-systems) | A custom VM or a Solidity transpiler does not make a system EVM-equivalent. |

Historical Consensys design discussions: [A zk EVM specification](https://ethresear.ch/t/a-zk-evm-specification/11549) and [Part 2](https://ethresear.ch/t/a-zk-evm-specification-part-2/13903). For current Linea resources, see [Linea](#linea).

## Referenced By

Known public pages and repositories that link to this list, checked on **September 23, 2026**. Entries describe the specific reference; inclusion alone does not imply endorsement or a software dependency. Translations and copies of the same material are grouped where identified. This directory is non-exhaustive; contributions with a direct reference are welcome.

### Official and Project Documentation

* [ethereum.org — Zero-Knowledge Rollups](https://ethereum.org/developers/docs/scaling/zk-rollups/) - Lists Awesome-zkEVM in its further reading section. Also appears in translated editions, including [Chinese](https://ethereum.org/zh/developers/docs/scaling/zk-rollups/).
* [Gevulot Documentation — zkVMs](https://github.com/gevulotnetwork/gevulot-docs/blob/main/usecases/zkvms.md) - Links to this list when introducing zkEVM implementations; the link points to the documentation source.

### Education and Learning Resources

* [Ingonyama — Ingopedia](https://ingonyama-zk.github.io/ingopedia/curatedzk.html) - Includes Awesome ZKEVM in its curated ZK references.
* [BlocSoc IIT Delhi — ZK Bootcamp](https://github.com/blocsoc-iitd/zkbootcamp#week-6-what-are-zkevms) - Uses this list as a building resource in the week on zkEVMs.
* [ZKPunk's ZKPedia — ZK Materials](https://learn.zkpunk.pro/materials/ZK-Materials.html) - Includes Awesome zkEVM in its ZKP learning-resource collection.

### Community Collections and Publications

* [Blockchain Development Resources](https://github.com/frankiefab100/Blockchain-Development-Resources) - Includes this list among blockchain-development learning resources.
* [Library of Ethereum](https://github.com/arpitingle/Library-of-Ethereum) - Includes this list in its ZKP resource collection.
* [Blockchain Security Library — ZK](https://github.com/0xNazgul/Blockchain-Security-Library/blob/main/Security%20Library/ZK.md) - Includes this list alongside ZK research and security resources.
* [Awesome Identity](https://github.com/telnet193/awesome-identity) - Links to this list in its ZK resource section.
* [Awesome Links for ZK](https://github.com/hasselalcala/Awesome-Links-For-ZK) - Includes this list among ZK learning links.
* [Blockchain Developer Toolbox](https://github.com/berkcicekk/Blockchain-Developer-Toolbox) - Includes this list in its developer-resource collection.
* [ZK Rollups Directory — Resource Catalog](https://github.com/zkrollups/zkr-app-directory/blob/zkr-v2/src/components/Resources/resources.js) - Includes Awesome zkEVM in the directory's resource data; linked here as source evidence.
* [Ethereum Knowledge Notes](https://github.com/past-nikiv/knowledge/blob/main/docs/databases/blockchain/ethereum.md) - Includes this list in personal Ethereum reading notes, preserved in an archived knowledge collection.
* [LearnBlockchain — Ethereum Weekly, July 26, 2022](https://learnblockchain.cn/article/4445) - Historical zkEVM resource-list recommendation, confirmed in the indexed article text; live page access may be restricted.

## Contributing

Contributions are very welcome!

Please have a look at [contributing.md](contributing.md) for guidelines. Include a concise description and prefer official documentation or source repositories. When correcting project status, link to the upstream announcement or repository notice.

## License

To the extent of the maintainer's rights, the original curation and descriptions in this list are dedicated to the public domain under [CC0 1.0 Universal](LICENSE).

This dedication does not relicense linked projects, third-party artwork or badges, attributed material such as the Contributor Covenant, or pre-existing third-party contributions. Those retain their respective rights and terms.

## Maintenance

Maintained by [@LuozhuZhang](https://github.com/LuozhuZhang). Contributions and updates are welcome.

Please open an issue or pull request for broken links, project renames, archived resources, or useful additions.
