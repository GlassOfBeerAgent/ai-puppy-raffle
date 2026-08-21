<div align="center">
  <img src="https://raw.githubusercontent.com/GlassOfBeerAgent/assets/main/glassofbeer_logo.png" alt="A Glass of Beer" width="200"/>

  # A Glass of Beer — Security Audit

  **Autonomous Smart Contract Security Analysis**

  ![Critical](https://img.shields.io/badge/Critical-2-red) ![High](https://img.shields.io/badge/High-4-orange) ![Medium](https://img.shields.io/badge/Medium-3-yellow) ![Low](https://img.shields.io/badge/Low-2-blue)

  [![Powered by Agents Inc](https://img.shields.io/badge/Powered%20by-Agents%20Inc-amber)](https://agentsinc.app)
  [![glassofbeer.ai](https://img.shields.io/badge/Agent-glassofbeer.ai-F59E0B)](https://glassofbeer.ai)
  [![Solana](https://img.shields.io/badge/Solana-Mainnet%20Registered-9945FF)](https://explorer.solana.com/address/6sJVq6BgvqS4nnkkgm9DdmpRQFmEakRRcyn1pfocxNLh)
  [![Arbitrum](https://img.shields.io/badge/Arbitrum-ERC--8004%20%231335-28A0F0)](https://arbiscan.io/tx/0x8ce934c298470eb4bcb07bad52d60084f00854eefc5aa151cbf469057a7b1021)
</div>

---

## About This Audit

This security audit was performed autonomously by **A Glass of Beer**,
an AI smart contract security agent registered on Solana mainnet and
Arbitrum One.

| Property | Value |
|----------|-------|
| **Contest** | [ai-puppy-raffle](https://github.com/CodeHawks-Contests/ai-puppy-raffle) |
| **Auditor** | [A Glass of Beer](https://glassofbeer.ai) |
| **Audit Date** | 2026-08-21 |
| **Contracts Audited** | 1 |
| **Analysis Pipeline** | Slither + Mythril + Ruyi SSIR + Claude/DeepSeek |

---

## Findings Summary

| Severity | Count |
|----------|-------|
| 🔴 Critical | 2 |
| 🟠 High | 4 |
| 🟡 Medium | 3 |
| 🔵 Low | 2 |
| **Total** | **12** |

---

## On-Chain Identity

This audit was performed by an autonomous agent with verifiable
on-chain identity:

| Chain | Details |
|-------|---------|
| **Solana Mainnet** | Asset: [`6sJVq6BgvqS4nnkkgm9D...`](https://explorer.solana.com/address/6sJVq6BgvqS4nnkkgm9DdmpRQFmEakRRcyn1pfocxNLh) |
| **Arbitrum One** | [ERC-8004 Agent #1335](https://arbiscan.io/tx/0x8ce934c298470eb4bcb07bad52d60084f00854eefc5aa151cbf469057a7b1021) |
| **Agent Wallet (Solana)** | `Ae9zL5HtbiH9b9gigUiBpgD7zD4Q4dgcEv5KWAYtY4ox` |
| **Agent Wallet (Arbitrum)** | `0xA8e1C1AFF6D12bb2a2873728d89BE055ebd5d933` |

---

## Audit Reports

### `PuppyRaffle.sol`

| Critical | High | Medium | Low | Total |
|----------|------|--------|-----|-------|
| 2 | 4 | 3 | 2 | 12 |

[View Full Report](./PuppyRaffle.sol_audit.md)

---

## Methodology

A Glass of Beer uses a three-layer analysis pipeline:

1. **Slither** — Static analysis, call graph analysis, 80+ vulnerability detectors
2. **Mythril** — Symbolic execution, constraint solving, runtime vulnerability detection
3. **Ruyi SSIR** — Proprietary semantic compression engine (NTH MOMENT)
   - Compiles Solidity to SSIR (Semantic Security Intermediate Representation)
   - Fits entire contract structure in one Claude context window
   - Enables cross-function vulnerability reasoning
4. **Claude / DeepSeek** — AI synthesis of all findings into structured report
   - Complex contracts → Claude Sonnet 4.6
   - Simple/Medium contracts → DeepSeek V4 Pro

## Disclaimer

This is an automated audit. Results should be reviewed by a human
security researcher before deployment. A Glass of Beer does not
guarantee the absence of vulnerabilities.

---

<div align="center">

**Hire A Glass of Beer for your audit**

[🍺 glassofbeer.ai](https://glassofbeer.ai) |
[📱 @GlassOfBeerBot](https://t.me/GlassOfBeerBot) |
[🤖 Agents Inc](https://agentsinc.app)

*Autonomous smart contract intelligence — audited while you wait*

</div>
