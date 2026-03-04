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
  - [Dormant Projects](#dormant-projects)
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
> 🏆 = Hackathon winners

<!-- ## 🔦 Featured Project -->

## Getting Started

_Official dApps and tools maintained by the Midnight team (for education + onboarding)_

- [Example Counter](https://github.com/midnightntwrk/example-counter) - Simple increment/decrement app demonstrating state management
- [Hello World Compact](https://github.com/Olanetsoft/hello-world-compact) - Minimal Hello World smart contract for Midnight. Deploy to Preprod and store/read messages on-chain
- [Example Bboard](https://github.com/midnightntwrk/example-bboard) - Bulletin board with multi-user interactions and privacy patterns
- [Example ZK Loan](https://github.com/midnightntwrk/example-zkloan) - ZK-powered loan contract demonstrating private state management
- [Midnight Kitties](https://github.com/midnightntwrk/example-kitties) - A full stack dApp using the NFT smart contract library to deploy Crypto Kitties on Midnight network
- [NFT Smart Contract Library](https://github.com/riusricardo/midnight-contracts) - A comprehensive smart contract library for NFTs on the Midnight network
- [Midnight Local Dev](https://github.com/midnightntwrk/midnight-local-dev) - 
Local development environment for building and testing Midnight 
smart contracts without connecting to Preprod
- [Create Midnight App](https://github.com/midnightntwrk/create-mn-app) - 
CLI tool for scaffolding Midnight smart contracts with automated 
generation. Includes enhanced data types, pre-generated wallet, and 
full contract-deploy pipeline. Available on 
[npm](https://www.npmjs.com/package/create-midnight-app) 

## Smart Contract Primitives

- [🔹 OpenZeppelin Compact Contracts](https://github.com/OpenZeppelin/compact-contracts) - Standard contract implementations
  - [🔹 FungibleToken](https://github.com/OpenZeppelin/compact-contracts/blob/main/contracts/src/token/FungibleToken.compact) - ERC-20 equivalent for tokens like stablecoins or rewards
    - [🔹 MultiToken](https://github.com/OpenZeppelin/compact-contracts/blob/main/contracts/src/token/MultiToken.compact) - ERC-1155 equivalent supporting both fungible and non-fungible tokens
  - [🔹 NonFungibleToken](https://github.com/OpenZeppelin/compact-contracts/blob/main/contracts/src/token/NonFungibleToken.compact) - NFT implementation for Midnight


## Starter Templates

_Community-created boilerplates or dev scaffolds_

- [🔹 Edda Labs Midnight Starter](https://github.com/eddalabs/midnight-starter-template) - Complete template with smart contracts, tests, UI, and all batteries included to kickstart your project
- [Midnightpy](https://github.com/Techgethr/midnightpy) - Midnight smart contract bindings for Python
- [Scaffold Midnight](https://github.com/kaleababayneh/scaffold-midnight) - Full-stack dev scaffold with Midnight integration
- [Wybe](https://github.com/lamg/wybe) - A minimal and expressive contract language for Midnight

## Developer Tools

_Tools that help other devs build, test, deploy, or index_

- [Compact Playground](https://github.com/Olanetsoft/compact-playground) - Browser-based Compact smart contract compiler, built as a companion to Learn Compact
- [Explorer](https://github.com/AIQUANT-Tech/explorer) - Simple block explorer for Midnight networks
- [Midnight Indexer](https://github.com/semsorock/midnight-indexer) - An indexing tool for querying Midnight blockchain data
- [Midnight MCP](https://github.com/Olanetsoft/midnight-mcp) - MCP server giving AI assistants access to the Midnight blockchain — search contracts, analyze code, explore docs
- [Midnight Live View](https://github.com/Midnight-Scripts/Midnight-Live-View) - A simple script that allows users to monitor key information about their Midnight node
- [Web3Fast Midnight](https://midnight.web3fast.dev/) - Fast development tools and services for Midnight blockchain
- [Midnight MNN Helm](https://github.com/0xstrong/midnight-mnn-helm) - Helm charts for running Midnight full nodes or services
- [Midnight Playground](https://midnight-playground-one.vercel.app/) - Online Compact IDE for writing, compiling, and building smart contracts with syntax error detection
- [MidnightForge](https://github.com/bytewizard42i/MidnightForge) - Infrastructure scripts and DevOps for Midnight dApp deployment
- [Midnightscan](https://github.com/mediocrehacker/Midnightscan) - Blockchain scanner for tracking Midnight contract deployments
- [Midnight Explorer](https://github.com/Tech-Expansion/midnight-explorer-web) - The leading block explorer on the Midnight Network, proudly built by TexLabs - [Website](https://www.midnightexplorer.com/) 

## Finance & DeFi

- [Asset Tokenization Platform](https://github.com/nicolasLuduena/2025-hackathon-midnight) - Decentralized asset tokenization platform
- [dMarket](https://github.com/bochaco/dmarket) - A decentralized e-commerce marketplace that utilizes a three-party escrow system on the Midnight Network, incorporating asymmetric encryption and zero-knowledge proofs (zk-proofs) to ensure robust user privacy and security.
- [Hydra Stake](https://github.com/statera-protocol/hydra-stake-protocol) - Hydra Stake Protocol is a privacy-preserving liquid staking solution. It allows users to stake their assets while maintaining liquidity through liquid staking tokens (LST), enabling participation in DeFi while earning staking rewards.
- [LunarSwap](https://github.com/OpenZeppelin/midnight-apps) - A UTXO-based DEX built on Midnight built with ❤️ by [OpenZeppelin](https://docs.openzeppelin.com/)
- [Midnauction](https://github.com/eryxcoop/midnauction) - Sealed-bid round-based auction platform
- [Midnight Bank](https://github.com/nel349/midnight-bank) - Privacy-first banking dApp
- [🔹 Real World Assets](https://github.com/bricktowers/midnight-rwa) - Brick Towers is a privacy-first RWA trading system on Midnight, using shielded tokens and privacy-preserving user accreditation to enable fully regulated trading.
- [SilentLedger](https://github.com/bytewizard42i/SilentLedger) - A privacy-preserving verified orderbook dApp
- [Statera Protocol](https://github.com/statera-protocol/statera-protocol-midnight) - Over-collateralized stablecoin protocol with modular dApp framework
- [Tokenless](https://github.com/luislucena16/tokenless) - Natively Midnight-based asset tokenization system

## Identity & Privacy

_Privacy-preserving identity, credentials, and proof of personhood_

- [Blockenfy](https://github.com/kevan1/kyc-midnight-hackathon) - Decentralized identity platform built on the Midnight network. It enables user data registration and validation through zkProof, integrating the Lace wallet and ensuring privacy in KYC processes.
- [Ethiopian Identity Wallet](https://github.com/HeikkiRuhanen/ethiopian-identity-wallet) - Self-Sovereign Identity (SSI) for verifying crypto wallet eligibility for National Stablecoin holding
- [Face Recognition Midnight](https://github.com/laughtt/face-recognition-midnight) - Facial recognition used to gate ZK-verified identity contracts
- 🏆 [KYC Midnight](https://github.com/joacolinares/kyc-midnight) - Know Your Customer (KYC) attestation system - LATAM Hack winner
- [🔹 Midnames](https://github.com/midnames/core) - ZK-powered DID and credential registry with selective disclosure
- [🔹 Midnight Identity](https://github.com/bricktowers/midnight-identity) - Brick Towers' ZK identity system for self-issued credentials
- [Private Data Management](https://github.com/Edgxtech/pdm-demo-app) - 
Private data management demonstration using decentralised ledgers 
([article](https://medium.com/itnext/private-data-management-using-decentralised-ledgers-b972c6855e48))
- [SentinelDID](https://github.com/bytewizard42i/SentinelDID-poc) - ZK identity and access prototype with selective attributes

## Gaming

_Interactive, zero-knowledge-powered games_

- [🔹 Midnight Seabattle](https://github.com/bricktowers/midnight-seabattle) - SeaBattle implementation by Brick Towers

## Governance

- [FundAGoal](https://github.com/codeBigInt/fundagoal) - Crowdfunding smart contracts for verified projects
- [Midnight Vote](https://github.com/armsves/midnightVotingW3PN) - An anonymous governance and polling app

## Healthcare

- [Medical Verification System](https://github.com/FranZavalla/midnight-ui) - A transparent, secure and privacy-preserving protocol for medical data validation and government grants management.
- [NextMed](https://github.com/NextMed-main/Main) - healthcare platform enabling zk medical data analysis.

## Dormant Projects

Projects that are no longer actively maintained live in the [Dormant Projects](./dormant_projects/README.md) folder. These projects and their code are preserved and available for reference, adoption, or revival by anyone in the community.

# Learning Resources

### Documentation

- [Midnight Docs](https://docs.midnight.network/) - Official documentation
- [Developer Academy](https://academy.midnight.network/) - Build data protection apps with midnight
- [Dev Diaries](https://docs.midnight.network/blog) - Technical blog posts and development insights
- [Kachina Paper](https://docs.midnight.network/learn/understanding-midnights-technology/kachina) - Privacy model paper
- [Tokenomics Paper](https://45047878.fs1.hubspotusercontent-na1.net/hubfs/45047878/Midnight-Tokenomics-And-Incentives-Whitepaper.pdf) - NIGHT/DUST economics

### Getting Started

- [Proof Server Setup](https://docs.midnight.network/guides/run-proof-server)
- [Testnet Faucet](https://docs.midnight.network/guides/acquire-tokens)
- [Compact Compiler](https://docs.midnight.network/relnotes/compact-tools)

### Community Created Tutorials

- [Compact By Example](https://github.com/Olanetsoft/compact-by-example) - Learn Midnight's Compact language through practical, real-world examples
- [🔹 Edda Labs YouTube Series](https://www.youtube.com/@eddalabs) - In-depth Midnight examples and "Understand the Code" in Spanish, English, and Portuguese
- [Korean Tutorial](https://github.com/jungmyeong96/midnight_tutorial) - Step-by-step development guide for Korean-speaking developers
- [Learn Compact](https://github.com/Olanetsoft/learn-compact) - Interactive book and exercise collection for learning Compact, Midnight's ZK smart contract language
- [🔹 Mesh Midnight](https://midnight.meshjs.dev/) - A unified repository that brings together packages, examples, and documentation to streamline development

### Join Our Community

- [Discord](https://discord.com/invite/midnightnetwork)
- [Forum](https://forum.midnight.network)
- [YouTube](https://www.youtube.com/@midnight.network)
- [Nightforce - Ambassadors](https://midnight.network/nightforce-ambassador-program)
- [Aliit - Technical Fellowship](https://midnight.network/aliit)


---

# Contributing

**Contributions to this repo are welcome! Please:**

1. Add projects in alphabetical order within sections
2. Use format: `[name](link) - Brief description`
3. Ensure projects are open source and functional

## License

[![Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)
