# Security Policy

DACnetwork is committed to responsible security practices.
This document describes how to report vulnerabilities and what to expect.

---

## Scope

This security policy applies to:

- DACnetwork GitHub repositories under https://github.com/DAC-web3
- DACx application (Android Beta)
- DACnetwork backend infrastructure (api.dacnetwork.io)
- $DAC token contract on Solana

This policy does NOT apply to:

- Third-party services or platforms
- Solana blockchain infrastructure itself
- Wallets or external applications

---

## Reporting a Vulnerability

If you discover a security vulnerability, please report it responsibly.

**Do NOT open a public GitHub Issue for security vulnerabilities.**

**Contact us privately at:**
👉 security@dacnetwork.io

Or reach us via X (Twitter): [@DACLabs](https://x.com/DACLabs)

---

## What to Include in Your Report

Please include as much of the following as possible:

- Description of the vulnerability
- Component affected (DACx, rutaX, API, token contract, documentation)
- Steps to reproduce
- Potential impact
- Suggested fix (optional)

---

## What to Expect

| Step | Timeline |
|------|----------|
| Acknowledgement of report | Within 72 hours |
| Initial assessment | Within 7 days |
| Status update | Within 14 days |
| Resolution (if confirmed) | Depends on severity |

---

## Severity Levels

| Level | Description |
|-------|-------------|
| Critical | Direct risk to user funds, private keys or ecosystem infrastructure |
| High | Significant impact on user privacy or data integrity |
| Medium | Limited impact, no immediate risk to users or funds |
| Low | Minor issues, documentation errors, informational findings |

---

## Our Commitments

- We will acknowledge your report promptly
- We will investigate all reported vulnerabilities seriously
- We will not take legal action against researchers acting in good faith
- We will keep you informed of the status of your report
- We will credit researchers who report valid vulnerabilities (if they wish)

---

## Out of Scope

The following are out of scope for this policy:

- Social engineering attacks
- Physical attacks
- Denial of service attacks
- Spam or phishing
- Issues in third-party dependencies outside our control
- Theoretical vulnerabilities without proof of concept

---

## Important Security Reminders

**For users:**
- Never share your PIN, private key or seed phrase with anyone
- Always verify the official $DAC contract address before any transaction
- Official contract: `4m9XHiFaZcoUiMxaJH9DbxSXJXuQuXASw3q35hZPjghb`
- Only download DACx from official sources: www.dacnetwork.io

**For contributors:**
- Never commit private keys, passwords, API secrets or credentials
- Never commit wallet seed phrases or authentication tokens
- If you accidentally expose sensitive information, contact us immediately

---

## Token Security

The $DAC token has the following security properties verified on-chain:

| Property | Status |
|----------|--------|
| Mint Authority | REVOKED — no new tokens possible |
| Freeze Authority | REVOKED — no account freezing possible |
| Total Supply | Fixed at 3,000,000,000 $DAC |
| Verifiable on | https://solscan.io/token/4m9XHiFaZcoUiMxaJH9DbxSXJXuQuXASw3q35hZPjghb |

---

*DACnetwork • Asociația DACnetwork Web3 • București, România*
*dacnetwork.io • security@dacnetwork.io*
