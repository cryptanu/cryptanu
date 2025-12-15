# Cryptanu - Smart Contract Security Auditor

## Profile
- Security Researcher, **QuillAudits**
- Block 7 Fellow, **YAudit (formerly YAcadamy, Electisec)**
- Audited 40+ blockchain protocols spanning across RWA, DeFi, AMM, NFT, Gaming, DAO, Launchpad, L1, Crosschain  

## Live Protocol Findings
- Saved a protocol with $3m TVL by catching a 2 y.o. vulnerability in the wild. [Read here](https://www.linkedin.com/posts/anuoluwapo-adeleke-75a705196_solidity-security-activity-7234483333722775552-f3Tp?utm_source=share&utm_medium=member_desktop&rcm=ACoAAC4F2fYBD6ZRHnINz7yz7tkiMN-0yifOAzI)
- Responsible disclosure of medium severity vulnerability in Dinari (an RWA-tokenization protocol) with >$40m TVL. [Dinari Responsible Disclosure](https://gist.github.com/cryptanu/c4ac07f5e602f4c7ef98e9b54091dc1c)

## My Audit Profiles & Links
- **Official audit portfolio**: [QuillAudits Profile](https://quillaudits.com/auditors/cryptanu)
- **Blog/Security insights & updates**: [X](https://x.com/cryptanu)

## Recent Audits & Notable Projects

### Top 5 Popular Protocols Audited

| Protocol | Category | Date | Findings (H/M/L) | Report | Status |
|----------|----------|------|------------------|--------|--------|
| ContinuumDAO | RWA, Governance, Multichain | 2025 | 21/13/24 | [🔓 Report](https://github.com/Quillhash/QuillAudit_Reports/blob/master/Continuum%20DAO%20Smart%20Contract%20Audit%20report%20-%20QuillAudits.pdf) | ✅ Complete |
| NexLabs | RWA | 2025 | 1/6/5 | [🔓 Report](https://github.com/Quillhash/QuillAudit_Reports/blob/master/Nex%20labs%20Defi%20Indices%20Audit%20report%20-%20QuillAudits.pdf) | ✅ Complete |
| Taiko | Bridge | 2024 | 4/0/6 | [🔓 Report](https://github.com/Quillhash/QuillAudit_Reports/blob/master/Taiko%20Smart%20Contracts%20Audit%20Report%20-%20QuillAudits.pdf) | ✅ Complete |
| IntoTheVerse | NFT Marketplace | 2024 | 6/2/4 | [🔓 Report](https://github.com/Quillhash/QuillAudit_Reports/blob/master/IntoTheVerse%20Smart%20Contract%20Audit%20Report%20-%20QuillAudits.pdf) | ✅ Complete |
| Aconomy | Lending | 2024 | 0/7/13 | [🔓 Report](https://github.com/Quillhash/QuillAudit_Reports/blob/master/Aconomy%20Smart%20Contract%20Audit%20Report%20-%20QuillAudits.pdf) | ✅ Complete |

## Summary Statistics

| Category | High | Medium | Low | Total |
|----------|------|--------|-----|-------|
| QuillAudits | 74 | 113 | 132 | 319 |
| Public Contests | 1 | 2 | 6 | 9 |
| **Total** | **75** | **115** | **138** | **328** |

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
