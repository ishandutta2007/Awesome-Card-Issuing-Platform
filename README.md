# Awesome Card Issuing Platform 💳🚀

![Awesome Card Issuing Platform Banner](assets/banner.svg)

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a><a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <img src="https://img.shields.io/github/last-commit/ishandutta2007/Awesome-Card-Issuing-Platform?style=flat-square" alt="Last Commit"/>
  <img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Card-Issuing-Platform?style=flat-square" alt="Stars"/>
  <img src="https://img.shields.io/github/license/ishandutta2007/Awesome-Card-Issuing-Platform?style=flat-square" alt="License"/>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

## 🌐 Top Card Issuing Platforms & Core Banking Ecosystem 📊

**Curated List of SaaS Products & Open-Source GitHub Projects for Programmable Card Issuance, Ledger Infrastructure, Spend Controls & Embedded Finance** 💳✨

*Last updated: September 2026*

This repository tracks notable **SaaS platforms** and **open-source projects** for **Card Issuing**, **programmable payments**, and **embedded finance**. These tools help fintechs, enterprise platforms, neobanks, and startups launch physical and virtual card programs—debit, credit, prepaid, fleet, and expense cards—without building card network connectivity or BIN sponsorship from scratch. 🛠️

**Key SaaS Category Leaders:** Marqeta, Lithic, Highnote, Galileo (SoFi Tech Solutions), Bond, Stripe Issuing, Adyen Issuing, Solaris, Episode Six, and Wallester.

**💡 Open-Source Reality & Architecture:** Card issuing is one of the **most commercially consolidated** sectors in fintech infrastructure. **No production-ready open-source card issuing platform exists** that provides real card network connectivity (Visa/Mastercard/Amex), BIN sponsorship, and compliance management out-of-the-box. The practical open-source strategy involves combining **core banking ledgers** (Apache Fineract, Open Source Bank, Moov Financial, Form3) with **payment switches** (jPOS) and custom card management services.

---

## 📑 Table of Contents
- [🏢 SaaS / Hosted Platforms](#-saas--hosted-platforms)
- [💻 Open-Source GitHub Projects](#-open-source-github-projects)
- [📊 Market Overview & Industry Insights](#-market-overview--industry-insights)
- [🤝 How to Contribute](#-how-to-contribute)
- [⚠️ Disclaimer](#️-disclaimer)
- [💖 Support](#-support)
- [📈 Star History](#-star-history)

---

## 🏢 SaaS / Hosted Platforms

> [!NOTE]
> **Market Size & Fragmentation:** The global card issuing and processing market size is estimated at **$32.5 Billion** and is projected to reach **$68.4 Billion by 2030**. The market is **moderately fragmented**, with dominant enterprise incumbents (Marqeta, Galileo, Adyen) powering high-volume consumer and commercial programs, alongside agile developer-first platforms (Lithic, Highnote) capturing fast-growing B2B expense and fintech niches.

The table below is sorted by **Company Size / Valuation (Descending)**:

| Platform / Company | Estimated Size / Valuation | Starting Tier Pricing | Free Tier / Trial Limits | Key Features & Program Strengths |
| :--- | :--- | :--- | :--- | :--- |
| **[Adyen Issuing](https://www.adyen.com/issuing)** 💳 | **~$48 Billion** market cap | $0.10 + Interchange++ per card transaction | 30-day sandbox trial with test API credentials | Unified acquiring & issuing platform; zero balance transfer delays; physical/virtual card controls. |
| **[Stripe Issuing](https://stripe.com/issuing)** ⚡ | **~$70 Billion** valuation | $0.10 per virtual card / $3.00 per physical card + $0.20 per transaction | $0 setup fee; free test mode with unlimited test API calls | Programmatic API spend controls, real-time webhooks, instant virtual provisioning, Stripe Treasury pairing. |
| **[Galileo (SoFi Tech Solutions)](https://www.galileo-ft.com/)** 🏛️ | **~$12 Billion** market cap (SoFi) | $5,000/month platform base fee | Sandbox demo environment with 90-day test API key | Enterprise scale, powers millions of accounts across Americas, fraud engines, Javelin 2025 top provider. |
| **[Marqeta](https://www.marqeta.com/)** 🚀 | **~$2.5 Billion** market cap | $2,500/month minimum platform fee | Sandbox environment with $1,000 simulated balance limit | Pioneer of Just-in-Time (JIT) funding, tokenization, digital wallet provisioning, custom webhooks. |
| **[Solaris](https://www.solarisgroup.com/)** 🏦 | **~$1.6 Billion** valuation | €3,000/month platform fee | 14-day staging sandbox access upon sales qualification | German banking license, turnkey compliance, SEPA integration, physical & tokenized credit/debit cards. |
| **[Lithic](https://www.lithic.com/)** 🛠️ | **~$800 Million** valuation | $0.10 per transaction (End-to-End tier) | $0/mo Free Developer Tier: Up to 750 transactions/mo & 20 active cards | Developer-first API, single-use virtual cards, Processing vs Program Managed models, transparent pricing. |
| **[Highnote](https://highnote.com/)** 📈 | **~$500 Million** valuation | $1,500/month base platform fee | Developer sandbox access with 60-day test token validity | GraphQL API, real-time programmable ledger, B2B virtual cards for travel/fleet, embedded credit/debit. |
| **[Episode Six](https://episodesix.com/)** 🌐 | **~$300 Million** valuation | $3,500/month base fee | Sandbox trial with test ledger setup (by request) | Enterprise ledger & payment switch engine, cooperative authorization model, stablecoin & multi-asset support. |
| **[Wallester](https://wallester.com/)** 🇪🇺 | **~$150 Million** valuation | €0/month Starter Plan (€0.35 per active card/mo) | Free Starter Plan: Up to 300 free virtual cards & 14-day trial | EU Visa principal licensee, ERP/SaaS REST API, instant corporate expense cards, fast GTM (< 30 days). |
| **[Bond](https://www.bond.tech/)** 🔗 | **~$100 Million** valuation | $1,000/month starter tier | Developer sandbox mode with 30-day API test keys | Universal Cards API, embedded consumer charge card underwriting, Apple/Google Pay provisioning. |

---

## 💻 Open-Source GitHub Projects

The following open-source repositories provide the essential **core banking ledgers**, **payment messaging switches**, and **account management engines** required to build custom card infrastructure.

Repositories are sorted by **GitHub Stars_Count (Descending)** ⭐:

| Project & Repo Link | Stars_Count | License | Architecture & Core Capabilities |
| :--- | :--- | :--- | :--- |
| **[Apache Fineract](https://github.com/apache/fineract)** 🏛️ | [![Stars](https://img.shields.io/github/stars/apache/fineract?style=social&color=white)](https://github.com/apache/fineract/stargazers) | Apache-2.0 | Enterprise core banking backend, multi-currency ledger, deposit/savings management, portfolio engine. |
| **[Mifos X](https://github.com/openMF/mifos-x)** 🌐 | [![Stars](https://img.shields.io/github/stars/openMF/mifos-x?style=social&color=white)](https://github.com/openMF/mifos-x/stargazers) | MPL-2.0 | Digital Public Good core banking suite built on Apache Fineract with admin web UI & field apps. |
| **[Moov Financial Services](https://github.com/moov-io/paygate)** ⚡ | [![Stars](https://img.shields.io/github/stars/moov-io/paygate?style=social&color=white)](https://github.com/moov-io/paygate/stargazers) | Apache-2.0 | Go-based open-source ACH payment gateway, bank rail integration, real-time transaction processing. |
| **[jPOS](https://github.com/jpos/jPOS)** 💳 | [![Stars](https://img.shields.io/github/stars/jpos/jPOS?style=social&color=white)](https://github.com/jpos/jPOS/stargazers) | AGPL-3.0 | Java ISO 8583 payment messaging switch, financial transaction gateway for merchant & card networks. |
| **[Form3 Open Banking Engine](https://github.com/form3tech-oss/interview-accountapi)** 🛠️ | [![Stars](https://img.shields.io/github/stars/form3tech-oss/interview-accountapi?style=social&color=white)](https://github.com/form3tech-oss/interview-accountapi/stargazers) | MIT | RESTful account management engine, double-entry balance validation, payment account REST API. |
| **[Open Source Bank](https://github.com/ishanperera/opensourcebank)** 🏦 | [![Stars](https://img.shields.io/github/stars/ishanperera/opensourcebank?style=social&color=white)](https://github.com/ishanperera/opensourcebank/stargazers) | MIT | API-first core banking engine with double-entry ledger, FastAPI + Next.js, Plaid/Stripe test sandbox. |
| **[FinAegis Core Banking Prototype](https://github.com/FinAegis/core-banking-prototype-laravel)** 🔧 | [![Stars](https://img.shields.io/github/stars/FinAegis/core-banking-prototype-laravel?style=social&color=white)](https://github.com/FinAegis/core-banking-prototype-laravel/stargazers) | MIT | Modular Laravel domain-driven banking prototype with event sourcing via Redis Streams & multi-asset accounts. |

---

## 📊 Market Overview & Industry Insights

Building a programmable card program requires understanding the three core pillars of payment stack architecture:

```
┌─────────────────────────┐       ┌─────────────────────────┐       ┌─────────────────────────┐
│   Core Ledger Engine    │  ◄──► │  Card Management / API  │  ◄──► │ Card Network / Sponsor  │
│ (Fineract / Custom DB)  │       │ (Marqeta / Lithic / JIT)│       │  (Visa / Mastercard)    │
└─────────────────────────┘       └─────────────────────────┘       └─────────────────────────┘
```

1. **BIN Sponsorship & Compliance**: Regulated banks supply the Bank Identification Number (BIN) and handle regulatory compliance (KYC, AML, BSA).
2. **Card Processing & Switch**: Translates Visa/Mastercard ISO 8583 messages into API webhooks for real-time auth decisions (Just-In-Time funding).
3. **Double-Entry Ledger**: Tracks user balances, authorization holds, clearing settlements, and interchange fees.

---

## 🤝 How to Contribute

Contributions are warmly welcomed! 💖

1. Fork the repository.
2. Add/edit entries in `README.md` following the standard table schema.
3. Ensure all descriptions are factual, pricing details are verified, and links point to official sources.
4. Open a Pull Request with a clear summary of changes.

---

## ⚠️ Disclaimer

- This repository is a **community-curated informational resource** — not financial advice or commercial endorsement.
- Card issuing involves strict legal and technical compliance including **PCI DSS**, **KYC/AML**, and network rules.
- **Open-source notice**: Open-source projects cover ledger engines and payment switches, but **do not provide direct network connectivity to Visa/Mastercard or BIN sponsorship out of the box**.

---

## 💖 Support & Community

If you find this repository helpful for your fintech research, project, or company:

- ⭐ **Star this repository** on GitHub to show support!
- 🔀 **Fork it** to customize or contribute back.
- 📢 **Share it** with fellow fintech engineers, architects, and product builders!
- ☕ **Buy me a coffee / Sponsor**: Support ongoing updates via [GitHub Sponsors](https://github.com/sponsors/ishandutta2007).

---

## 📈 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Card-Issuing-Platform&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Card-Issuing-Platform&type=date&legend=top-left)

---

<p align="center">
  <i>Built with ❤️ for fintech builders, embedded finance developers, product managers, and platform architects.</i>
</p>
