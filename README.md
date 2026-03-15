# Cryptanu - Smart Contract Security Researcher

## Profile
- Senior Security Researcher, **[QuillAudits](https://www.quillaudits.com/auditors/cryptanu)**
- Block 7 [Fellow](https://x.com/yAuditDAO/status/1935024370931614171?s=20), **YAudit (formerly YAcadamy, electisec)**
- Caught critical bugs in RWA, DeFi, AMM, NFT, Gaming, DAO, Launchpad, L1, Crosschain systems.

## Open-Source Contributions, Disclosures and Articles
2025
- Saved a protocol with $3m TVL by catching a 2 y.o. vulnerability in the wild. [Read here](https://www.linkedin.com/posts/anuoluwapo-adeleke-75a705196_solidity-security-activity-7234483333722775552-f3Tp?)
- Responsible disclosure of medium severity vulnerability in Dinari (an RWA-tokenization protocol) with >$40m TVL. [Dinari Responsible Disclosure](https://gist.github.com/cryptanu/c4ac07f5e602f4c7ef98e9b54091dc1c)
- GMX v2.1 <> v2.2 upgrade breakdown. [What should be fixed, and what isn't?](https://hackmd.io/RIzE1saMSwmVxArscNw0gw)

2026
- Security at the Human Layer [Talk presented at Blockchain UNIBEN Conference 2026](https://github.com/cryptanu/verify/blob/main/Security%20at%20the%20Human%20Layer.pptx.pdf)
- TOCTOU: Upgrading code to near MEV status [Article Link](https://hackmd.io/1iXzq20LSjS2V_U25N8EVw)

## Recent Audits & Notable Projects

### Recent Popular Protocols Audited

| Protocol | Category | Date | Findings (C/H/M) | Report | Status |
|----------|----------|------|------------------|--------|--------|
| HeyElsa | Staking | 2026 | 0/1/4 | [🔓 Report]([https://github.com/Quillhash/QuillAudit_Reports/blob/master/Continuum%20DAO%20Smart%20Contract%20Audit%20report%20-%20QuillAudits.pdf])(https://github.com/Quillhash/QuillAudit_smart_contract_audit_Reports/blob/master/HeyElsa%20V2%20Smart%20Contract%20Audit%20Report%20-%20QuillAudits.pdf)) | ✅ Complete |
| Bean Exchange | GMX Fork | 2025 | 1/1/2 | REDACTED | ✅ Complete |
| ContinuumDAO | RWA, Governance, Multichain | 2025 | 0/21/13 | [🔓 Report](https://github.com/Quillhash/QuillAudit_Reports/blob/master/Continuum%20DAO%20Smart%20Contract%20Audit%20report%20-%20QuillAudits.pdf) | ✅ Complete |
| NexLabs | RWA | 2025 | 0/1/6 | [🔓 Report](https://github.com/Quillhash/QuillAudit_Reports/blob/master/Nex%20labs%20Defi%20Indices%20Audit%20report%20-%20QuillAudits.pdf) | ✅ Complete |
| Taiko | Bridge | 2024 | 0/4/0 | [🔓 Report](https://github.com/Quillhash/QuillAudit_Reports/blob/master/Taiko%20Smart%20Contracts%20Audit%20Report%20-%20QuillAudits.pdf) | ✅ Complete |
| IntoTheVerse | NFT Marketplace | 2024 | 0/6/2 | [🔓 Report](https://github.com/Quillhash/QuillAudit_Reports/blob/master/IntoTheVerse%20Smart%20Contract%20Audit%20Report%20-%20QuillAudits.pdf) | ✅ Complete |

## Summary Statistics

| Category | High | Medium | Low |
|----------|------|--------|-----|
| Private Reviews | 74 | 113 | 132 |
| Public Contests | 1 | 2 | 6 |
| **Total** | **75** | **115** | **138** |

## Interesting Findings & Impact

- **Structural week-ratcheting suppresses intended decay** - Updating the split and merge functionality in Curve's veCTM introduced this critical issue allowing users not lose voting power over the 4 year period at no significant cost. [ContinuumDAO C-5](...)
- **AMM Fee Bypass** - Discovered a flaw in fee calculation allowing users to bypass trading fees, potentially costing the protocol significant revenue. [NexLabs Defi Indices H-1](https://www.quillaudits.com/leaderboard/nex-labs/nex-labs-defi-indices)
- **Cross-chain Bridge Validation Bypass** - Signature replay flaw that could allow unauthorized funds claims. [WChain Bridge H-1](https://www.quillaudits.com/leaderboard/w-chain-bridge)
- **Collateralization Ratio Flaw** - Poor collateral calculation leading to potential under-collateralization. [Aconomy M-5](https://www.quillaudits.com/leaderboard/aconomy)
- **Infinite Mint Vulnerability** - A vulnerability allowing unlimited minting of tokens under specific conditions. [NexLabs Stock Indices M-1](https://www.quillaudits.com/leaderboard/nex-labs/nex-labs-stock-index)

## Reach out here

🐦 **Twitter**: [@cryptanu](https://twitter.com/@cryptanu)  

## Testimonials & Recognition

> "Huge thanks to Anu and Victor for their incredible audit!  Their sharp eyes caught 4 critical high-severity issues(hard to find bugs), and their detailed proofs of concept were eye-opening. This is top-notch work on par with industry leaders like Trail of Bits and ConsenSys. Everyone please join me in a round of applause for our amazing auditors!"

--**Akshay, Technical Project Manager**

<img width="598" height="198" alt="Screenshot 2025-12-10 at 07 55 19" src="https://github.com/user-attachments/assets/a2ca9233-6e49-4b16-8b25-5c66234d41f1" />

--**Selqui, CTO - ContinuumDAO**

---

*Last updated: December 2025*
