# DACnetwork Whitepaper v2.0
## $DAC — Token of Society

**Version 2.0 | Updated September 2026**

> A decentralized ecosystem on Solana where human activity, digital creation, physical infrastructure and private communication become verifiable value.

Asociația DACnetwork Web3 (registration in progress under Romanian law OG 26/2000) | Bucharest, Romania | [dacnetwork.io](https://dacnetwork.io) | X: [@DACLabs](https://x.com/DACLabs)

**DISCLAIMER (MiCA Art. 6):** This white paper has not been examined or approved by any competent authority. $DAC is a utility token. Not an investment. Not a financial instrument. No profit guaranteed. No returns promised. Participation involves risk.

---

## Table of Contents

- [00. Executive Summary](#00-executive-summary)
- [01. Why DACnetwork?](#01-why-dacnetwork)
- [02. The DACnetwork Ecosystem](#02-the-dacnetwork-ecosystem)
- [03. The $DAC Utility Token](#03-the-dac-utility-token)
- [04. Tokenomics & Public Presale](#04-tokenomics--public-presale)
- [05. Governance & DAO](#05-governance--dao)
- [06. The DAC Economic Model](#06-the-dac-economic-model)
- [07. Security & Trust Framework](#07-security--trust-framework)
- [08. Legal Framework & MiCA Alignment](#08-legal-framework--mica-alignment)
- [09. Risk Management](#09-risk-management)
- [10. Roadmap 2026–2030](#10-roadmap-20262030)
- [11. Conclusion](#11-conclusion)
- [12. Technical Architecture](#12-technical-architecture)
- [13. $DAC Token Lifecycle](#13-dac-token-lifecycle)
- [14. Ecosystem Participation](#14-ecosystem-participation)
- [15. Transparency & Treasury](#15-transparency--treasury)
- [16. DACx — Private Communication Layer](#16-dacx--private-communication-layer)
- [17. Frequently Asked Questions](#17-frequently-asked-questions)

---

## 00. Executive Summary

DACnetwork is a decentralized Web3 ecosystem built on the Solana blockchain with the mission of transforming real human activity into verifiable digital value.

Unlike speculative crypto projects, DACnetwork is designed around measurable utility. Every token distributed within the ecosystem is intended to represent a real contribution made by users, creators, infrastructure operators, or community participants.

### Four Ecosystem Pillars

| # | Product | Type | Status | Description |
|---|---------|------|--------|-------------|
| 01 | rutaX | Proof of Activity | In development (Devnet) | Mobile app rewarding verified physical movement. GPS-validated, anti-fraud protected. Rewards are Devnet, not $DAC mainnet. |
| 02 | DACmeta | Digital Society | Planned | Structured virtual environments for interaction, digital creation and a decentralized marketplace. |
| 03 | DAC Smart Systems | DePIN | Research | Physical edge nodes extending DACnetwork into the real world through decentralized infrastructure. |
| 04 | DACx | Private Communication | Beta live (Android v1.5.6) | Ephemeral messaging with xID identity and a self-custody Solana Devnet wallet. No phone. No email. Messages are not end-to-end encrypted yet. |

### The $DAC Token

$DAC is the native utility token of the DACnetwork ecosystem. Its designed functions include access to ecosystem services, payments inside DACmeta, rewards for Proof of Activity, rewards for infrastructure contributions, digital marketplace transactions, and community governance through future DAO mechanisms.

**$DAC does not represent equity, ownership, shares, dividends or any financial claim against the issuer.** The token exists to enable and support the functionality of the DACnetwork ecosystem.

### Token Parameters

| Parameter | Specification |
|-----------|---------------|
| Token Name | DACnetwork |
| Symbol | $DAC |
| Blockchain | Solana Mainnet |
| Standard | Token Extensions Program (Token-2022) |
| Total Supply | 3,000,000,000 $DAC (fixed, immutable) |
| Decimals | 9 |
| Transfer Fee | 0.5% per eligible transfer (auto-burn mechanism) |
| Mint Authority | REVOKED |
| Freeze Authority | REVOKED |
| Mint Address | `4m9XHiFaZcoUiMxaJH9DbxSXJXuQuXASw3q35hZPjghb` |
| Metadata URI | `https://dacnetwork.io/dac-metadata.json` |
| Logo | `https://dacnetwork.io/DAC_logo.png` |
| Explorer | https://solscan.io/token/4m9XHiFaZcoUiMxaJH9DbxSXJXuQuXASw3q35hZPjghb |

On-chain metadata is Metaplex (mutable). The Token-2022 mint itself does not carry a TokenMetadata extension (the mint was created without it; mint authority is revoked).

---

## 01. Why DACnetwork?

### The Problem

Today's digital economy creates enormous value, yet millions of people contribute every day without receiving fair recognition or ownership of the value they generate. People walk, create content, build communities, operate devices, share knowledge and contribute to digital ecosystems, while the economic benefits are often captured by centralized platforms.

Blockchain technology introduced digital ownership, but much of the crypto industry has focused on speculation rather than real-world utility. DACnetwork was created to address this imbalance.

### Our Solution

> Real activity should create real value. Every contribution is measurable. Every verified contribution strengthens the ecosystem.

DACnetwork rewards measurable contribution through four interconnected pillars: Human Activity (rutaX), Digital Creation (DACmeta), Physical Infrastructure (DAC Smart Systems) and Private Communication (DACx).

### Core Principles

- Utility before speculation
- Transparency by default
- Privacy by architecture
- Community-first governance
- Open innovation
- Sustainable decentralization

---

## 02. The DACnetwork Ecosystem

DACnetwork is designed as a decentralized ecosystem where multiple independent products operate under one shared digital economy powered by the $DAC utility token.

```
rutaX — Proof of Activity          (IN DEVELOPMENT — Devnet)
DACmeta — Digital Society          (PLANNED)
DAC Smart Systems — DePIN          (RESEARCH)
DACx — Private Communication       (BETA LIVE — Android v1.5.6)
$DAC — Common utility token        (LIVE — Solana Mainnet)
```

### rutaX — Proof of Activity

rutaX transforms verified physical movement into digital value using GPS validation and anti-fraud checks. Rewarded activities include walking, running, cycling and hiking. Sensitive location data is processed locally whenever possible.

**Live on Devnet now** (`https://api.dacnetwork.io/rutax/health`):

- 1 $DAC per 10 km of GPS-validated activity
- Maximum **5 $DAC per user per day**
- Maximum **50,000 $DAC per day** network-wide
- Identity is linked from DACx (Link rutaX). A typed 9-digit xID is rejected
- Cash-out checks the vault before transfer

**Not live:** mainnet $DAC rewards, public APK, the 240,000,000 $DAC rutaX allocation as a deployed vault.

### DACmeta — Digital Society

DACmeta is planned as a structured digital society — not a speculative gaming metaverse. Designed capabilities include virtual meeting spaces, educational environments, NFT galleries, a digital asset marketplace, and a creator economy.

### DAC Smart Systems — DePIN

Research stage. Edge devices are designed to process locally, publish cryptographic proof when required, and avoid sending unnecessary personal data to centralized servers.

### DACx — Private Communication Layer

DACx is live on Android (Beta v1.5.6) with OTA updates. Members communicate through ephemeral messaging and a self-custody Solana **Devnet** wallet, identified by a unique xID, without a phone number or email. Voice calls are not offered in the current UI. Mainnet $DAC payments inside DACx are a future milestone.

Download: [dacnetwork.io](https://dacnetwork.io) · Releases: https://github.com/DAC-web3/dacx/releases

---

## 03. The $DAC Utility Token

$DAC is not designed as a speculative asset. It is designed to facilitate participation, reward contribution and enable interactions across the ecosystem.

| Utility | Today |
|---------|--------|
| Proof of Activity rewards | Designed. rutaX pays on **Devnet**, not mainnet |
| DACmeta marketplace currency | Planned |
| DePIN infrastructure rewards | Research |
| DACx payments | Devnet DAC only. Mainnet $DAC in DACx is planned |
| Governance | Future DAO |
| Staking | Possible future upgrade, not live |

---

## 04. Tokenomics & Public Presale

**Total supply: 3,000,000,000 $DAC** — no additional tokens can be minted. Mint authority revoked.

| Category | % | Amount | Notes |
|----------|---|---------|--------|
| Community Rewards | 30% | 900,000,000 | PoA, campaigns, creators, governance |
| Ecosystem Development | 25% | 750,000,000 | rutaX, DACmeta, Smart Systems, DACx |
| Treasury | 15% | 450,000,000 | Security, legal, infrastructure, reserves |
| Team & Advisors | 15% | 450,000,000 | Vesting / unlock **not yet finalized (TBD)** |
| Public Presale | 10% | 300,000,000 | **Allocation only.** No active public sale. Price, cap, date, TGE, DEX, vesting: TBD |
| Initial Liquidity | 5% | 150,000,000 | Planned DAC/SOL DEX liquidity — DEX TBD |
| **TOTAL** | **100%** | **3,000,000,000** | Fixed |

Community Rewards breakdown (of total supply): DACx users 10% (300M), rutaX 8% (240M), campaigns 5% (150M), creators 4% (120M), early supporters 3% (90M).

Full subcategory tables: [TOKENOMICS.md](./TOKENOMICS.md)

### Burn

Every eligible on-chain transfer retains 0.5% via the Token-2022 Transfer Fee extension. Collected tokens are periodically sent to the Solana Incinerator and permanently destroyed. Burns are announced on X (@DACLabs) and verifiable on Solscan.

---

## 05. Governance & DAO

| Phase | Status | Description |
|-------|--------|-------------|
| Phase 0 — Foundation | In progress | Coordination by the DACnetwork Web3 Association (legal registration in progress). Community feedback via official channels |
| Phase 1 — Community Participation | In progress | Non-binding community proposals |
| Phase 2 — Hybrid Governance | Planned | Selected decisions subject to community vote; Association keeps legal duties |
| Phase 3 — DAO Governance | Planned | On-chain voting for treasury, protocol and ecosystem decisions |

---

## 06. The DAC Economic Model

Contribution → Reward → Utility → Participation → Growth.

Humans contribute. Devices measure. Edge systems process. Blockchain verifies. The ecosystem rewards.

Growth is based on cooperation: users, creators, organizations, infrastructure operators and the Association benefit if the ecosystem is actually used.

---

## 07. Security & Trust Framework

- Fixed supply. Mint authority revoked.
- Freeze authority revoked — holders keep control of their tokens.
- Every $DAC transaction is publicly verifiable on Solana.
- Privacy by architecture: process locally; transmit cryptographic proof when needed.
- Prefer audited, widely used token standards over unnecessary custom programs.

Trust is built by what can be verified, not by marketing claims.

---

## 08. Legal Framework & MiCA Alignment

The project is developed by Asociația DACnetwork Web3, a non-profit **being established** under Romanian law (OG 26/2000). This white paper is **MiCA-aligned**, not a claim of completed regulatory approval.

$DAC is designed as a utility token under Regulation (EU) 2023/1114. It does not represent company shares, ownership rights, debt instruments, investment contracts or profit-sharing rights.

**MiCA Art. 6:** this white paper has not been examined or approved by any competent authority.

---

## 09. Risk Management

| Risk | Description |
|------|-------------|
| Market | Value of $DAC may increase, decrease or become zero |
| Adoption | Slower than expected community adoption |
| Technology | Outages, bugs, cybersecurity incidents |
| Regulatory | Future legislation may affect operations |
| Operational | Delays, budget, technical complexity |
| Liquidity | Limited trading after any DEX listing |
| Keys | Users are responsible for protecting private keys |

---

## 10. Roadmap 2026–2030

Roadmap may change. Planned milestones are not guarantees.

| Phase | Period | Status | Milestones |
|-------|--------|--------|------------|
| 0 | 2026 | In progress | Association registration in progress; whitepaper v2.0; $DAC live; DACx Beta v1.5.6; **website live**; community; GitHub docs; rutaX Devnet |
| 1 | 2026–2027 | In progress | rutaX public beta; GPS anti-fraud; DACmeta prototype; Smart Systems prototype; DACx public launch / iOS |
| 2 | 2027 | Planned | Official rutaX; DACmeta beta; Marketplace v1; public presale (TBD); DEX listing DAC/SOL (TBD); initial liquidity |
| 3 | 2027–2028 | Planned | International expansion; partnerships; DACx mainnet $DAC payments; governance voting; 50,000+ active users target |
| 4 | 2028–2029 | Planned | DAO; treasury governance; community proposals; governance dashboard |
| 5 | 2030+ | Planned | Large-scale usage; enterprise integrations; self-sustaining DAO |

---

## 11. Conclusion

DACnetwork was created to build a durable digital ecosystem where technology serves people — not another short-lived cryptocurrency. $DAC connects users, creators, organizations and infrastructure through a shared utility layer.

Move. Create. Build. Own your contribution.

---

## 12. Technical Architecture

Five layers share $DAC:

| Layer | Product | Status |
|-------|---------|--------|
| Activity | rutaX | In development — Devnet API live |
| Social | DACmeta | Planned |
| Physical | DAC Smart Systems | Research |
| Communication | DACx | Beta v1.5.6 Android |
| Economic | $DAC | Live — Solana Mainnet Token-2022 |

Architectural principle: humans contribute; devices measure; edge systems process; blockchain verifies; the ecosystem rewards.

---

## 13. $DAC Token Lifecycle

1. **Collection** — 0.5% transfer fees accumulate via Token-2022 Transfer Fee.
2. **Announcement** — planned burn announced on X (@DACLabs).
3. **Incineration** — tokens sent to the Solana Incinerator.
4. **Verification** — transaction hash published on Solscan.

---

## 14. Ecosystem Participation

| Path | Product | How |
|------|---------|-----|
| Physical activity | rutaX | Walk, run, cycle — GPS-validated Proof of Activity (Devnet today) |
| Digital creation | DACmeta | 3D assets, NFTs, virtual spaces (planned) |
| Physical infrastructure | DAC Smart Systems | DePIN nodes (research) |
| Private communication | DACx | xID + Devnet wallet, OTA, honest storage |

---

## 15. Transparency & Treasury

| Principle | Meaning |
|-----------|---------|
| Transparency | Significant treasury activity identifiable when legally and technically possible |
| Responsibility | Allocate to ecosystem priorities, not short-term market noise |
| Sustainability | Long-term ability to build and maintain |
| Accountability | Major decisions documented; later, community oversight |

If it can be verified, make it verifiable. If resources move, show the movement. If tokens are burned, prove the burn.

---

## 16. DACx — Private Communication Layer

> Communication must not become an archive. It must remain consent and moment.

**Version:** 1.5.6 · **Platform:** Android · **Status:** Beta live + OTA  
Download: [dacnetwork.io](https://dacnetwork.io) · https://github.com/DAC-web3/dacx/releases

### 16.1 What it is

DACx is how DACnetwork members speak to each other — by mutual consent, and ephemerally. No phone. No email.

### 16.2 What is live

| Feature | Status | Description |
|---------|--------|-------------|
| xID | Live | 9-digit identity. No phone, no email |
| Message requests | Live | Add by QR or xID. They accept or ignore. Chat starts after accept. Incoming requests are possible — spam is limited by consent, not by claiming zero unsolicited contact |
| Ephemeral messages | Live | Disappear 3 minutes after read. Unread messages are held on DACx servers until read, then deleted. No permanent conversation archive |
| Wallet | Live — **Devnet** | Key created on device. 12-word phrase. Phrase never sent to the server |
| Devnet DAC | Live (OTA) | Token-2022 mint `8NeGLu1s8jQjvrtgpTKPMkGg71NKKpwaMthhUSkfLatR`. View + send. Needs Devnet SOL for fees |
| Hide home balance | Live | Eye toggle |
| OTA + PIN vault | Live | PIN on every open. JS/UI updates without reinstall |
| Push (FCM) | Live | Notifications when the app is closed |
| Link rutaX | Live | Settings → Link rutaX |
| Voice calls | Not in current UI | Hidden on purpose |
| $DAC mainnet | Not live | Mainnet mint is `4m9XHiFaZcoUiMxaJH9DbxSXJXuQuXASw3q35hZPjghb` |
| E2EE | Not live | Planned. Messages currently pass through DACx servers until they disappear |

Old accounts (server-held key) still sign in with xID + PIN. Phrase restore is for on-device keys.

rutaX cash-out goes to the Phantom/Solflare connected in rutaX — not the DACx wallet.

### 16.3 Privacy commitment

- No phone numbers, no emails
- No sale of user data, no behavior monetization
- Recovery phrase never sent to the server
- Messages are **not** end-to-end encrypted yet
- Unread messages sit on DACx servers until they are read, then delete after 3 minutes
- After that, conversation content is not kept as a permanent archive

DACx does **not** claim that conversation content never touches a server.

### 16.4 DACx roadmap

| Phase | Status | Milestones |
|-------|--------|------------|
| 0 | Done | MVP, xID, Android Beta v1.5.6, OTA, Devnet wallet |
| 1 | In progress | Public beta, 1,000+ xIDs, iOS, anti-spam |
| 2 | Planned | Mainnet wallet, multi-app xID, public launch |
| 3 | Planned | E2EE, $DAC payments in DACx, group chat |
| 4 | Planned | DAO integration |

---

## 17. Frequently Asked Questions

**What is DACnetwork?**  
A Solana Web3 ecosystem around real-world participation, digital creation, physical infrastructure and private communication: rutaX, DACmeta, DAC Smart Systems and DACx, sharing the $DAC utility token.

**What is $DAC?**  
The native utility token, Token-2022 on Solana Mainnet. It is not an investment.

**Total supply?**  
3,000,000,000 $DAC, fixed. Mint authority revoked.

**Mint address?**  
`4m9XHiFaZcoUiMxaJH9DbxSXJXuQuXASw3q35hZPjghb` — always verify this address.

**Transfer fee?**  
0.5% on eligible transfers via Token-2022, later burned.

**What is rutaX?**  
Proof-of-Activity app **in development**. Target: 1 $DAC / 10 km, max **5 $DAC / user / day**, max **50,000 $DAC / network / day**. Rewards on **Devnet**, not mainnet. Identity from DACx (Link rutaX).

**What is DACx?**  
Private messenger: ephemeral messages (3 minutes after read), 9-digit xID, built-in Solana Devnet wallet. Android Beta v1.5.6 + OTA. Voice calls not in the current UI. E2EE planned, not live. Devnet DAC mint `8NeGLu1s8jQjvrtgpTKPMkGg71NKKpwaMthhUSkfLatR` is not mainnet $DAC.

**Does $DAC guarantee returns?**  
No. No price, liquidity or listing is guaranteed.

**Where do I verify $DAC?**  
Solscan, mint `4m9XHiFaZcoUiMxaJH9DbxSXJXuQuXASw3q35hZPjghb`.

**Where do I download DACx?**  
[dacnetwork.io](https://dacnetwork.io) and https://github.com/DAC-web3/dacx/releases/latest

---

**DACnetwork · $DAC — Token of Society · 2026**

Asociația DACnetwork Web3 (registration in progress) | Bucharest, Romania

[dacnetwork.io](https://dacnetwork.io) | X: [@DACLabs](https://x.com/DACLabs) | Telegram: [t.me/DACNetwork](https://t.me/DACNetwork)

*$DAC is a utility token. Not an investment. Published under Regulation (EU) 2023/1114 — MiCA. This document has not been examined or approved by any competent authority.*
