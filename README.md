# Hi, I'm Vivek Khudaniya 👋

**Senior Smart Contract Developer · Cross-Chain DeFi Architect · Security Auditor**

> Building production-grade DeFi infrastructure with zero security incidents. 5+ years specialising in EVM smart contracts, cross-chain systems, and institutional-grade yield products.

---

## 🏠 About Me

I'm a Senior Smart Contract Developer at **Aarna Protocol** (Singapore), working remotely from Gurgaon, India. I architect and deploy complex DeFi systems across Ethereum, Base, Arbitrum, and HyperEVM — from cross-chain vault infrastructure to ERC-3643 compliant RWA tokens.

- 🔭 Currently building **ICT (India Credit Token)** — a regulated ERC-3643 security token on GIFT City infrastructure backed by SEBI Category II AIFs
- 🛡️ Proven security auditor — reviewed LayerZero v2 OFT composer contracts, identified critical vulnerabilities in production
- ⚡ 12+ core smart contracts deployed on mainnet with **zero security incidents**
- 🌐 Open to remote roles worldwide

---

## 🛠️ Technical Skills

**Smart Contracts**
`Solidity` `ERC-4626 Vaults` `ERC-3643 T-REX` `ERC-20/721` `UUPS Proxy` `Diamond Proxy` `OpenZeppelin` `Gas Optimization`

**Cross-Chain**
`LayerZero v2` `OFT / OApp / lzCompose` `Stargate v2` `Cross-Chain Message Composition` `Fee Quoting`

**DeFi Protocols**
`Aave v3` `Morpho Blue` `Pendle (PT/YT/LP)` `Uniswap V3` `1inch` `Compound` `Curve` `Hyperliquid Perps`

**Security**
`Smart Contract Auditing` `Foundry Fuzz/Invariant Testing` `Slither Static Analysis` `Manual Vulnerability Review` `Security Report Writing`

**Tooling & Infrastructure**
`Foundry` `Hardhat` `Tenderly` `Chainlink Oracles` `The Graph` `Node.js` `TypeScript` `Docker` `AWS`

**Chains**
`Ethereum` `Base` `Arbitrum` `Optimism` `HyperEVM` `Polygon` `Solana`

---

## 💼 Professional Experience

### Senior Smart Contract Developer — Aarna Protocol *(May 2022 – Present)*
*Remote · Singapore*

- **Cross-Chain Vault System** — Architected hub-spoke vault infrastructure using LayerZero v2 + Stargate, enabling atomic deposits from Base/Optimism into Ethereum ERC-4626 vaults in single transactions
- **ERC-3643 T-REX KYC Integration** — Integrated permissioned token standard with 5 KYC enforcement gates; built dual-mode IdentityRegistry (Simple whitelist + Full T-REX with on-chain claim verification)
- **Multi-Protocol Yield Engine** — Integrated 7 DeFi protocols (Aave, Compound, Morpho Blue, Pendle, Uniswap V3, 1inch, Curve) into unified yield optimization engine
- **Gas Optimization** — Reduced gas consumption by 45% via storage packing, assembly-level optimizations across 50K+ transactions
- **Leverage Bundler** — Built modular leverage vault using PT-USDC as Morpho Blue collateral, generating dual yield across 16 strategy combinations with atomic deleverage
- **Security Auditing** — Comprehensive review of LayerZero v2 OFT composer contracts; identified reentrancy vectors, access control issues, and cross-chain messaging vulnerabilities

### Full Stack Blockchain Developer — RevInfotech *(Nov 2020 – Apr 2022)*
*Remote · India*

- Deployed 3 production DeFi protocols (AMM, staking, yield farming) with 95% test coverage
- Built NFT marketplace with lazy minting, reducing gas costs by 60%
- Engineered React Native crypto wallet with biometric auth + Ledger hardware support (4.5★)

---

## 🚀 Key Projects

### Cross-Chain Vault Infrastructure (LayerZero v2 + Stargate)
Built `VaultComposerStargate`, `ShareOFTAdapter`, and Asset OFT contracts enabling any-chain deposits into hub ERC-4626 vaults. Handles lzCompose callbacks, 6→18 decimal conversion, multi-hop bridging, and mainnet fee edge cases.

### Delta-Neutral HYPE Vault (HyperEVM)
Designed 11-contract delta-neutral system: `DeltaNeutralVault`, `PositionManager`, `NAVCalculator`, `CircuitBreaker`, `HyperliquidAdapter`, `DEXAdapter`. Solved cross-chain NAV calculation between HyperEVM spot and Hypercore perp using oracle bridge feeds.

### VulnHound — AI-Powered Smart Contract Auditing Agent
9-section architecture with 7-stage pipeline combining Slither static analysis with AI-driven vulnerability pattern recognition. Designed to surface real vulnerabilities and filter false positives at scale.

### ERC-3643 T-REX Integration (AtvPtMax)
First production integration of full T-REX permissioned token standard into an ERC-4626 vault. Dual-mode IdentityRegistry, ONCHAINID support, and cross-chain KYC bridging via LayerZero.

---

## 📍 Deployed Contracts (Mainnet)

### Ethereum
| Contract | Address |
|----------|---------|
| âtvPTmax | [0xb9C1344...F2AE8](https://etherscan.io/address/0xb9c1344105faa4681bc7ffd68c5c526da61f2ae8) |
| pendleAdapter | [0x45afBaC...2dff](https://etherscan.io/address/0x45afBaC8be713d5F7cB42A7b1e6D034A681a2dff) |
| âtvUSDC | [0xF30F629...0EA9](https://etherscan.io/address/0xF30F62963CCE132F32306d7F18a8587958b30EA9) |
| âtv Factory | [0x3E20112...5d1](https://etherscan.io/address/0x3E20112aE272b8Af63477452c127Ad9A452CD5d1) |
| âtv Manager | [0xCfff0e2...fEc](https://etherscan.io/address/0xCfff0e29cD34c60B6Eb02b022AB45AB1D571DfEc) |
| âtv Oracle | [0x6936df2...6Dd](https://etherscan.io/address/0x6936df2D345605b3aF42b880660B9717F2ae66Dd) |
| âtv Storage | [0xCeb202D...8ad](https://etherscan.io/address/0xCeb202D3075bE4abD24865fD8F307374923948ad) |
| âtv TimeDelay | [0xE56E418...F24](https://etherscan.io/address/0xE56E418ad7FC784011b93360A4b4A84211d22F24) |

### Base
| Contract | Address |
|----------|---------|
| âtvBTC | [0x9dC3F0f...1166](https://basescan.org/address/0x9dC3F0f25d793bee5eec75Da3058b0c919F71166) |
| âtvUSDC | [0x748d974...9F63](https://basescan.org/address/0x748d974d8c1d380da29DB16d0840788949b99F63) |
| âtv LeverageBundler | [0xFaC8b52...95D](https://basescan.org/address/0xFaC8b52EbD53863222FddCD8e8Af30c1915b095D) |
| âtv MorphoBlue Integration | [0x3c29EFF...9d8](https://basescan.org/address/0x3c29EFF521e6F8F8488Eb9DFe7c81386D83db9d8) |
| âtv Factory | [0x053136b...Ad4](https://basescan.org/address/0x053136b9a3826e72e6B8b692fD607ea8CD72BAd4) |
| âtv Manager | [0xD3327F5...963](https://basescan.org/address/0xD3327F5102f59E57F34ee136D3Be0b80d7BB2963) |
| âtv Oracle | [0xEf3CEbF...602](https://basescan.org/address/0xEf3CEbF4F1539D02Ec58fc5525ac791E015f6602) |
| âtv Storage | [0x6469D15...318](https://basescan.org/address/0x6469D15333e7d6a8bDad18a18c251706570bc318) |

---

## 🎓 Education & Certifications

**B.Tech. Computer Science** — Chandigarh University *(2016–2020)*

- ✅ Certified Ethereum Developer (Ethereum Masterclass)
- ✅ Smart Contract Security Auditor (Secureum)
- ✅ DeFi Integration Specialist

---

## 📊 GitHub Stats

![Vivek's GitHub Stats](https://github-readme-stats.vercel.app/api?username=Vivekkhudaniya&show_icons=true&theme=dark&hide_border=true&count_private=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Vivekkhudaniya&layout=compact&theme=dark&hide_border=true)

---

## 📫 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Vivek%20Khudaniya-blue?style=flat&logo=linkedin)](https://linkedin.com/in/vivekkhudaniya)
[![Twitter/X](https://img.shields.io/badge/X-@Vivek__khudaniya-black?style=flat&logo=x)](https://x.com/Vivek_khudaniya)
[![Email](https://img.shields.io/badge/Email-vivekkhudaniya@gmail.com-red?style=flat&logo=gmail)](mailto:vivekkhudaniya@gmail.com)

---

*Open to remote opportunities worldwide — DeFi protocols, security audit firms, cross-chain infrastructure teams.*
