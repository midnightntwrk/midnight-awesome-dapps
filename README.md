# Awesome Midnight dApps [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome Midnight dApps, tools, and resources

## Contents

- [Awesome Midnight dApps ](#awesome-midnight-dapps-)
  - [Contents](#contents)
  - [🔦 Featured Project](#-featured-project)
  - [Getting Started](#getting-started)
  - [Smart Contract Primitives](#smart-contract-primitives)
  - [Starter Templates](#starter-templates)
  - [Developer Tools](#developer-tools)
  - [Finance \& DeFi](#finance--defi)
  - [Identity \& Privacy](#identity--privacy)
  - [Gaming](#gaming)
  - [Governance](#governance)
  - [Learning Resources](#learning-resources)
    - [Documentation](#documentation)
    - [Getting Started](#getting-started-1)
    - [Tutorials](#tutorials)
    - [Community](#community)
  - [Community Projects](#community-projects)
  - [Contributing](#contributing)
  - [License](#license)

> [!IMPORTANT]  
> Community-contributed projects are shared for inspiration and exploration. These repositories are not maintained by the Midnight team, and their functionality may vary.

> [!NOTE]  
> 🔹 = Official Midnight Ecosystem Partner

## 🔦 Featured Project

A part of the Midnight LATAM Hackathon, [KYC Midnight](https://github.com/joacolinares/kyc-midnight) is a privacy-preserving KYC attestation dApp on the Midnight network. It verifies user eligibility—such as age and country—using zero-knowledge proofs without revealing personal data on-chain. The project ships with both a web UI and a CLI, includes admin-managed policy controls, and is testnet-ready—making it a practical template for compliant, privacy-first onboarding flows.  
The open-source code is available on GitHub, encouraging collaboration and further development.

## Getting Started

_Official dApps maintained by the Midnight's DevRel team (for education + onboarding)_

- [Example Counter](https://github.com/midnightntwrk/example-counter) - Simple increment/decrement app demonstrating state management
- [Example Bboard](https://github.com/midnightntwrk/example-bboard) - Bulletin board with multi-user interactions and privacy patterns
- [Example Dex](https://github.com/midnightntwrk/example-dex) - Decentralized exchange using OpenZeppelin FungibleToken (WIP)
- [Example Proofshare](https://github.com/midnightntwrk/example-proofshare) - Selective disclosure of personal data (WIP)
- [NFT Smart Contract Library](https://github.com/riusricardo/midnight-contracts) - A comprehensive smart contract library for NFTs on the Midnight network.
- [Midnight Kitties](https://github.com/riusricardo/midnight-kitties) - A full stack Dapp using the NFT smart contract library to deploy Crypto Kitties on Midnight network.

## Smart Contract Primitives

- [🔹 OpenZeppelin Compact Contracts](https://github.com/OpenZeppelin/compact-contracts) - Standard contract implementations
  - [🔹 FungibleToken](https://github.com/OpenZeppelin/compact-contracts/blob/main/contracts/src/token/FungibleToken.compact) - ERC-20 equivalent for tokens like stablecoins or rewards
  - [🔹 NonFungibleToken](https://github.com/OpenZeppelin/compact-contracts/blob/main/contracts/src/token/NonFungibleToken.compact) - NFT implementation for Midnight
  - [🔹 MultiToken](https://github.com/OpenZeppelin/compact-contracts/blob/main/contracts/src/token/MultiToken.compact) - ERC-1155 equivalent supporting both fungible and non-fungible tokens

## Starter Templates

_Community-created boilerplates or dev scaffolds_

- [Create Midnight App](https://www.npmjs.com/package/create-midnight-app) - Build Midnight smart contracts with automated CLI generation. Includes enhanced data types, pre-generated wallet, and full contract-deploy pipeline
- [🔹 MeshJS Midnight Starter](https://github.com/MeshJS/midnight-starter-template) - Complete template with smart contracts, tests, UI, and all batteries included to kickstart your project
- [Midnightpy](https://github.com/Techgethr/midnightpy) - Midnight smart contract bindings for Python
- [Scaffold Midnight](https://github.com/kaleababayneh/scaffold-midnight) - Full-stack dev scaffold with Midnight integration
- [Wybe](https://github.com/lamg/wybe) - A minimal and expressive contract language for Midnight

## Developer Tools

_Tools that help other devs build, test, deploy, or index_

- [Explorer](https://github.com/AIQUANT-Tech/explorer) - Simple block explorer for Midnight networks
- [Midnight Indexer](https://github.com/semsorock/midnight-indexer) - An indexing tool for querying Midnight blockchain data
- [Midnight Live View](https://github.com/Midnight-Scripts/Midnight-Live-View) - A simple script that allows users to monitor key information about their Midnight node
- [Midnight Playground](https://midnight-playground-one.vercel.app/) - Online Compact IDE for writing, compiling, and building smart contracts with syntax error detection
- [Midnight MNN Helm](https://github.com/0xstrong/midnight-mnn-helm) - Helm charts for running Midnight full nodes or services
- [Web3Fast Midnight](https://midnight.web3fast.dev/) - Fast development tools and services for Midnight blockchain
- [MidnightForge](https://github.com/bytewizard42i/MidnightForge) - Infrastructure scripts and DevOps for Midnight dApp deployment
- [Midnightscan](https://github.com/mediocrehacker/Midnightscan) - Blockchain scanner for tracking Midnight contract deployments

## Finance & DeFi

- [Asset Tokenization Platform](https://github.com/nicolasLuduena/2025-hackathon-midnight) - Decentralized asset tokenization platform
- [Midnauction](https://github.com/eryxcoop/midnauction) - Sealed-bid round-based auction platform
- [Midnight Bank](https://github.com/nel349/midnight-bank) - Privacy-first banking DApp
- [SilentLedger](https://github.com/bytewizard42i/SilentLedger) - A privacy-preserving verified orderbook DApp
- [Statera Protocol](https://github.com/statera-protocol/statera-protocol-midnight) - Over-collateralized stablecoin protocol with modular dApp framework
- [Tokenless](https://github.com/luislucena16/tokenless) - Natively Midnight-based asset tokenization system

## Identity & Privacy

_Privacy-preserving identity, credentials, and proof of personhood_

- [Ethiopian Identity Wallet](https://github.com/HeikkiRuhanen/ethiopian-identity-wallet) - Self-Sovereign Identity (SSI) for verifying crypto wallet eligibility for National Stablecoin holding
- [Face Recognition Midnight](https://github.com/laughtt/face-recognition-midnight) - Facial recognition used to gate ZK-verified identity contracts
- [🔹 Midnames](https://github.com/midnames/core) - ZK-powered DID and credential registry with selective disclosure
- [🔹 Midnight Identity](https://github.com/bricktowers/midnight-identity) - Brick Towers' ZK identity system for self-issued credentials
- [SentinelDID](https://github.com/bytewizard42i/SentinelDID-poc) - ZK identity and access prototype with selective attributes
- [ZkBadge](https://github.com/Imdavyking/zkbadge) - Private achievement verifier that allows users to prove they hold valid certifications without revealing sensitive information
- [ZkID](https://github.com/quantus0/zkID) - A zk-SNARK-based identity layer

## Gaming

_Interactive, zero-knowledge-powered games_

- [Midnight Battleship](https://github.com/mediocrehacker/midnight-battleship) - A ZK-powered battleship game
- [🔹 Midnight Seabattle](https://github.com/bricktowers/midnight-seabattle) - SeaBattle implementation by Brick Towers
- [Midnight Sea Battle Hackathon](https://github.com/eddex/midnight-sea-battle-hackathon) - Jan & Eddex's SeaBattle submission

## Governance

- [FundAGoal](https://github.com/codeBigInt/fundagoal) - Crowdfunding smart contracts for verified projects
- [Midnight Vote](https://github.com/armsves/midnightVotingW3PN) - An anonymous governance and polling app

## Learning Resources

### Documentation

- [Midnight Docs](https://docs.midnight.network/) - Official documentation
- [Developer Academy](https://docs.midnight.network/academy/) - Structured learning modules (Modules 1-7 now live!)
- [Dev Diaries](https://docs.midnight.network/blog) - Technical blog posts and development insights
- [Kachina Paper](https://docs.midnight.network/learn/understanding-midnights-technology/kachina) - Privacy model paper
- [Tokenomics Paper](https://45047878.fs1.hubspotusercontent-na1.net/hubfs/45047878/Midnight-Tokenomics-And-Incentives-Whitepaper.pdf) - NIGHT/DUST economics

### Getting Started

- [Proof Server Setup](https://docs.midnight.network/develop/tutorial/using/proof-server)
- [Testnet Faucet](https://docs.midnight.network/develop/tutorial/using/faucet)
- [Compact Compiler](https://docs.midnight.network/relnotes/compact-tools)

### Tutorials

- [🔹 Edda Labs YouTube Series](https://www.youtube.com/@eddalabs) - In-depth Midnight examples and "Understand the Code" in Spanish, English, and Portuguese
- [Korean Tutorial](https://github.com/jungmyeong96/midnight_tutorial) - Step-by-step development guide for Korean-speaking developers
- [🔹 Mesh Midnight](https://midnight.meshjs.dev/) - A unified repository that brings together packages, examples, and documentation to streamline development

### Community

- [Discord](https://discord.com/invite/midnightnetwork)
- [Forum](https://forum.midnight.network)
- [YouTube](https://www.youtube.com/@midnight.network)

## Community Projects

Projects marked with 🏆 are hackathon winners

- 🏆 [KYC Midnight](https://github.com/joacolinares/kyc-midnight) - LATAM Hackathon winner

---

## Contributing

Contributions welcome! Please:

1. Add projects in alphabetical order within sections
2. Use format: `[name](link) - Brief description`
3. Ensure projects are open source and functional

## License

[![Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)
