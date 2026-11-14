<p align="center">
  <img src="https://img.shields.io/badge/Web3-Free%20Resources-blueviolet?style=for-the-badge&logo=ethereum&logoColor=white" alt="Web3 Free Resources"/>
  <img src="https://img.shields.io/badge/Resources-27+-success?style=for-the-badge" alt="27+ Resources"/>
  <img src="https://img.shields.io/badge/Hindi%20Videos-11+-orange?style=for-the-badge&logo=youtube&logoColor=white" alt="Hindi Videos"/>
  <img src="https://img.shields.io/badge/Cost-₹0%20FREE-brightgreen?style=for-the-badge" alt="Free"/>
  <img src="https://img.shields.io/badge/Updated-August%202026-blue?style=for-the-badge" alt="Updated August 2026"/>
</p>

<h1 align="center">🌐 Web3 Free Resources — The Ultimate Guide</h1>

<p align="center">
  <strong>A curated, verified collection of 27+ free resources to learn Web3, Blockchain, Solidity, DeFi, and Smart Contract Development — from absolute zero to production-ready.</strong>
</p>

<p align="center">
  <em>🇮🇳 Includes dedicated Hindi learning resources & YouTube channels</em>
</p>

---

## 📖 Table of Contents

- [🗺️ Web3 Learning Roadmap](#️-web3-learning-roadmap)
- [🏗️ Architecture Overview](#️-architecture-overview)
- [📚 Free Learning Resources (27+)](#-free-learning-resources-27)
  - [🔰 Foundations & Concepts](#-foundations--concepts)
  - [📝 Solidity & Smart Contracts](#-solidity--smart-contracts)
  - [🛠️ Development Frameworks & Tools](#️-development-frameworks--tools)
  - [🔗 L1 / L2 Ecosystem Documentation](#-l1--l2-ecosystem-documentation)
  - [🌉 Oracles, Indexing & Storage](#-oracles-indexing--storage)
  - [🏆 Challenges, CTFs & Hands-On Practice](#-challenges-ctfs--hands-on-practice)
  - [🎓 Full Courses & Bootcamps](#-full-courses--bootcamps)
- [🇮🇳 Hindi YouTube Resources](#-hindi-youtube-resources)
- [🧭 Ecosystem Map](#-ecosystem-map)
- [🛤️ 90-Day Learning Plan](#️-90-day-learning-plan)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)

---

## 🗺️ Web3 Learning Roadmap

> Follow this roadmap from top to bottom. Each phase builds on the previous one.

```mermaid
graph TD
    A["🌱 <b>PHASE 1: Foundations</b><br/>Blockchain concepts, Crypto wallets,<br/>How transactions work"]
    B["📝 <b>PHASE 2: Solidity Basics</b><br/>Data types, Functions, Mappings,<br/>Events, Modifiers, Inheritance"]
    C["🎮 <b>PHASE 3: Interactive Practice</b><br/>CryptoZombies, Solidity by Example,<br/>Remix IDE experiments"]
    D["🛠️ <b>PHASE 4: Dev Tooling</b><br/>Hardhat / Foundry setup,<br/>Testing, Deployment, Scripts"]
    E["🏗️ <b>PHASE 5: Full-Stack dApps</b><br/>ethers.js / wagmi / viem,<br/>Next.js + Wallet integration"]
    F["🔐 <b>PHASE 6: Security & DeFi</b><br/>Ethernaut, Damn Vulnerable DeFi,<br/>Audit patterns, OpenZeppelin"]
    G["🚀 <b>PHASE 7: Multi-Chain & Ship</b><br/>Solana / Sui / Starknet,<br/>Oracles, The Graph, IPFS"]

    A --> B --> C --> D --> E --> F --> G

    style A fill:#1a1a2e,stroke:#e94560,color:#fff,stroke-width:2px
    style B fill:#1a1a2e,stroke:#f39c12,color:#fff,stroke-width:2px
    style C fill:#1a1a2e,stroke:#2ecc71,color:#fff,stroke-width:2px
    style D fill:#1a1a2e,stroke:#3498db,color:#fff,stroke-width:2px
    style E fill:#1a1a2e,stroke:#9b59b6,color:#fff,stroke-width:2px
    style F fill:#1a1a2e,stroke:#e74c3c,color:#fff,stroke-width:2px
    style G fill:#1a1a2e,stroke:#1abc9c,color:#fff,stroke-width:2px
```

---

## 🏗️ Architecture Overview

> Understanding where each technology fits in the Web3 stack.

```mermaid
graph TB
    subgraph USER_LAYER["👤 User Layer"]
        direction LR
        WALLET["🦊 MetaMask / Phantom"]
        BROWSER["🌐 Browser dApp"]
    end

    subgraph FRONTEND["⚛️ Frontend Layer"]
        direction LR
        NEXTJS["Next.js / React"]
        ETHERSJS["ethers.js / viem"]
        WAGMI["wagmi hooks"]
    end

    subgraph MIDDLEWARE["🔗 Middleware Layer"]
        direction LR
        CHAINLINK["⛓️ Chainlink<br/>Oracles"]
        THEGRAPH["📊 The Graph<br/>Indexing"]
        IPFS["📦 IPFS / Filecoin<br/>Storage"]
    end

    subgraph BLOCKCHAIN["⛓️ Blockchain Layer"]
        direction LR
        ETH["Ethereum<br/>Mainnet"]
        BASE["Base<br/>L2"]
        POLYGON["Polygon<br/>L2"]
        SOLANA["Solana"]
        SUI["Sui"]
        STARKNET["Starknet"]
    end

    subgraph CONTRACTS["📜 Smart Contracts"]
        direction LR
        SOLIDITY["Solidity"]
        RUST["Rust"]
        MOVE["Move"]
        CAIRO["Cairo"]
    end

    subgraph TOOLS["🛠️ Dev Tools"]
        direction LR
        HARDHAT["Hardhat"]
        FOUNDRY["Foundry"]
        REMIX["Remix IDE"]
        OZ["OpenZeppelin"]
    end

    USER_LAYER --> FRONTEND
    FRONTEND --> MIDDLEWARE
    FRONTEND --> BLOCKCHAIN
    MIDDLEWARE --> BLOCKCHAIN
    CONTRACTS --> BLOCKCHAIN
    TOOLS --> CONTRACTS

    style USER_LAYER fill:#0d1117,stroke:#58a6ff,color:#c9d1d9,stroke-width:2px
    style FRONTEND fill:#0d1117,stroke:#7ee787,color:#c9d1d9,stroke-width:2px
    style MIDDLEWARE fill:#0d1117,stroke:#d2a8ff,color:#c9d1d9,stroke-width:2px
    style BLOCKCHAIN fill:#0d1117,stroke:#f0883e,color:#c9d1d9,stroke-width:2px
    style CONTRACTS fill:#0d1117,stroke:#ff7b72,color:#c9d1d9,stroke-width:2px
    style TOOLS fill:#0d1117,stroke:#79c0ff,color:#c9d1d9,stroke-width:2px
```

---

## 📚 Free Learning Resources (27+)

### 🔰 Foundations & Concepts

> Start here if you're brand new to blockchain and Web3.

| # | Resource | What You'll Learn | Best For | Link |
|:-:|----------|-------------------|----------|:----:|
| 1 | **Ethereum Learn Hub** | How blockchain works, consensus, wallets, gas, accounts | Absolute beginners | [🔗 Visit](https://ethereum.org/learn/) |
| 2 | **Ethereum Developer Tutorials** | Guided step-by-step tutorials for building dApps | Beginners ready to code | [🔗 Visit](https://ethereum.org/developers/tutorials) |

Optional reading (Simplified Chinese): [链小知区块链: Token approvals](https://lianxiaozhi.com/learn/token-approvals) explains ERC-20 allowances, disconnecting versus revoking, and checking the network, owner, spender and post-transaction allowance; free, source-linked and AI-assisted.

```mermaid
flowchart LR
    A["📖 Read Ethereum<br/>Learn Hub"] --> B["🧪 Try Developer<br/>Tutorials"] --> C["✅ You understand<br/>blockchain basics!"]
    style A fill:#161b22,stroke:#58a6ff,color:#c9d1d9
    style B fill:#161b22,stroke:#7ee787,color:#c9d1d9
    style C fill:#161b22,stroke:#2ea043,color:#c9d1d9
```

---

### 📝 Solidity & Smart Contracts

> The core language for Ethereum and EVM-compatible chains.

| # | Resource | What You'll Learn | Format | Link |
|:-:|----------|-------------------|--------|:----:|
| 3 | **Solidity Documentation** | Complete language reference — types, functions, assembly | Official docs | [🔗 Visit](https://docs.soliditylang.org/en/latest/) |
| 4 | **Solidity by Example** | 60+ short, copy-paste-ready Solidity patterns | Code snippets | [🔗 Visit](https://solidity-by-example.org/) |
| 5 | **Remix IDE** | Write, compile, deploy, and debug contracts in the browser | Browser IDE | [🔗 Visit](https://remix.ethereum.org/) |
| 6 | **CryptoZombies** | Learn Solidity by building a zombie game — interactive & fun | Interactive game | [🔗 Visit](https://cryptozombies.io/) |
| 7 | **OpenZeppelin Contracts + Wizard** | Battle-tested ERC-20, ERC-721, ERC-1155, access control | Library + generator | [🔗 Visit](https://docs.openzeppelin.com/contracts) |

```mermaid
flowchart LR
    A["📄 Solidity Docs<br/><i>Reference</i>"] --> B["🧩 Solidity by Example<br/><i>Patterns</i>"]
    B --> C["🎮 CryptoZombies<br/><i>Practice</i>"]
    C --> D["🖥️ Remix IDE<br/><i>Deploy</i>"]
    D --> E["🛡️ OpenZeppelin<br/><i>Secure Code</i>"]

    style A fill:#161b22,stroke:#f0883e,color:#c9d1d9
    style B fill:#161b22,stroke:#f0883e,color:#c9d1d9
    style C fill:#161b22,stroke:#f0883e,color:#c9d1d9
    style D fill:#161b22,stroke:#f0883e,color:#c9d1d9
    style E fill:#161b22,stroke:#f0883e,color:#c9d1d9
```

---

### 🛠️ Development Frameworks & Tools

> Professional toolchains for building, testing, and deploying smart contracts.

| # | Resource | What You'll Learn | Language | Link |
|:-:|----------|-------------------|----------|:----:|
| 8 | **Foundry** | Blazing-fast Solidity testing, fuzzing, scripting, local chains | Solidity-native | [🔗 Visit](https://www.getfoundry.sh/) |
| 9 | **Hardhat** | The most popular EVM development environment | JavaScript/TS | [🔗 Visit](https://hardhat.org/docs/getting-started) |
| 10 | **Scaffold-ETH 2** | Full-stack dApp starter — Next.js + Hardhat + wallet connect | Full-stack | [🔗 Visit](https://scaffoldeth.io/) |

```mermaid
graph LR
    subgraph CHOOSE["Pick Your Framework"]
        direction TB
        F["⚡ Foundry<br/><small>Speed & Solidity-native tests</small>"]
        H["🎩 Hardhat<br/><small>JS/TS ecosystem & plugins</small>"]
        S["🏗️ Scaffold-ETH 2<br/><small>Full-stack starter kit</small>"]
    end

    F --> DEPLOY["🚀 Deploy to<br/>Testnet / Mainnet"]
    H --> DEPLOY
    S --> DEPLOY

    style CHOOSE fill:#0d1117,stroke:#58a6ff,color:#c9d1d9,stroke-width:2px
    style F fill:#161b22,stroke:#7ee787,color:#c9d1d9
    style H fill:#161b22,stroke:#f0883e,color:#c9d1d9
    style S fill:#161b22,stroke:#d2a8ff,color:#c9d1d9
    style DEPLOY fill:#161b22,stroke:#2ea043,color:#c9d1d9
```

---

### 🔗 L1 / L2 Ecosystem Documentation

> Explore multiple blockchains — each with its own language and ecosystem.

| # | Resource | Blockchain | Language | Link |
|:-:|----------|------------|----------|:----:|
| 11 | **Base Developer Docs** | Base (Ethereum L2) | Solidity | [🔗 Visit](https://docs.base.org/get-started/base) |
| 12 | **Polygon dApp Launchpad** | Polygon (Ethereum L2) | Solidity | [🔗 Visit](https://docs.polygon.technology/tools/dApp-development/launchpad/quickstart) |
| 13 | **Solana Documentation** | Solana | Rust / Anchor | [🔗 Visit](https://solana.com/docs) |
| 14 | **Sui Documentation** | Sui | Move | [🔗 Visit](https://docs.sui.io/) |
| 15 | **The Move Book (Sui)** | Sui | Move | [🔗 Visit](https://examples.sui.io/) |
| 16 | **The Cairo Book** | Starknet | Cairo | [🔗 Visit](https://www.starknet.io/cairo-book/) |
| 17 | **Starknet Docs** | Starknet | Cairo | [🔗 Visit](https://docs.starknet.io/) |

```mermaid
graph TB
    subgraph EVM["🔷 EVM Chains — Solidity"]
        ETH["Ethereum"]
        BASE["Base L2"]
        POLY["Polygon L2"]
    end

    subgraph ALT["🔶 Alt Chains"]
        SOL["Solana<br/><small>Rust / Anchor</small>"]
        SUI_C["Sui<br/><small>Move</small>"]
        STARK["Starknet<br/><small>Cairo</small>"]
    end

    LEARN["🧑‍💻 You"] --> EVM
    LEARN --> ALT

    style EVM fill:#0d1117,stroke:#58a6ff,color:#c9d1d9,stroke-width:2px
    style ALT fill:#0d1117,stroke:#f0883e,color:#c9d1d9,stroke-width:2px
    style LEARN fill:#161b22,stroke:#2ea043,color:#c9d1d9
    style ETH fill:#161b22,stroke:#58a6ff,color:#c9d1d9
    style BASE fill:#161b22,stroke:#58a6ff,color:#c9d1d9
    style POLY fill:#161b22,stroke:#58a6ff,color:#c9d1d9
    style SOL fill:#161b22,stroke:#d2a8ff,color:#c9d1d9
    style SUI_C fill:#161b22,stroke:#7ee787,color:#c9d1d9
    style STARK fill:#161b22,stroke:#ff7b72,color:#c9d1d9
```

---

### 🌉 Oracles, Indexing & Storage

> Essential middleware for production-grade dApps.

| # | Resource | Purpose | What You'll Build | Link |
|:-:|----------|---------|-------------------|:----:|
| 18 | **Chainlink Developer Bootcamp** | Price feeds, VRF, Automation, CCIP | Oracle-powered dApps | [🔗 Visit](https://chain.link/bootcamp/on-demand) |
| 19 | **Chainlink Tutorials** | Step-by-step project guides | NFT marketplaces, cross-chain apps | [🔗 Visit](https://chain.link/tutorials) |
| 20 | **The Graph Academy** | Indexing on-chain data with subgraphs | Queryable blockchain data APIs | [🔗 Visit](https://thegraph.academy/course/the-graph-intro-course/) |
| 21 | **IPFS Documentation** | Decentralized file storage & hosting | Store NFT metadata, host dApps | [🔗 Visit](https://docs.ipfs.tech/) |

```mermaid
flowchart TB
    DAPP["🏗️ Your dApp"] -->|"needs real-world data"| CL["⛓️ Chainlink Oracles"]
    DAPP -->|"needs to query chain"| TG["📊 The Graph"]
    DAPP -->|"needs file storage"| IP["📦 IPFS"]

    CL --> |"Price feeds, VRF,<br/>Automation"| DAPP
    TG --> |"GraphQL API for<br/>on-chain events"| DAPP
    IP --> |"Content-addressed<br/>file storage"| DAPP

    style DAPP fill:#161b22,stroke:#58a6ff,color:#c9d1d9,stroke-width:2px
    style CL fill:#161b22,stroke:#375bd2,color:#c9d1d9
    style TG fill:#161b22,stroke:#6f4cff,color:#c9d1d9
    style IP fill:#161b22,stroke:#65c2cb,color:#c9d1d9
```

---

### 🏆 Challenges, CTFs & Hands-On Practice

> Level up by solving real security puzzles and building projects.

| # | Resource | Difficulty | What You'll Practice | Link |
|:-:|----------|:----------:|----------------------|:----:|
| 22 | **Ethernaut (OpenZeppelin)** | 🟡 Medium | Solidity vulnerabilities — reentrancy, overflow, access control | [🔗 Visit](https://ethernaut.openzeppelin.com/) |
| 23 | **Damn Vulnerable DeFi** | 🔴 Hard | DeFi exploit patterns — flash loans, governance attacks | [🔗 Visit](https://github.com/OpenZeppelin/damn-vulnerable-defi) |
| 24 | **Speedrun Ethereum** | 🟢 Easy-Med | Build & deploy real dApps — DEX, staking, NFTs | [🔗 Visit](https://speedrunethereum.com/) |
| 25 | **BuidlGuidl CTF** | 🟡 Medium | Solidity puzzles and pattern recognition | [🔗 Visit](https://ctf.buidlguidl.com/) |
| 26 | **Node Guardians** | 🟡 Medium | Quest-based learning with RPG-style progression | [🔗 Visit](https://nodeguardians.io/) |

```mermaid
graph LR
    A["🟢 Speedrun<br/>Ethereum<br/><small>Build dApps</small>"] --> B["🟡 Ethernaut<br/><small>Security basics</small>"]
    B --> C["🟡 Node<br/>Guardians<br/><small>RPG quests</small>"]
    C --> D["🟡 BuidlGuidl<br/>CTF<br/><small>Puzzles</small>"]
    D --> E["🔴 Damn<br/>Vulnerable DeFi<br/><small>Exploits</small>"]

    style A fill:#161b22,stroke:#2ea043,color:#c9d1d9
    style B fill:#161b22,stroke:#f0883e,color:#c9d1d9
    style C fill:#161b22,stroke:#f0883e,color:#c9d1d9
    style D fill:#161b22,stroke:#f0883e,color:#c9d1d9
    style E fill:#161b22,stroke:#f85149,color:#c9d1d9
```

---

### 🎓 Full Courses & Bootcamps

> Structured, comprehensive courses that take you from zero to builder.

| # | Resource | Duration | What's Covered | Link |
|:-:|----------|:--------:|----------------|:----:|
| 27 | **Cyfrin Updraft** | 50+ hrs | Solidity, Foundry, DeFi, Security, Advanced patterns | [🔗 Visit](https://updraft.cyfrin.io/courses) |
| 28 | **freeCodeCamp × Patrick Collins (32hr)** | 32 hrs | Full-stack Web3 with JavaScript — contracts to frontend | [🔗 YouTube](https://www.youtube.com/watch?v=gyMwXuJrbJQ) |
| 29 | **Solana Developer Bootcamp 2026** | 12+ hrs | Solana programs, clients, full-stack crypto development | [🔗 YouTube](https://www.youtube.com/watch?v=2pcm7ICRJKU) |
| 30 | **Chainlink Bootcamp (On-Demand)** | 8+ hrs | Solidity + Chainlink oracles, VRF, automation | [🔗 Visit](https://chain.link/bootcamp/on-demand) |
| 31 | **LearnWeb3** | Self-paced | Track-based: Freshman → Senior, NFTs, DeFi | [🔗 Visit](https://learnweb3.xyz/) |
| 32 | **Uniswap Developer Guide** | Self-paced | DeFi protocol integration, swaps, liquidity pools | [🔗 Visit](https://developers.uniswap.org/docs/protocols/v2/guides/getting-started) |

---

## 🇮🇳 Hindi YouTube Resources

> **हिंदी में Web3 सीखें** — ये सभी verified channels और playlists हैं जो high-quality Hindi content provide करते हैं।

### 📺 Channel: Code Eater

> *India's most popular Hindi blockchain education channel with 100K+ subscribers.*

| # | Topic | Video / Playlist | Duration | Link |
|:-:|-------|------------------|:--------:|:----:|
| 1 | Blockchain fundamentals | Blockchain Full Course — 6 hours | ~6 hrs | [▶️ Watch](https://www.youtube.com/watch?v=6aF6p2VUORE) |
| 2 | Solidity programming | Solidity Programming Tutorial Hindi | ~4 hrs | [▶️ Watch](https://www.youtube.com/watch?v=NqGe942J4Y0) |
| 3 | Web3 frontend | web3.js Full Course Hindi | ~3 hrs | [▶️ Watch](https://www.youtube.com/watch?v=u3PtGMRmGA0) |
| 4 | Development tools | Hardhat Full Course Hindi | ~4 hrs | [▶️ Watch](https://www.youtube.com/watch?v=6SYsy1ZlOPo) |
| 5 | Project building | Solidity Project for Beginners | ~2 hrs | [▶️ Watch](https://www.youtube.com/watch?v=aFI_XPll_mg) |
| 6 | NFT development | NFT Full Course (Playlist) | Multi-part | [▶️ Watch](https://www.youtube.com/playlist?list=PLgPmWS2dQHW8AUns9PlkBW_vQsPr7fO9H) |
| 7 | Starknet & Cairo | Starknet & Cairo Introduction Hindi | ~1 hr | [▶️ Watch](https://www.youtube.com/watch?v=OmlsK_Wvzss) |

---

### 📺 Channel: web3Mantra

> *Comprehensive blockchain development tutorials in Hindi with project-based learning.*

| # | Topic | Video / Playlist | Duration | Link |
|:-:|-------|------------------|:--------:|:----:|
| 8 | Complete blockchain dev | Complete Blockchain Dev Course | ~8 hrs | [▶️ Watch](https://www.youtube.com/watch?v=RkYVVC2vXho) |
| 9 | Solidity deep dive | Solidity Full Course in Hindi (Playlist) | Multi-part | [▶️ Watch](https://www.youtube.com/playlist?list=PLR0uCBk15bq9a__TgfcZ7oA73MTEZ3NOK) |
| 10 | Real-world dApp | Web3 Crowdfunding dApp in Hindi | ~3 hrs | [▶️ Watch](https://www.youtube.com/watch?v=ls1Noh2b5Ms) |

---

### 📺 Channel: Pepcoding

> *Well-known Indian coding education platform with a dedicated Solidity playlist.*

| # | Topic | Video / Playlist | Duration | Link |
|:-:|-------|------------------|:--------:|:----:|
| 11 | Solidity 0.8 | Pepcoding Solidity in Hindi (Playlist) | Multi-part | [▶️ Watch](https://www.youtube.com/playlist?list=PL-Jc9J83PIiG6_thChXWzolj9BEG-Y0gh) |

---

### 📺 Bonus: Smart Contract Programmer (English)

> *Best for Solidity deep-dives — DeFi protocols, gas optimization, and patterns.*

| # | Topic | Link |
|:-:|-------|:----:|
| 12 | Solidity patterns, DeFi code walkthroughs, gas optimization | [▶️ Channel](https://www.youtube.com/@smartcontractprogrammer) |

---

### 🎯 Recommended Hindi Learning Path

```mermaid
graph TD
    A["📖 Code Eater<br/>Blockchain Full Course<br/><small>6 hours — basics to advanced</small>"]
    B["📝 Code Eater<br/>Solidity Tutorial<br/><small>Learn the language</small>"]
    C["🎮 CryptoZombies<br/><small>Practice Solidity interactively</small>"]
    D["🛠️ Code Eater<br/>Hardhat Course<br/><small>Professional dev setup</small>"]
    E["🌐 Code Eater<br/>web3.js Course<br/><small>Connect frontend to chain</small>"]
    F["🏗️ web3Mantra<br/>Crowdfunding dApp<br/><small>Build a real project</small>"]
    G["🎨 Code Eater<br/>NFT Course<br/><small>Create and deploy NFTs</small>"]
    H["🚀 Speedrun Ethereum<br/><small>Build portfolio projects</small>"]

    A --> B --> C --> D --> E --> F --> G --> H

    style A fill:#1a1a2e,stroke:#e94560,color:#fff,stroke-width:2px
    style B fill:#1a1a2e,stroke:#f39c12,color:#fff,stroke-width:2px
    style C fill:#1a1a2e,stroke:#2ecc71,color:#fff,stroke-width:2px
    style D fill:#1a1a2e,stroke:#3498db,color:#fff,stroke-width:2px
    style E fill:#1a1a2e,stroke:#9b59b6,color:#fff,stroke-width:2px
    style F fill:#1a1a2e,stroke:#e67e22,color:#fff,stroke-width:2px
    style G fill:#1a1a2e,stroke:#1abc9c,color:#fff,stroke-width:2px
    style H fill:#1a1a2e,stroke:#2ecc71,color:#fff,stroke-width:2px
```

---

## 🧭 Ecosystem Map

> See how all the tools, chains, and protocols connect in the Web3 ecosystem.

```mermaid
mindmap
  root((🌐 Web3<br/>Ecosystem))
    📜 Smart Contract Languages
      Solidity
        EVM Chains
        Most popular
      Rust
        Solana
        High performance
      Move
        Sui / Aptos
        Resource-oriented
      Cairo
        Starknet
        ZK-powered
    🔗 Blockchains
      Ethereum
        Base L2
        Polygon L2
        Starknet L2
      Solana
        High throughput
        Low fees
      Sui
        Object-centric
        Parallel execution
    🛠️ Dev Tools
      Foundry
        forge test
        cast send
        anvil
      Hardhat
        Tasks
        Plugins
        TypeScript
      Remix IDE
        Browser-based
        Quick prototyping
      Scaffold-ETH 2
        Full-stack
        Next.js ready
    🌉 Infrastructure
      Chainlink
        Oracles
        VRF
        CCIP
      The Graph
        Subgraphs
        GraphQL
      IPFS
        File storage
        NFT metadata
    🎓 Learning
      CryptoZombies
      Cyfrin Updraft
      Ethernaut
      SpeedRun ETH
      LearnWeb3
```

---

## 🛤️ 90-Day Learning Plan

> A structured plan to go from zero blockchain knowledge to building and deploying your own dApps.

### 📅 Month 1 — Foundations & Solidity

```mermaid
gantt
    title Month 1 — Foundations & Solidity
    dateFormat  X
    axisFormat %s

    section Week 1-2
    Ethereum Learn Hub & Concepts     :a1, 0, 14
    section Week 2-3
    Solidity Docs + Solidity by Example :a2, 7, 21
    section Week 3-4
    CryptoZombies (all levels)          :a3, 14, 28
    section Week 4
    Remix IDE — deploy first contract   :a4, 21, 28
```

| Week | Focus | Resources | Goal |
|:----:|-------|-----------|------|
| 1–2 | Blockchain fundamentals | Ethereum Learn Hub, Code Eater (6hr course) | Understand blocks, txns, gas, wallets |
| 2–3 | Solidity basics | Solidity Docs, Solidity by Example | Write functions, mappings, events |
| 3–4 | Interactive practice | CryptoZombies (all 6 lessons) | Build a complete game contract |
| 4 | First deployment | Remix IDE on Sepolia testnet | Deploy & verify your first contract |

---

### 📅 Month 2 — Tooling & Full-Stack

| Week | Focus | Resources | Goal |
|:----:|-------|-----------|------|
| 5–6 | Dev framework | Foundry or Hardhat (pick one) | Write tests, scripts, deploy locally |
| 6–7 | Frontend integration | ethers.js / wagmi, Code Eater web3.js course | Connect wallet, read/write contracts |
| 7–8 | Full-stack dApp | Scaffold-ETH 2 or Speedrun Ethereum | Build & deploy a working dApp |
| 8 | OpenZeppelin | Use OZ Contracts, ERC-20/721 Wizard | Create a token and an NFT |

---

### 📅 Month 3 — Security, DeFi & Beyond

| Week | Focus | Resources | Goal |
|:----:|-------|-----------|------|
| 9–10 | Smart contract security | Ethernaut (first 15 levels) | Identify common vulnerabilities |
| 10–11 | DeFi concepts | Uniswap Guide, Damn Vulnerable DeFi | Understand AMMs, flash loans |
| 11–12 | Middleware & multi-chain | Chainlink, The Graph, IPFS | Integrate oracles, indexing, storage |
| 12 | Portfolio project | Combine everything learned | Deploy a production-quality dApp |

---

## 📊 Resource Comparison Matrix

> Quick comparison to help you choose the right resource for your level.

| Resource | Beginner | Intermediate | Advanced | Interactive | Free | Has Hindi |
|----------|:--------:|:------------:|:--------:|:-----------:|:----:|:---------:|
| Ethereum Learn Hub | ✅ | ❌ | ❌ | ❌ | ✅ | ❌ |
| CryptoZombies | ✅ | ✅ | ❌ | ✅ | ✅ | ❌ |
| Solidity by Example | ✅ | ✅ | ❌ | ❌ | ✅ | ❌ |
| Cyfrin Updraft | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ |
| Ethernaut | ❌ | ✅ | ✅ | ✅ | ✅ | ❌ |
| Damn Vulnerable DeFi | ❌ | ❌ | ✅ | ✅ | ✅ | ❌ |
| Speedrun Ethereum | ❌ | ✅ | ✅ | ✅ | ✅ | ❌ |
| Code Eater (YT) | ✅ | ✅ | ❌ | ❌ | ✅ | ✅ |
| web3Mantra (YT) | ✅ | ✅ | ✅ | ❌ | ✅ | ✅ |
| Patrick Collins 32hr | ✅ | ✅ | ❌ | ❌ | ✅ | ❌ |
| LearnWeb3 | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ |
| Node Guardians | ❌ | ✅ | ✅ | ✅ | ✅ | ❌ |

---

## 🔑 Quick Reference: Key Concepts

```mermaid
graph LR
    subgraph CORE["Core Concepts"]
        direction TB
        BC["⛓️ Blockchain<br/><small>Immutable distributed ledger</small>"]
        SC["📜 Smart Contract<br/><small>Self-executing on-chain code</small>"]
        GAS["⛽ Gas<br/><small>Computation fee in ETH/GWEI</small>"]
        WALLET["👛 Wallet<br/><small>Public + Private key pair</small>"]
    end

    subgraph TOKENS["Token Standards"]
        direction TB
        E20["🪙 ERC-20<br/><small>Fungible tokens (USDC, UNI)</small>"]
        E721["🖼️ ERC-721<br/><small>NFTs — unique tokens</small>"]
        E1155["🎁 ERC-1155<br/><small>Multi-token standard</small>"]
    end

    subgraph DEFI["DeFi Primitives"]
        direction TB
        AMM["💱 AMM<br/><small>Automated Market Maker</small>"]
        LP["🏊 Liquidity Pool<br/><small>Token pairs for trading</small>"]
        FL["⚡ Flash Loan<br/><small>Uncollateralized instant loan</small>"]
    end

    CORE ~~~ TOKENS ~~~ DEFI

    style CORE fill:#0d1117,stroke:#58a6ff,color:#c9d1d9,stroke-width:2px
    style TOKENS fill:#0d1117,stroke:#7ee787,color:#c9d1d9,stroke-width:2px
    style DEFI fill:#0d1117,stroke:#d2a8ff,color:#c9d1d9,stroke-width:2px
    style BC fill:#161b22,stroke:#58a6ff,color:#c9d1d9
    style SC fill:#161b22,stroke:#58a6ff,color:#c9d1d9
    style GAS fill:#161b22,stroke:#58a6ff,color:#c9d1d9
    style WALLET fill:#161b22,stroke:#58a6ff,color:#c9d1d9
    style E20 fill:#161b22,stroke:#7ee787,color:#c9d1d9
    style E721 fill:#161b22,stroke:#7ee787,color:#c9d1d9
    style E1155 fill:#161b22,stroke:#7ee787,color:#c9d1d9
    style AMM fill:#161b22,stroke:#d2a8ff,color:#c9d1d9
    style LP fill:#161b22,stroke:#d2a8ff,color:#c9d1d9
    style FL fill:#161b22,stroke:#d2a8ff,color:#c9d1d9
```

---

## 🤝 Contributing

Found a broken link or want to add a resource? Contributions are welcome!

1. **Fork** this repository
2. **Add** your resource to the appropriate section
3. **Verify** the link is working and the resource is genuinely free
4. **Submit** a Pull Request

### Contribution Guidelines

- ✅ Resource must be **100% free** (no paywalled content)
- ✅ Resource must be **actively maintained** (updated within the last 12 months)
- ✅ Include a brief description of what the resource teaches
- ✅ Hindi resources should be clearly marked with 🇮🇳

---

## 📄 License

This resource list is released under the [MIT License](LICENSE). Share it freely! 🚀

---

<p align="center">
  <strong>⭐ If this helped you, give it a star!</strong><br/>
  <em>Built with ❤️ for the Web3 community</em><br/><br/>
  <img src="https://img.shields.io/badge/Made%20with-❤️-red?style=flat-square" alt="Made with love"/>
  <img src="https://img.shields.io/badge/PRs-Welcome-brightgreen?style=flat-square" alt="PRs Welcome"/>
</p>
