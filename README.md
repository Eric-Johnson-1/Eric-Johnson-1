# 👋 Hello, Web3 Wanderers! I'm Eric Johnson

> _In a world of centralized solutions, be the decentralized revolution you want to see_

[![Portfolio](https://img.shields.io/badge/Portfolio-eric--johnson--web3.top-8A2BE2?style=for-the-badge&logo=safari&logoColor=white)](https://eric-johnson-web3.top)
[![Telegram](https://img.shields.io/badge/Telegram-Message-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/eric_johnson_web3)
[![Email](https://img.shields.io/badge/Email-Contact-red?style=for-the-badge&logo=gmail)](mailto:eric.johnson.dev123@gmail.com)

## 🧙‍♂️ Web3 Code Wizard | Smart Contract Alchemist | dApp Architect

When I'm not optimizing gas fees, I'm probably meditating on the next blockchain innovation or hiking somewhere with terrible WiFi but spectacular views.

```solidity
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract AboutEric {
    string public mission = "Building the decentralized future, one block at a time";
    uint256 public web3ExperienceYears = 3;
    uint256 public web2ExperienceYears = 2;
    bool public openToWork = true;
    string public portfolio = "https://eric-johnson-web3.top";

    function getSkills() public pure returns (string[] memory) {
        string[] memory skills = new string[](72);

        // --- Core Smart Contract Architecture & EVM Mechanics ---
        skills[0] = "Solidity (Custom Errors, Yul IR Pipeline, Inline Assembly)";
        skills[1] = "UUPS (Universal Upgradeable Proxy Standard)";
        skills[2] = "EIP-7201 (Namespaced Storage Layouts via Inline Assembly)";
        skills[3] = "ERC-4337 (Account Abstraction, Bundlers & EntryPoint)";
        skills[4] = "ERC-4337 (Verifying Paymaster, ECDSA Signature, postOp Gas Refund)";
        skills[5] = "ERC-5192 (Soulbound SBTs & Non-Transferable Tokens)";
        skills[6] = "ERC-7821 (Minimal Batched Execution)";
        skills[7] = "ERC-1271 (Off-Chain Smart Account Signature Validation)";
        skills[8] = "EIP-712 (Typed Data Hashing & Signing)";
        skills[9] = "ERC-2612 (Gasless ERC20 Permit Approvals)";
        skills[10] = "CREATE2 (Deterministic Deployments & Counterfactual Addresses)";
        skills[11] = "EIP-1167 (Minimal Clones via Clones.cloneDeterministic)";
        skills[12] = "ERC-1967 Proxy (Storage Slot Standard for Upgradeable Proxies)";
        skills[13] = "Gas Optimization (Storage Slot Packing, Bitwise Ops, via_ir)";
        skills[14] = "ERC-721A (Gas-Optimized Batch Minting)";
        skills[15] = "ERC-721 + ERC-5192 (Soulbound Medical Records Architecture)";
        skills[16] = "ERC-1155 (Multi-Token Soulbound Donation Receipts)";
        skills[17] = "ERC-20 Votes + ERC20Permit (Governance Delegation & Snapshots)";

        // --- Cryptography, Math & Decentralized Governance ---
        skills[18] = "Merkle Trees & Cryptographic Proof Verification";
        skills[19] = "On-Chain Quadratic Funding (CLR & Babylonian Sqrt)";
        skills[20] = "DAO Governance (Governor, Timelock, Quorums, GovernorVotesQuorumFraction)";
        skills[21] = "Verifier Staking, Slashing & On-Chain Reputation Scoring";
        skills[22] = "MasterChef V2 LP Farming (allocPoint, IRewarder, accPerShare)";
        skills[23] = "Linear Vesting (Immutable Beneficiary, SafeERC20 Distribution)";
        skills[24] = "AES-256-GCM Encryption (On-Chain/Off-Chain Hybrid, GDPR via Key Destruction)";
        skills[25] = "ECDSA Signature Recovery & MessageHashUtils";

        // --- OpenZeppelin Security Primitives ---
        skills[26] = "OpenZeppelin Contracts & Upgradeable Contracts";
        skills[27] = "AccessControl RBAC (GOVERNOR_ROLE, GUARDIAN_ROLE, MINTER_ROLE)";
        skills[28] = "Ownable2Step (Two-Phase Ownership Transfer)";
        skills[29] = "ReentrancyGuard / Pausable / SafeERC20";
        skills[30] = "Chainlink Oracles (Price Feeds & VRF)";

        // --- L2 Deployment & Multi-Chain ---
        skills[31] = "Base L2 (Deployment, Basescan Verification, Sepolia Testnet)";
        skills[32] = "Arbitrum L2 (Multi-Chain RPC Configuration)";
        skills[33] = "EVM L2 Gas-Optimized Architecture Patterns";

        // --- Local Nodes, Testing & Hacker Workflow ---
        skills[34] = "Foundry (Forge, Anvil, Cast, Chisel)";
        skills[35] = "Invariant & Stateful Fuzz Testing (10,000 CI Fuzz Runs)";
        skills[36] = "Forge Scripts (Solidity Deployment Scripting)";
        skills[37] = "Forge Gas Snapshots & Contract Size Reports";

        // --- Top-Tier Frontend & Web3 Wallet Interactions ---
        skills[38] = "TypeScript (Strict Type Inference)";
        skills[39] = "Next.js (App Router, RSC, SSG, Turbopack)";
        skills[40] = "React / React Server Components";
        skills[41] = "Wagmi (React Hooks for Ethereum)";
        skills[42] = "Viem (Type-safe Ethereum Client)";
        skills[43] = "RainbowKit / ConnectKit / WalletConnect";
        skills[44] = "Tailwind CSS / CSS Grid / Glassmorphism UI";
        skills[45] = "Framer Motion Animations & Micro-Interactions";
        skills[46] = "TanStack Query (Async State & Dual-Source Fallback: API -> IPFS)";
        skills[47] = "Zustand (Global State Management)";
        skills[48] = "Radix UI / Headless Accessible Components";
        skills[49] = "next-intl (Multi-Language i18n)";
        skills[50] = "react-hook-form / Zod Schema Validation";
        skills[51] = "class-variance-authority / clsx / tailwind-merge";
        skills[52] = "Lucide React / next-themes (Dark Mode)";

        // --- High-Performance Backend & Decentralized Infra ---
        skills[53] = "Bun.js (High-performance JS Runtime & Package Manager)";
        skills[54] = "Hono (Ultrafast Edge Web Framework)";
        skills[55] = "Node.js / Express.js Ecosystem";
        skills[56] = "Drizzle ORM (Type-safe SQL, Migrations & Drizzle Kit)";
        skills[57] = "PostgreSQL / Advanced SQL Optimizations";
        skills[58] = "The Graph (GraphQL Subgraph, AssemblyScript, @derivedFrom, Immutable Entities)";
        skills[59] = "IPFS (Pinata SDK / Decentralized Storage & Anti-Censorship)";
        skills[60] = "Satori + Sharp (Dynamic SVG to WebP/PNG Badge Rendering)";
        skills[61] = "Zod (Runtime Schema Validation & @hono/zod-validator)";
        skills[62] = "Upstash Redis (Rate Limiting & Distributed Caching)";
        skills[63] = "Backend Merkle Tree Generation (merkletreejs + keccak256)";

        // --- Systems Engineering, DevOps & Monorepos ---
        skills[64] = "Docker / Docker Compose / Multi-Service Orchestration";
        skills[65] = "GitHub Actions (Multi-Job CI/CD: Forge + Bun + Docker + Gas Snapshots)";
        skills[66] = "Turborepo (Scalable Monorepo / Bun Workspaces)";
        skills[67] = "Multi-Stage Dockerfile Builds (Bun Alpine Production Images)";
        skills[68] = "Graph Node Local Dev Infrastructure (Postgres + IPFS + Graph Node)";

        // --- Architecture, Compliance & SEO ---
        skills[69] = "GDPR-Compliant Decentralized Architectures (IPFS Unpin + Key Rotation)";
        skills[70] = "JSON-LD Structured Data / Open Graph / Twitter Cards (Technical SEO)";
        skills[71] = "Semantic HTML5 / ARIA Accessibility / Progressive Enhancement";

        return skills;
    }

    function contactMe() public view returns (string memory) {
        require(openToWork, "Currently unavailable, but feel free to connect!");
        return "Let's build something amazing together!";
    }
}
```

## 🚀 What I Do

- **Smart Contract Sorcery**: Crafting secure, gas-optimized contracts that even Vitalik would nod approvingly at
- **Front-end Wizardry**: Building seamless dApp experiences with Next.js, Wagmi, and Viem that make Web3 accessible to everyone
- **Decentralized Architecture**: Designing systems that would make centralized services jealous (looking at you, AWS)
- **Gas Optimization**: Because nobody likes paying more ETH than necessary, especially not me!

## 🛠️ Recent Enchantments

### ✨ Staking Platform

Conjured a IDO & staking platform where your tokens work for you while you sleep. Integrated Chainlink oracles for reliable price feeds and Layer 2 solutions to keep those gas fees from burning a hole in your digital wallet.

### 🖼️ NFT Marketplace

Architected an NFT marketplace where digital artists can thrive. Implemented IPFS for decentralized storage because your digital art deserves better than a centralized server that could disappear tomorrow.

### 💚 HopeDAO

Brewed a DAO-powered wishing well where every donation magically multiplies through the arcane art of on-chain quadratic funding. Because saving the world shouldn't require paying a toll to Web2 overlords! Sprinkled with enough Account Abstraction fairy dust so even your grandma can fund public goods without sacrificing her sanity to MetaMask or mainnet gas fees.

### 💉 MedBadge

Cast a level 9 protection spell on flimsy paper vaccination booklets, transmuting them into cryptographically indestructible Soulbound Tokens on Base L2. Your health data is finally locked in your own personal vault—and if you ever wish to vanish into the digital shadows, it's merely one cheeky IPFS unpin away. GDPR compliance has never felt this much like dark magic!

## 📊 GitHub Stats That Don't Tell The Whole Story

![GitHub Stats](https://github-readme-activity-graph.vercel.app/graph?username=Eric-Johnson-1&theme=github-dark)

_Stats are cool, but they don't show the hours debugging a smart contract at 3 AM or the joy when you finally get that complex state management working just right._

## 🧘‍♂️ When Not Coding...

You'll find me exploring nature, cycling through new cities, or deep in meditation trying to visualize Ethereum's state trie. Yes, I'm that kind of blockchain enthusiast!

---

> "The best way to predict the future is to build it... on a blockchain." - Me, probably after too much coffee

_For a deeper dive into my blockchain journey, check out [my portfolio](https://eric-johnson-web3.top). Open to remote Web3 opportunities worldwide. Let's redefine what's possible in the decentralized world!_
