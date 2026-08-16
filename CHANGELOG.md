# Changelog

All notable changes to DACnetwork are documented here.

Format: `[Version] — Date — Description`
## [0.8.3] — 16 August 2026

### Added
- rutaX Devnet network cap: 50,000 $DAC / day
- rutaX vault ATA check before cash-out (503 if empty)
- Cash-out idempotency on signature
- DACx `POST /auth/rutax-attest` + verify; Settings → Link rutaX
- rutaX rejects unsigned / typed xID

### Changed
- rutaX daily user cap documented as **5 $DAC** (matches live API, not 10)

### Not shipped
- $DAC mainnet rewards / 240M vault
- Public rutaX APK
- 180-day runway dashboard
  
---
## [0.8.2] — 16 August 2026

### Added
- DACx phrase restore (OTA + server, runtime 1.5.6)
- Restore with xID → same xID, same Solana address
- Restore with new xID → new identity, same wallet
- Phrase never sent to the server

### Changed
- Wallet slice complete for new (on-device) accounts
- Docs: restore marked live

### Unchanged
- Old accounts still log in with xID + PIN
- Devnet only — not $DAC mainnet
- Voice calls hidden
- Not E2EE
  
---
## [0.8.1] — 16 August 2026

### Added
- DACx OTA on runtime 1.5.6 (no new APK)
- Home glass header, transparent logo, social footer
- Full-screen QR; accepts `dacx://add/…` and plain xID
- New accounts: on-device Solana key, 12-word display + 3-word confirm
- Wallet DEVNET badge and honest copy

### Changed
- Chat unread / composer / Android back behavior
- PIN: single field, 4–6 digits
- dacx README aligned with live status (no false self-custody, no live voice calls)

### Not shipped
- Phrase restore
- E2EE
- $DAC mainnet in DACx
- Voice calls (remain hidden)

---
## [0.8.0] — August 2026

### Updated
- README.md — ecosystem status table, $DAC status clarified
- ROADMAP.md — $DAC token status vs ecosystem milestones clarified
- PROGRESS.md — full progress update August 2026
- DACx README — source code status added, feature table updated

---
## [0.7.0] — August 2026

### Added
- ARCHITECTURE.md — ecosystem layer documentation
- SECURITY.md — security policy and vulnerability reporting
- TOKENOMICS.md — official $DAC allocation structure v1.0
- START_HERE.md — full onboarding guide with contributor paths

### Updated
- README.md — added ARCHITECTURE, TOKENOMICS, SECURITY to documents
- WHITEPAPER.md — tokenomics section updated, link to TOKENOMICS.md

---

## [0.6.0] — August 2026

### Added
- WHITEPAPER.md v2.0 — full 17-section whitepaper published
- Public Presale section added
- Risk Management section added
- Transparency & Treasury section added
- $DAC Token Lifecycle section added
- Ecosystem Participation section added
- FAQ section added (17 questions)
- DACx updated to v1.5.6 with OTA updates in whitepaper
- Tokenomics updated — 6 allocation categories

---

## [0.5.0] — August 2026

### Added
- DACx v1.5.6 — OTA update system live
- expo-updates production channel enabled
- Automatic JS/UI updates without APK reinstall
- DACx Security & UI Premium OTA update
- PIN Vault — required on every app open
- Privacy cover — app switcher shows only logo
- Auto-lock with configurable timer
- 24 emoji reactions + Delete for both
- Custom SVG icon set
- Avatar colors derived from xID

---

## [0.4.0] — August 2026

### Added
- DACx Beta v1.5.2 — private communication layer launched
- DACx repository: https://github.com/DAC-web3/dacx
- xID identity system — no phone, no email
- Ephemeral messages — 3 min TTL after read
- Solana self-custody wallet bound to xID
- Voice calls (WebRTC) + push notifications (FCM)
- WHITEPAPER.md updated — DACx added as 4th ecosystem layer
- README.md updated — DACx added as fourth pillar

---

## [0.3.0] — May 2026

### Added
- $DAC Token deployed on Solana Mainnet
- Token 2022 Standard — 3B supply, 0.5% auto-burn per transaction
- Contract: `4m9XHiFaZcoUiMxaJH9DbxSXJXuQuXASw3q35hZPjghb`
- README.md fully updated with all pillars, roadmap, documents
- LICENSE added (MIT)
- Topics and website added to repository
- Google Collaboration Form live
- Issue Templates added (Bug Report, Feature Request, Collaboration)
- CONTRIBUTING.md updated

---

## [0.2.0] — May 2026

### Added
- WHITEPAPER.md v1.0 — initial whitepaper
- ROADMAP.md — phased development plan 2026–2030
- GOVERNANCE.md — DAO governance model
- CONTRIBUTING.md — contributor guidelines
- TEAM.md — founding team
- PROGRESS.md — live progress tracking
- VISION.md — core philosophy and vision
- START_HERE.md — initial onboarding document
- Three contribution pillars defined: rutaX, DACmeta, DAC Smart Systems
- Circular $DAC economy model defined

---

## [0.1.0] — May 2026

### Added
- Repository created: DAC-web3/dac-network
- README.md — initial vision and mission
- First 5 Issues opened — community discussions started
- Founder Update #1 published

---

## Roadmap Preview

| Version | Target | Milestone |
|---------|--------|-----------|
| 0.8.0 | 2026 Q3 | rutaX beta launch |
| 0.9.0 | 2026 Q4 | First 1,000 users |
| 1.0.0 | 2027 Q1 | rutaX mainnet + DACmeta beta |
| 2.0.0 | 2028+ | Full DAO governance |

---

*DACnetwork • dacnetwork.io • Whitepaper v2.0 | 2026*
