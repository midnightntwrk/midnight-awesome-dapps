# Awesome Midnight dApps [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> This project is built on the Midnight Network.


> A curated list of awesome Midnight dApps, tools, and resources

## Contents

- [Awesome Midnight dApps ](#awesome-midnight-dapps-)
  - [Contents](#contents)
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
  - [Submission Criteria](#submission-criteria)
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
- [Midnight Local Dev](https://github.com/midnightntwrk/midnight-local-dev) -  
Local development environment for building and testing Midnight  
smart contracts without connecting to Preprod
- [Create Midnight App](https://github.com/midnightntwrk/create-mn-app) - CLI tool for scaffolding Midnight smart contracts with automated generation, enhanced data types, a pre-generated wallet, and a full contract-deploy pipeline, available on [npm](https://www.npmjs.com/package/create-midnight-app)

## Smart Contract Primitives

- [🔹 OpenZeppelin Compact Contracts](https://github.com/OpenZeppelin/compact-contracts) - Standard contract implementations
  - [🔹 FungibleToken](https://github.com/OpenZeppelin/compact-contracts/blob/main/contracts/src/token/FungibleToken.compact) - ERC-20 equivalent for tokens like stablecoins or rewards
  - [🔹 MultiToken](https://github.com/OpenZeppelin/compact-contracts/blob/main/contracts/src/token/MultiToken.compact) - ERC-1155 equivalent supporting both fungible and non-fungible tokens
  - [🔹 NonFungibleToken](https://github.com/OpenZeppelin/compact-contracts/blob/main/contracts/src/token/NonFungibleToken.compact) - NFT implementation for Midnight


## Starter Templates

_Community-created boilerplates or dev scaffolds_

- [🔹 Edda Labs Midnight Starter](https://github.com/eddalabs/midnight-starter-template) - Complete template with smart contracts, tests, UI, and all batteries included to kickstart your project

## Developer Tools

_Tools that help other devs build, test, deploy, or index_

- 🧰 [midnight-wallet-cli](https://github.com/nel349/midnight-wallet-cli-hub) - Standalone terminal wallet for Midnight with multi-wallet management, DApp connector server (`mn serve`), local network management, and MCP server for AI agents - [npm](https://www.npmjs.com/package/midnight-wallet-cli) - [Connector](https://www.npmjs.com/package/midnight-wallet-connector)
- [midnight-wallet-kit](https://www.npmjs.com/package/midnight-wallet-kit) - Lightweight toolkit for seamless wallet integration in Midnight dApps
- [Compact LSP](https://github.com/1NickPappas/compact-lsp) - Language Server Protocol for Compact smart contracts with diagnostics, completion, hover, go-to-definition, references, rename, and formatting.
- [Compact Playground](https://github.com/Olanetsoft/compact-playground) - Browser-based Compact smart contract compiler, built as a companion to Learn Compact
- [Compact Syntax Highlighting for VS Code](https://github.com/foxytanuki/compact-vscode) - VS Code extension providing syntax highlighting for Compact smart contracts
- [compact.vim](https://github.com/1NickPappas/compact.vim) - Vim and Neovim plugin for the Compact language with syntax highlighting, Tree-sitter support, filetype detection, smart indentation, and compiler quickfix integration.
- [🔹 OpenZeppelin Compact Tools](https://github.com/OpenZeppelin/compact-tools) - Tools for compiling, building, and testing Compact smart contracts
- [🔹 Web3Fast Midnight](https://midnight.web3fast.dev/) - Fast development tools and services for Midnight blockchain
- [DPO2U Midnight Relayer](https://github.com/fredericosanntana/dpo2u-midnight-relayer) - Cross-chain compliance relay for Midnight Network with ZK proofs
- [EchoMKB](https://github.com/EchoForge-Dev/EchoMKB) - Agent skill that searches the Midnight documentation live on every use, returns cited excerpts carrying each page's Compact language and compiler version, and reports version drift between the compatibility matrix and the latest releases - [Website](https://m.echoforgeef.com/echomkb)
- [Midnight Doctor](https://github.com/fredericosanntana/midnight-doctor) - CLI pre-flight check that cross-references SDK + Docker + config against a verified compatibility matrix to catch version mismatches and known bugs before silent failures - [npm](https://www.npmjs.com/package/midnight-doctor)
- [Midnight Explorer](https://github.com/Tech-Expansion/midnight-explorer-web) - The leading block explorer on the Midnight Network, proudly built by TexLabs - [Website](https://www.midnightexplorer.com/)
- [Midnight Local Playground](https://github.com/0xshae/midnight-playground) - Local dev environment: run full node, indexer, and proof server via Docker; fund and deploy Compact contracts with Lace on "Undeployed" — no testnet or faucet. Includes Hello World contract and CLI
- [Midnight MCP](https://github.com/Olanetsoft/midnight-mcp) - MCP server giving AI assistants access to the Midnight blockchain — search contracts, analyze code, explore docs
- [Midnight Mobile SDK](https://github.com/mzf11125/midnight-mobile-sdk) - React Native SDK for mobile wallet, zero-knowledge contracts, and DApp connectivity with biometric auth, secure storage (iOS Keychain/Android Keystore), deep links, QR code scanner, and offline transaction queue - [npm](https://www.npmjs.com/package/@dedanzi/midnight-mobile-sdk)
- [Midday SDK](https://github.com/no-witness-labs/midday-sdk) - Developer-friendly TypeScript SDK for building dApps on Midnight Network, with wallet management, contract deployment, and state management in one package
- [Midnight Compact Smart Contract Skill](https://github.com/adavault/midnight-skill) - Agent skill for AI coding assistants to write, test, and deploy Compact smart contracts. 151 compiler-validated circuits, 30 deployed contracts, 59 developer gotchas
- [Midnight Network Agent Skills](https://github.com/mzf11125/midnight_agent_skills) - 4 modular agent skills covering Midnight concepts, Compact language, API integration, and network deployment for AI-assisted development
- [Midnight Wallet Extension](https://github.com/Ansh-Sonkusare/midnight-extension) - Self-contained Midnight wallet browser extension (Manifest V3) with seed import, NIGHT send/receive, transaction history, multisig vaults, and a ConnectedAPI v4 DApp connector.
- [Nocturne Wallet](https://github.com/htlabs-xyz/nocturne) - Self-custodial Chrome extension wallet for Midnight with shielded/unshielded balances, DUST registration, multi-network support, and dApp connector - [Chrome Web Store](https://chromewebstore.google.com/detail/nocturne/ijfdfgajlffijenjneoppbfnhjkdibna)
- [Midnight Playground](https://midnight-playground-one.vercel.app/) - Online Compact IDE for writing, compiling, and building smart contracts with syntax error detection
- [MIDSKILLS](https://github.com/Kali-Decoder/Midnight-skills) - Modular agent skills for AI coding assistants covering Compact contracts, wallet integration, indexer queries, and full DApp scaffolds. - [Website](https://midskills.sevryn.xyz/)
- [Night Check](https://github.com/CjDabrow/night-check) - Reviews Compact contracts and SDK code for Midnight-specific privacy and security issues, and certifies a review on-chain with a privacy-preserving Compact contract. - [Website](https://midnight.gridservices.xyz)
- [Nightforge](https://github.com/cadalt0/NIGHTFORGE) - CLI development toolkit for building, deploying, and managing Midnight smart contracts with project scaffolding, compilation, and proof server orchestration
- [NightGate](https://github.com/ODATANO/NIGHTGATE) - Self contained Midnight Indexer packaged as an SAP CAP plugin normalizes chain data into CAP entities, and exposes it through OData V4 Services.
- [Pelagos SDK](https://github.com/0xAtelerix/sdk) - Go SDK for building appchains with native Midnight, EVM, and non-EVM integration

## Finance & DeFi

- 🔹 [LunarSwap](https://github.com/OpenZeppelin/midnight-apps) - A UTXO-based DEX built on Midnight built with ❤️ by [OpenZeppelin](https://docs.openzeppelin.com/)
- [🔹 Real World Assets](https://github.com/bricktowers/midnight-rwa) - Brick Towers is a privacy-first RWA trading system on Midnight, using shielded tokens and privacy-preserving user accreditation to enable fully regulated trading
- [dMarket](https://github.com/bochaco/dmarket) - A decentralized e-commerce marketplace that utilizes a three-party escrow system on the Midnight Network, incorporating asymmetric encryption and zero-knowledge proofs (zk-proofs) to ensure robust user privacy and security
- [Hydra Stake](https://github.com/statera-protocol/hydra-stake-protocol) - Hydra Stake Protocol is a privacy-preserving liquid staking solution. It allows users to stake their assets while maintaining liquidity through liquid staking tokens (LST), enabling participation in DeFi while earning staking rewards
- [Midnight Escrow](https://github.com/tusharpamnani/midnight-escrow) - Privacy-preserving escrow contract demonstrating confidential conditional payments using zk proofs on Midnight
- [Midnight Private Auction](https://github.com/pplmaverick/midnight-private-auction) - Sealed-bid auction on Midnight using Compact private state so bid amounts stay private until reveal. - [Demo](https://midnight-private-auction.vercel.app)
- [MidPilot](https://github.com/ANPAN27/MidPilot) - AI spending assistant for Midnight that plans transfers with local policy checks and MCP wallet integration. - [Demo](https://midpilot.vercel.app)
- [Noctis](https://github.com/NoctisZone/Noctis) - Token launchpad with a private Midnight buying phase: amounts stay hidden until reveal, when the contract checks the per-wallet cap. - [Site](https://noctis.zone)
- [Pintent](https://github.com/0xAtelerix/pintent) - Cross-chain bridge from Midnight to EVM and non-EVM chains using an intent-based solver model
- [Selkie](https://github.com/DpacJones/selkie-usdm-escrow) - Escrow that holds USDM in contract state and releases it to whoever proves knowledge of a secret, with no identity check in the claim path.
- [SilentBid](https://github.com/efekrbas/midnight-sealed-bid-marketplace) - A zero-knowledge sealed-bid marketplace where bids stay private until settlement.
- [SilentLedger](https://github.com/bytewizard42i/SilentLedger) - A privacy-preserving verified orderbook dApp

## Identity & Privacy

_Privacy-preserving identity, credentials, and proof of personhood_

- [🔹 Midnight Identity](https://github.com/bricktowers/midnight-identity) - Brick Towers' ZK identity system for self-issued credentials
- [AirLog](https://github.com/hbrazier01/airlog) - Privacy preserving aviation maintenance record verification system built with Midnight Compact smart contracts
- [Anonboard](https://github.com/nel349/solana-anonboard) - Anonymous bulletin board that proves membership with a zero-knowledge circuit on Midnight, while posts are stored publicly and gaslessly on Solana, linked by an EffectStream sync node.
- [Anonymous Whispers](https://github.com/Emmanuellsensai/anonymous-whispers) - Whistleblower DApp on Midnight that stores client-encrypted reports on-chain with an in-circuit hash commitment of the plaintext. - [Demo](https://anonymous-whispers.vercel.app)
- [Credence](https://github.com/0xfdbu/midnight-apps/tree/main/fullstack-dapp) - Fullstack ZK identity platform for privacy-preserving credential attestations — authorities attest users via Merkle-tree commitments; users prove eligibility without revealing identity using nullifier-protected ZK proofs, with deterministic key derivation
- [AutoDiscovery](https://github.com/SpyCrypto/AutoDiscovery) - Privacy-preserving legal discovery automation with jurisdiction-aware compliance, ZK proofs, and dual-ledger architecture
- [DPO2U Midnight](https://github.com/fredericosanntana/dpo2u-midnight) - Autonomous LGPD/GDPR compliance protocol with ZK-attested privacy scores. AI agents audit data protection practices off-chain and record immutable attestations on Midnight via four Compact smart contracts (ComplianceRegistry, AgentRegistry, FeeDistributor, Treasury)
- [Kredz](https://github.com/kredz-labs/kredz/tree/main/kredz-midnight) - Privacy-preserving credit identity protocol using ZK witnesses, score commitment hashing, and selective disclosure on the Midnight Network.
- [Midnight Authenticator](https://github.com/subc0der/midnight-authenticator) - Zero-knowledge TOTP authenticator that proves code validity without revealing secrets
- [Midnight Cloak](https://github.com/subc0der/midnight-cloak) - Zero-knowledge identity verification SDK enabling dApps to verify user attributes (age, credentials) without exposing personal data
- [Midnight-ZK-Judge](https://github.com/efekrbas/Midnight-ZK-Judge) - Privacy-preserving decision circuit that evaluates private inputs against a public threshold on Midnight. - [Demo](https://midnight-zk-judge.vercel.app)
- [Nightroom](https://github.com/Gutopro/nightroom) - Privacy-preserving room rental protocol using zero-knowledge proofs to verify owner and guest identity without exposing sensitive data on-chain.
- [Proof-of-Age Gate](https://github.com/tomiin/midnight-proof-of-age) - Prove you meet a minimum age without revealing your birth year; ZK selective disclosure in Compact, with a React frontend wired to the 1AM wallet
- [SentinelDID](https://github.com/bytewizard42i/SentinelDID-poc) - ZK identity and access prototype with selective attributes
- [ShadowVoice](https://github.com/priyalraut703/shadowvoice) - Anonymous student feedback DApp on Midnight where enrollment is proven with zero-knowledge proofs and complaint identity stays private.
- [ZIP](https://github.com/oluwatobiss/zip-midnight-mlh-202605-hack) - A privacy-first Proof-of-Humanity application
- [zkTanitID](https://github.com/carthagexlabs/zk-tanit-id) - Privacy-Preserving Identity Attestations, inspired by Tunisia’s digital sovereignty challenges

# Topics


## Gaming

_Interactive, zero-knowledge-powered games_

- 🕹️ [Midnight Starship](https://github.com/nel349/midnight-starship) - Galaga-style space shooter with privacy-first on-chain leaderboard using ZK selective disclosure, built with midnight-wallet-connector
- [🔹 Midnight Seabattle](https://github.com/bricktowers/midnight-seabattle) - SeaBattle implementation by Brick Towers

- [Midnight DiceRoll Game](https://github.com/Kali-Decoder/Midnight-Dice-Roll) - Midnight Dice Roll is a reference implementation of a verifiable dice game built using Midnight’s Compact smart contracts.

- [Midnight Prediction Market App](https://github.com/mashharuki/midnight-prediction-market-sample-app) - Privacy-preserving four-outcome football prediction market using Compact, Midnight.js, and Lace Wallet.

- [Midnight RPC Game](https://github.com/mashharuki/midnight-rps-sample-app) - Sample Rock-Paper-Scissors DApp on Midnight using a Compact commit/reveal flow.

## Governance

- [FundAGoal](https://github.com/codeBigInt/fundagoal) - Crowdfunding smart contracts for verified projects

## Healthcare

- [NextMed](https://github.com/NextMed-main/Main) - healthcare platform enabling zk medical data analysis

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

- [Learn Compact](https://github.com/Olanetsoft/learn-compact) - Interactive book and exercise collection for learning Compact, Midnight's ZK smart contract language
- [Compact By Example](https://github.com/Olanetsoft/compact-by-example) - Learn Midnight's Compact language through practical, real-world examples
- [🔹 Edda Labs YouTube Series](https://www.youtube.com/@eddalabs) - In-depth Midnight examples and "Understand the Code" in Spanish, English, and Portuguese
- [🔹 Mesh Midnight](https://midnight.meshjs.dev/) - A unified repository that brings together packages, examples, and documentation to streamline development



### Join Our Community

- [Midnight Network Discord](https://discord.com/invite/midnightnetwork)
- [Follow Midnightntwrk on X](https://x.com/MidnightNtwrk)
- [Midnight Forum - Best for technical Q&A](https://forum.midnight.network)
- [Midnight Network YouTube](https://www.youtube.com/@midnight.network)
- [Nightforce - Ambassadors](https://midnight.network/nightforce-ambassador-program)
- [Aliit - Technical Fellowship](https://midnight.network/aliit)


---

# Contributing

**Contributions to this repo are welcome! Please:**

1. Add projects in alphabetical order within sections
2. Use format: `[name](link) - Brief description`
3. Ensure projects are open source and functional

## Submission Criteria

Projects must include working Compact code, proper attribution, and represent 
a real use case built on Midnight Network. See [CONTRIBUTING.md](CONTRIBUTING.md) 
for full review guidelines before opening a PR.

## License

[![Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)
