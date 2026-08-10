# 0xvd

> Smart contract security researcher. I find the bug before it finds the treasury.

Independent researcher working across audit competitions, private engagements, and live bug bounty programs. I focus on the structural soundness of DeFi — accounting math, oracle integrity, share-token mechanics, lending invariants, and the cross-contract interactions that turn a benign-looking write into a ledger break. Most of my time goes into protocols where mistakes are measured in eight or nine figures.

---

## Receipts

- **$400M+** in live exploits prevented across 3 production protocols
- Immunefi **#1** *(last 90d)* · **#2** *(2026)* · **#22** *(all-time)* · HackenProof **#36**
- **31 Immunefi · 18 Code4rena · 17 HackenProof · 15 Sherlock · 7 CodeHawks · 5+ Hats** valid findings — weighted toward Critical, High, and Medium severity
- **1× gold, 1× silver, 1× bronze, 12× top-10** finishes in competitive audits
- Bounties paid by top-tier L1s, L2s, liquid staking and restaking protocols, lending markets, oracle networks, AMMs, bridges, cross-chain messaging layers, Bitcoin staking and payments infra, and DeFi infra
- Active across EVM, Move, Cadence, Solana, and Cosmos-SDK ecosystems

## Recent Bug Bounty Disclosures *(since September 2025)*

**4× Critical · 4× High · 13× Medium · 10× Low** — 31 disclosures across 25 protocols and 5 platforms.

| Date | Platform | Protocol / Class | Severity |
|------|----------|------------------|----------|
| Jul 2026 | Immunefi | Metaverse / NFT platform | Low |
| Jul 2026 | Immunefi | Omnichain messaging | Critical |
| Jul 2026 | Immunefi | Bitcoin / Lightning payments | Low |
| Jun 2026 | Immunefi | Bitcoin staking | Low |
| Jun 2026 | Immunefi | Oracle network | Medium |
| Jun 2026 | Immunefi | Bitcoin / Lightning payments | High |
| Jun 2026 | Immunefi | Layer 1 (Cosmos-SDK) | Medium |
| May 2026 | Immunefi | Cross-chain messaging | Medium |
| May 2026 | HackenProof | Modular DA layer | Low |
| May 2026 | Sherlock | Tokenized RWA | Low |
| Apr 2026 | HackenProof | Cross-chain intents | Medium |
| Apr 2026 | Immunefi | Layer 2 / scaling | Critical |
| Mar 2026 | Immunefi | Lido | Medium |
| Mar 2026 | Immunefi | Layer 1 (Cosmos-SDK) | High |
| Mar 2026 | HackerOne | Layer 1 (non-EVM) | Low |
| Mar 2026 | Immunefi | Beanstalk | Medium |
| Mar 2026 | Code4rena | Glow Finance | Critical |
| Mar 2026 | Code4rena | Glow Finance | Low |
| Mar 2026 | Code4rena | Glow Finance | Low |
| Feb 2026 | Code4rena | Intuition | Medium |
| Feb 2026 | Sherlock | Liquid restaking | Medium |
| Jan 2026 | HackenProof | Layer 1 (Move) | High |
| Dec 2025 | HackenProof | Layer 1 (gaming-focused) | Medium |
| Nov 2025 | Code4rena | Rujira | Medium |
| Nov 2025 | Code4rena | Rujira | Low |
| Nov 2025 | Immunefi | Serai | Medium |
| Nov 2025 | Immunefi | Serai | Low |
| Nov 2025 | Code4rena | Rujira | Critical |
| Nov 2025 | HackenProof | DEX aggregator | High |
| Oct 2025 | HackenProof | Dexlyn | Medium |
| Oct 2025 | HackenProof | Cross-chain bridge | Medium |

### Selected Public Disclosures

- [BOW Swap Pays Arbitrary Caller-Specified Denom Allowing Liquidity Theft](https://github.com/code-423n4/rujira-bug-bounty/issues/3) — **Rujira** · Critical · sponsor confirmed
- [transfer_deposit Allows Collateral Withdrawal Without Health Check, Enabling Immediate Under-Collateralization](https://github.com/code-423n4/glow-finance-bug-bounty/issues/28) — **Glow Finance** · Critical · sponsor confirmed
- [AtomWallet ERC-4337 userOp.callData Prefixing Breaks EntryPoint Execution (AA DoS)](https://github.com/code-423n4/intuition-bug-bounty/issues/34) — **Intuition** · Medium
- [Rewarder Emissions On Pool Assets Drain LP Liquidity](https://hackenproof.com/reports/DEXLYNCA-102) — **Dexlyn** · Medium · HackenProof
- [Deny-Withdrawals Bypass via transfer_deposit Allows Unauthorized Redemption](https://github.com/code-423n4/glow-finance-bug-bounty/issues/5) — **Glow Finance** · Low · sponsor confirmed
- [Fee Withdrawal Leaves Pool Accounting Unchanged](https://github.com/code-423n4/glow-finance-bug-bounty/issues/22) — **Glow Finance** · Low · sponsor confirmed

## Focus

- **Languages.** Solidity, Yul, Move (Sui). Cross-ecosystem bounty work on Cadence and Cosmos-SDK chains.
- **Protocol classes.** Lending and money markets, AMMs and concentrated-liquidity DEXes, liquid staking and restaking, oracle systems, vaults and yield strategies, cross-chain bridges, RWA and stablecoin issuance.
- **Where I tend to find bugs.** Rounding and precision drift, stale state in conditional writes, share-inflation and donation surfaces, oracle staleness and decimal mismatches, role-boundary violations, accounting invariant breaks under flash-loan and boundary conditions.

## How I Work

- **Adversarial-first.** Every state change is a hypothesis until I've traced who can reach it and what it costs to push past intended bounds.
- **Boundary-obsessed.** Zero-state, max-state, first-depositor, last-withdrawer, and dust-amount paths get more attention than the happy path.
- **Mechanical proof, not vibes.** Findings ship with PoCs or concrete numerical traces. If I can't make it break in a test, I don't claim it does.

---

## Profiles

[![Immunefi](https://img.shields.io/badge/Immunefi-vivekd-FF3D3D?style=for-the-badge)](https://immunefi.com/profile/vivekd)
[![Sherlock](https://img.shields.io/badge/Sherlock-vivekd-1D5BFF?style=for-the-badge)](https://audits.sherlock.xyz/watson/vivekd)
[![Code4rena](https://img.shields.io/badge/Code4rena-0xvd-9146FF?style=for-the-badge)](https://code4rena.com/@0xvd)
[![Cyfrin](https://img.shields.io/badge/Cyfrin-0xvd-00C853?style=for-the-badge)](https://profiles.cyfrin.io/u/0xvd)
[![HackenProof](https://img.shields.io/badge/HackenProof-0xvivekd-FF6A00?style=for-the-badge)](https://hackenproof.com/hackers/0xvivekd)
[![X](https://img.shields.io/badge/X-@0xvivekd-000000?style=for-the-badge)](https://x.com/0xvivekd)

## Currently

Open to audit collaborations and retainer work. Especially keen on protocols pushing complex accounting, novel AMM curves, cross-chain messaging primitives, or anything where a single character can own the treasury.

DMs open on X — [@0xvivekd](https://x.com/0xvivekd).

