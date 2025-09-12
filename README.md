# 🚀 Build with Midnight: Open Source dApps & Tools

Welcome to the Midnight ecosystem's curated list of example dApps, starter templates, tutorials, learning resources, and hackathon projects. This repo is designed to help developers get inspired, learn from real-world projects, and build more confidently with privacy-preserving tools on Midnight.

You'll find:

- 🔧 Official examples from the Midnight team
- 🌱 Community-built dApps and templates
- 🎓 Learning resources and video tutorials
- 🏆 Projects from past hackathons

We welcome contributions! If you’ve built something on Midnight or adapted an existing tool, [open a pull request](https://github.com/midnightntwrk/midnight-awesome-dapps/pulls) to share it with the community.

## 🌱 Core Examples

_Official dApps maintained by the Midnight's DevRel team (for education + onboarding)_

- [Counter dApp](https://github.com/midnightntwrk/example-counter) – A simple increment/decrement app using Midnight smart contracts

- [Bulletin Board](https://github.com/midnightntwrk/example-bboard) – A basic public message board built on Midnight

- [Decentralized Exchange](https://github.com/midnightntwrk/example-dex) – A simple decentralized exchange built on Midnight using the OpenZeppelin `FungibleToken` library (Under construction)

- [Proofshare](https://github.com/midnightntwrk/example-proofshare) – A privacy-focused dApp demonstrating selective disclosure of personal data (Under construction)

## 📚 Learning Resources

- #### Midnight Docs Blog, [Dev Diaries](https://docs.midnight.network/blog)

- #### Midnight Developer Academy [Modules 1-7 now live!](https://docs.midnight.network/academy/)

> [!IMPORTANT]  
> Community-contributed projects are shared for inspiration and exploration. These repositories are not maintained by the Midnight team, and their functionality may vary.

# Ecosystem-Contributed dApps & Tools

> [!NOTE]  
> 🔹 = Official Midnight Ecosystem Partner

## 🔦 Ecosystem dApp of the Month!

A part of the Midnight LATAM Hackathon, [KYC Midnight](https://github.com/joacolinares/kyc-midnight) is a privacy-preserving KYC attestation dApp on the Midnight network. It verifies user eligibility—such as age and country—using zero-knowledge proofs without revealing personal data on-chain. The project ships with both a web UI and a CLI, includes admin-managed policy controls, and is testnet-ready—making it a practical template for compliant, privacy-first onboarding flows.  
The open-source code is available on GitHub, encouraging collaboration and further development.

## 🧱 Smart Contract Primitives (by [🔹OpenZeppelin](https://github.com/OpenZeppelin/compact-contracts))

- **[🔹 Fungible Token](https://github.com/OpenZeppelin/compact-contracts/tree/main/contracts/fungibleToken)** — Midnight-native equivalent of ERC-20 for tokens like stablecoins or rewards
- **[🔹 Non-Fungible Token (NFT)](https://github.com/OpenZeppelin/compact-contracts/tree/main/contracts/nonFungibleToken)** — Create and manage NFTs on Midnight using Compact
- **[🔹 MultiToken (ERC-1155)](https://github.com/OpenZeppelin/compact-contracts/tree/main/contracts/multitoken)** — Efficient multi-asset standard supporting both fungible and non-fungible tokens

## 🧑‍💻 Starter Templates

_Community-created boilerplates or dev scaffolds_

- **[🔹 MeshJS Starter Template](https://github.com/MeshJS/midnight-starter-template)** — A complete template with smart contracts, tests, UI, and all batteries included to kickstart your project
- **[Scaffold Midnight](https://github.com/kaleababayneh/scaffold-midnight)** — Full-stack dev scaffold with Midnight integration
- **[Create Midnight App (npm)](https://www.npmjs.com/package/create-midnight-app)** — Build Midnight smart contracts with automated CLI generation. Includes enhanced data types, pre-generated wallet, and full contract-deploy pipeline
- **[midnightpy](https://github.com/Techgethr/midnightpy)** — Midnight smart contract bindings for Python
- **[wybe](https://github.com/lamg/wybe)** — A minimal and expressive contract language for Midnight

## 🧩 Ecosystem Tooling

_Tools that help other devs build, test, deploy, or index_

- **[Statera Protocol](https://github.com/LucentLabss/statera-protocol)** — A framework for building modular dApps on Midnight
- **[MidnightForge](https://github.com/bytewizard42i/MidnightForge)** — Infrastructure scripts and DevOps for Midnight dApp deployment
- **[Midnightscan](https://github.com/mediocrehacker/Midnightscan)** — Blockchain scanner for tracking Midnight contract deployments
- **[Explorer](https://github.com/AIQUANT-Tech/explorer)** — Simple block explorer for Midnight networks
- **[Midnight MNN Helm](https://github.com/0xstrong/midnight-mnn-helm)** — Helm charts for running Midnight full nodes or services
- **[Midnight Indexer](https://github.com/semsorock/midnight-indexer)** — An indexing tool for querying Midnight blockchain data
- **[Midnight Live View](https://github.com/Midnight-Scripts/Midnight-Live-View)** - A simple script that allows users to monitor key information about their Midnight node.

## 🧠 ZK Identity Projects

_Privacy-preserving identity, credentials, and proof of personhood_

- **[🔹 Midnames](https://github.com/midnames/core)** — ZK-powered DID and credential registry with selective disclosure
- **[🔹 midnight-identity](https://github.com/bricktowers/midnight-identity)** — Brick Towers’ ZK identity system for self-issued credentials
- **[Ethiopian Identity Wallet](https://github.com/HeikkiRuhanen/ethiopian-identity-wallet/tree/main)** — Self-Sovereign Identity (SSI) for verifying crypto wallet eligibility for National Stablecoin holding
- **[SentinelDID](https://github.com/bytewizard42i/SentinelDID-poc)** — ZK identity and access prototype with selective attributes
- **[face-recognition-midnight](https://github.com/laughtt/face-recognition-midnight)** — Facial recognition used to gate ZK-verified identity contracts
- **[zkID](https://github.com/quantus0/zkID)** — A zk-SNARK-based identity layer

## ⚔️ Game Examples

_Interactive, zero-knowledge-powered games_

- **[🔹 midnight-seabattle](https://github.com/bricktowers/midnight-seabattle)** — SeaBattle implementation by Brick Towers
- **[midnight-battleship](https://github.com/mediocrehacker/midnight-battleship)** — A ZK-powered battleship game
- **[midnight-sea-battle-hackathon](https://github.com/eddex/midnight-sea-battle-hackathon)** — Jan & Eddex’s SeaBattle submission

## 🧪 Hackathon dApps

_Experimental apps from community hackathons_

- **[FundAGoal](https://github.com/codeBigInt/fundagoal)** — Crowdfunding smart contracts for verified projects
- **[Midnight Vote](https://github.com/armsves/midnightVotingW3PN)** — An anonymous governance and polling app
- **[KYC Midnight](https://github.com/joacolinares/kyc-midnight)** – Know Your Customer (KYC) attestation system
- **[Asset Tokenization Platform](https://github.com/nicolasLuduena/2025-hackathon-midnight)** – Decentralized asset tokenization platform
- **[Midnauction](https://github.com/eryxcoop/midnauction)** – Sealed-bid round-based auction platform

## 💻 Mini dApps

- **[Midnight Bank](https://github.com/nel349/midnight-bank)** – (Privacy-First Banking DApp) Privacy-first banking DApp
- **[zkBadge](https://github.com/Imdavyking/zkbadge)** – (Private Achievement Verifier) Allows users to prove they hold valid certifications or identity attributes without revealing any sensitive information
- **[Statera](https://github.com/statera-protocol/statera-protocol-midnight)** – Over-collateralized stablecoin protocol
- **[SilentLedger](https://github.com/bytewizard42i/SilentLedger)** – A privacy-preserving verified orderbook DApp
- **[Tokenless](https://github.com/luislucena16/tokenless)** – Natively Midnight-based asset tokenization system

## 🎓 Video + Tutorial Content

_Learn how to build with Midnight, from the community_

- **[🔹 Edda Labs YouTube Series](https://www.youtube.com/@eddalabs)** — In-depth Midnight examples and “Understand the Code” in Spanish, English, and Portuguese
- **[Midnight Korean Tutorial](https://github.com/jungmyeong96/midnight_tutorial/tree/main)** — Step-by-step development guide for Korean-speaking developers
- **[🔹 Mesh Midnight](https://midnight.meshjs.dev/en)** — A unified repository that brings together packages, examples, and documentation to streamline development
