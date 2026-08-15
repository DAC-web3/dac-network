# DACnetwork — Architecture

**Version:** 1.0 | **Date:** August 2026 | **Status:** Documentation

---

## Overview

DACnetwork is designed as a multi-layer decentralized ecosystem built on the Solana blockchain.

Five independent layers operate under one shared economic layer powered by the $DAC utility token. Each layer addresses a different type of real-world contribution while sharing the same utility and identity infrastructure.

---

## Ecosystem Structure

DACnetwork
│
├── Activity Layer
│ └── rutaX
│ Status: IN DEVELOPMENT
│ Proof-of-Activity mobile application
│
├── Social Layer
│ └── DACmeta
│ Status: PLANNED
│ Digital society, VR/AR, 3D creation, marketplace
│
├── Physical Layer
│ └── DAC Smart Systems
│ Status: RESEARCH
│ DePIN, edge nodes, physical infrastructure
│
├── Communication Layer
│ └── DACx
│ Status: LIVE (Beta v1.5.6 — Android)
│ Private messaging, xID identity, Solana wallet
│
└── Economic Layer
└── $DAC Token
Status: LIVE (Solana Mainnet)
Utility token — Token-2022 Standard

---

## Layer Status

| Layer | Product | Status |
|-------|---------|--------|
| Activity | rutaX | 🔄 IN DEVELOPMENT |
| Social | DACmeta | 📋 PLANNED |
| Physical | DAC Smart Systems | 🔬 RESEARCH |
| Communication | DACx | ✅ LIVE — Beta v1.5.6 |
| Economic | $DAC Token | ✅ LIVE — Solana Mainnet |

---

## Layer Details

### Activity Layer — rutaX

**Status:** IN DEVELOPMENT

rutaX is the Proof-of-Activity mobile application of DACnetwork.

**Designed to:**
- Track verified physical movement via GPS
- Reward users with $DAC for validated activity
- Apply multi-layer anti-fraud validation

**Reward model (designed):**
- 1 $DAC per 10 km of GPS-validated activity
- Maximum 10 $DAC per user per day

**Anti-fraud layers (designed):**
- Speed verification — movement above 20 km/h invalidated
- Altitude validation — trajectory anomaly detection
- Route analysis — suspicious pattern detection
- GPS spoofing detection
- Machine learning behavioral model

**Platform:** iOS & Android (in development)

---

### Social Layer — DACmeta

**Status:** PLANNED

DACmeta is the digital society layer of DACnetwork.

**Designed to include:**
- Virtual meeting and social spaces
- 3D asset creation and marketplace
- NFT creation and trading
- Photogrammetry — real objects as digital assets
- Creator economy powered by $DAC

**Access model (designed):**
- Public spaces — free for all users
- Premium experiences — accessible via $DAC
- Creator monetization — direct, no intermediaries

---

### Physical Layer — DAC Smart Systems

**Status:** RESEARCH

DAC Smart Systems is the DePIN (Decentralized Physical Infrastructure Network) layer of DACnetwork.

**Designed around:**
- Autonomous edge nodes with local processing
- Privacy by design — minimal data collection
- No mandatory cloud dependency
- Standard IoT protocol compatibility
- On-chain contribution verification

**Core principle:**
Technology must protect human freedom, not replace it.
Final authority always belongs to the human.

---

### Communication Layer — DACx

**Status:** LIVE — Beta v1.5.6 (Android)

DACx is the private communication and identity layer of DACnetwork.

**Currently live:**
- xID identity — 9-digit unique identity, no phone or email
- Mutual contact system — bilateral consent required
- Ephemeral messages — disappear 3 minutes after read
- Solana self-custody wallet — bound to xID + PIN
- Voice calls — WebRTC
- Push notifications — FCM
- OTA updates — automatic, no reinstall needed
- PIN Vault — required on every app open
- Privacy cover — app switcher shows only logo
- Auto-lock — configurable timer
- 24 emoji reactions + Delete for both
- Custom SVG icon set

**Download:** www.dacnetwork.io
**Repository:** https://github.com/DAC-web3/dacx

---

### Economic Layer — $DAC Token

**Status:** LIVE — Solana Mainnet

$DAC is the native utility token of the DACnetwork ecosystem.

| Parameter | Value |
|-----------|-------|
| Token Name | DACnetwork |
| Symbol | $DAC |
| Blockchain | Solana Mainnet |
| Standard | Token Extensions Program (Token-2022) |
| Total Supply | 3,000,000,000 $DAC (fixed, immutable) |
| Transfer Fee | 0.5% per transaction (auto-burn) |
| Mint Authority | REVOKED |
| Freeze Authority | REVOKED |
| Contract | `4m9XHiFaZcoUiMxaJH9DbxSXJXuQuXASw3q35hZPjghb` |
| Explorer | https://solscan.io/token/4m9XHiFaZcoUiMxaJH9DbxSXJXuQuXASw3q35hZPjghb |

---

## Value Flow

Physical Activity (rutaX) → $DAC rewards
Digital Creation (DACmeta) → $DAC rewards
Infrastructure (DAC Smart Systems) → $DAC rewards
Private Communication (DACx) → $DAC integration
↓
$DAC → Used across entire ecosystem
↓
0.5% fee per on-chain transaction
↓
Auto-burn → Reduced circulating supply

---

## Identity Architecture — xID

xID is the universal identity layer of DACnetwork, currently implemented in DACx.

**Designed as universal identity:**

xID
├─ DACx (messaging + wallet) — LIVE
├─ rutaX (Proof of Activity) — IN DEVELOPMENT
├─ DACmeta (social / VR) — PLANNED
└─ DAC Smart Systems (nodes) — RESEARCH

---

## Blockchain Layer

| Property | Value |
|----------|-------|
| Blockchain | Solana |
| Token Standard | Token-2022 (Token Extensions Program) |
| Transfer Fee Extension | 0.5% auto-burn |
| Wallet Compatibility | Phantom, Solflare, and compatible Solana wallets |
| DACx Wallet | Self-custody, xID-bound, PIN-secured |

---

## Repositories

| Repository | Description | Status |
|------------|-------------|--------|
| [dac-network](https://github.com/DAC-web3/dac-network) | Main documentation repository | ✅ Active |
| [dacx](https://github.com/DAC-web3/dacx) | DACx private messenger | ✅ Active |

---

## Documentation

| Document | Description |
|----------|-------------|
| [README.md](./README.md) | Project overview |
| [WHITEPAPER.md](./WHITEPAPER.md) | Full technical whitepaper v2.0 |
| [TOKENOMICS.md](./TOKENOMICS.md) | Token allocation structure |
| [ROADMAP.md](./ROADMAP.md) | Development roadmap |
| [GOVERNANCE.md](./GOVERNANCE.md) | DAO governance model |
| [SECURITY.md](./SECURITY.md) | Security policy |
| [CONTRIBUTING.md](./CONTRIBUTING.md) | How to contribute |
| [CHANGELOG.md](./CHANGELOG.md) | Version history |
| [PROGRESS.md](./PROGRESS.md) | Live progress updates |
| [TEAM.md](./TEAM.md) | Founding team |

---

## Design Principles

- **Privacy by architecture** — data minimization, local processing
- **Human authority** — technology assists, humans decide
- **Contribution first** — activity precedes reward
- **Transparency** — verifiable on-chain
- **Sustainability** — long-term ecosystem over short-term speculation

---

*DACnetwork • Asociația DACnetwork Web3 • București, România*
*dacnetwork.io • X: @DACLabs*

*This document describes the designed architecture of DACnetwork.*
*Clearly distinguishes between what is LIVE, IN DEVELOPMENT, RESEARCH and PLANNED.*
