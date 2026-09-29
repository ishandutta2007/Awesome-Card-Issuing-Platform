# Awesome-Card-Issuing-Platform

# Top Card Issuing Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Programmable Card Issuance, Ledger Infrastructure, Spend Controls & Embedded Finance*
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Card Issuing**. These tools help fintechs, enterprises, and platforms launch and manage physical and virtual card programs—debit, credit, prepaid, and fleet—without building card network connectivity or bank sponsorship from scratch.

**Examples** include Marqeta, Lithic, Highnote, Galileo (SoFi Tech Solutions), Bond, Stripe Issuing, Adyen Issuing, Solaris, Episode Six, and Wallester (the category leaders).

**Open-source emphasis**: Card issuing is one of the **most commercially consolidated** categories in fintech infrastructure. **No production-ready open-source card issuing platform exists** that provides real card network connectivity, BIN sponsorship, and compliance management out of the box. The practical open-source path involves building on **core banking ledgers** (Apache Fineract, Open Source Bank) combined with **payment switch software** and **custom card management systems**. This section documents these foundations honestly, including the significant regulatory and integration work required.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Marqeta](https://www.marqeta.com/)**
  The incumbent in programmable card issuing. Powers Square's debit card, DoorDash driver cards, Instacart payments, and many enterprise programs. Deeply customizable: every rule, authorization stream, and funding feed can be configured per program. Just-in-time funding, tokenization, and digital wallet provisioning are production-grade. **Tradeoff**: complexity—expects a compliance team, dedicated integration engineer, and volume justifying onboarding investment. Pricing is custom and minimum-commit-based .

- **[Lithic](https://www.lithic.com/)**
  Developer-first issuing platform (formerly Privacy.com's B2B spin-out). Clean, well-versioned API documented like it was written by engineers for engineers. **Single-use virtual cards are a first-class primitive**, ideal for expense management and SaaS subscription control. Offers **Processing** (you own the program, bring your own bank) and **Program Managed** (Lithic handles compliance, bank sponsorship, and ledgering) models. Coverage: US and Canada. Per-card and per-authorization pricing with no monthly minimum .

- **[Highnote](https://highnote.com/)**
  Unified platform for embedded finance built for both card issuance and acquiring, including credit and real-time money movement. Core features include a **real-time programmable ledger**, integrated payments, and complete program management. Uses a **GraphQL API** with a no-code dashboard built on top. Supports debit, credit, prepaid, fleet, and virtual cards. Recently expanded commercial card issuing for online travel agencies with single-use virtual cards tied to bookings and wholesale travel BIN access .

- **[Galileo (SoFi Tech Solutions)](https://www.galileo-ft.com/)**
  SoFi's technology platform (rebranding to SoFi Tech Solutions), powering banks, fintechs, and brands for over two decades. Currently supporting millions of enabled accounts across North and Latin America. Earned top spot in Javelin Strategy & Research's **2025 Digital Issuance Provider Scorecard**. Flexible, secure, API-based platform handling card issuance, real-time transactions, fraud prevention, and embedded payment capabilities. Joined AWS Partner Network to expand access .

- **[Bond](https://www.bond.tech/)**
  Provides physical and virtual cards via a universal Cards API. Issue debit, prepaid, secured charge, or credit cards. **Instant issuance**—virtual cards in minutes, physical cards within days through a single API call. Bank partnerships with Mastercard, provisioning into Apple Pay, Google Pay, Samsung Pay. **Bond handles program management and underwriting** for consumer charge card programs, including KYC and credit decisioning .

- **[Stripe Issuing](https://stripe.com/issuing)**
  Create, manage, and scale a payment card program without setup fees. Programmatic control over physical or virtual cards, spending controls, and real-time transaction approvals/declines. Partners with multiple trusted banks and Mastercard/Visa. Available in US, UK, and many EEA countries; stablecoin-backed programs in 30+ countries. Can integrate with **Stripe Treasury for platforms** to attach cards to fiat or stablecoin wallets. Webhooks for real-time authorization control .

- **[Adyen Issuing](https://www.adyen.com/issuing)**
  Complete card issuing solution within Adyen's unified payments platform. **Unique advantage**: bridge acquiring and issuing so funds flow seamlessly, reducing cash tied up in transit. Advanced API for physical/virtual issuance, adjustable card controls, real-time authorization, customizable branding. Transparent Interchange++ pricing model. Currently available for selected businesses in Europe, UK, and US. Use cases include expense management, benefits programs, and platform cards .

- **[Solaris](https://www.solarisgroup.com/)**
  German licensed bank offering fully branded cards backed by its own banking license. Supports prepaid, debit, and credit (charge or revolving) cards—physical, virtual, or tokenized. **Solaris handles regulated infrastructure and compliance** while you keep control of UX, data, and insights. Powers ADAC's 1.3 million credit card portfolio. Configurable card rules by merchant category, country, or payment method. In-app cardholder controls (freeze, limits, foreign transaction blocks) .

- **[Episode Six](https://episodesix.com/)**
  Enterprise-grade card issuing and **ledger infrastructure**. Provides modular architecture for card programs, with a **cooperative authorization model** allowing clients to retain control of their ledger while using Episode Six's processing capabilities. Selected by ZEN.COM for European and Asian expansion, chosen for strong Asia presence and rapid go-to-market timelines. Partnership with Fireblocks enables unified traditional and digital asset payments including stablecoin-backed programs .

- **[Wallester](https://wallester.com/)**
  Licensed, developer-first card issuing infrastructure operating under its own EU-issued Visa license. RESTful API for card creation, transaction monitoring, and spend controls. **ERP/SaaS integration focus**: embed card issuing in a few API calls, with virtual cards for expense control, supplier payments, and client wallet systems. Handles AML/KYC and reporting—you don't need to become a regulated financial institution. Launch in under 30 days with sandbox testing and dedicated integration support .

## Open-Source GitHub Projects

- **[Apache Fineract](https://github.com/apache/fineract)**
  Open-source core banking system designed for digital financial services. Provides the **ledger and account infrastructure** on which card programs can be built. Version 1.11.0 (March 2025) includes lending, savings, deposits, and client management. Supports multi-currency, interest calculations, and financial reporting. Used by Mifos X and financial inclusion organizations worldwide. **Apache-2.0**. **Not a card issuing platform**—requires payment switch integration and card management layer .

- **[Open Source Bank](https://github.com/ishanperera/opensourcebank)**
  API-first core banking engine with a **double-entry ledger**, transaction processing, and compliance tooling. Explicitly designed so developers can build financial products on top. Features idempotent transactions, JWT + API keys auth, RBAC, PII encryption, audit logging, fraud detection engine, Plaid sandbox, and Stripe test mode integration. Python FastAPI + Next.js, PostgreSQL, Docker Compose deployment. **Open source**.

- **[Mifos X](https://github.com/openMF/mifos-x)**
  Digital Public Good recognized by the Digital Public Goods Alliance. Full core banking suite including Fineract backend, web UI, reporting plugin, mobile field operations app (Kotlin), and customer mobile banking app. Used by financial inclusion organizations worldwide. **Mozilla Public License**. **Not a card issuing platform**—provides the ledger foundation.

- **[FinAegis Core Banking Prototype](https://github.com/FinAegis/core-banking-prototype-laravel)**
  Laravel-based core banking prototype with **modular domain architecture**. Install only needed domains: `php artisan domain:install lending` or `php artisan domain:install card-issuing` (if available). Features event sourcing with Redis Streams, multi-asset accounts, governance, and compliance domains. PHP 8.4+, PostgreSQL, Redis. Demo mode runs without external dependencies. **Open source**. Card issuing domain availability uncertain—verify repository.

- **[Open Payments Platform](https://github.com/open-payments)**
  Open-source payment platform efforts. The **Open Payments** ecosystem includes specifications and implementations for payment initiation and account information. Related to card issuing via payment rails but **not a complete card management system**.

### Additional Strong Open-Source Options

- **Core Banking Ledgers**: **Apache Fineract** (Apache-2.0, most mature), **Open Source Bank** (API-first, double-entry), **Mifos X** (Digital Public Good), **FinAegis** (modular domains).
- **Payment Switch Software**: **jPOS** (Java payment transaction processing, ISO 8583 support), **OpenACH** (ACH processing).
- **Card Management (Non-Issuing)**: **Snipe-IT** (asset tracking, not payment cards), **GLPI** (IT asset management).
- **Critical Gap**: **No open-source software provides card network connectivity (Visa/Mastercard), BIN sponsorship, or PCI-compliant card issuing out of the box.** Open-source covers the ledger and account layers; card issuance requires commercial partnerships.

**Frameworks for building custom systems**: Combine **Apache Fineract** or **Open Source Bank** for the core ledger and account infrastructure, **jPOS** for ISO 8583 payment message processing, and **custom development** for card lifecycle management (card numbers, CVV, expiration, tokenization). Add **PostgreSQL** for persistence and **HashiCorp Vault** for PCI-compliant key management. **Note**: Real card issuance requires a BIN sponsor, card network certification, and PCI DSS compliance—none of which open-source software provides .

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Card issuing platforms handle sensitive payment and personal data; ensure compliance with PCI DSS, KYC/AML, and relevant financial regulations.
- **Open-source reality**: **No production-ready open-source card issuing platform exists.** Open-source software covers the **ledger and account infrastructure** (Apache Fineract, Open Source Bank, Mifos X) but **not card network connectivity, BIN sponsorship, or PCI-compliant card issuance**. Building a card program requires commercial partnerships with a BIN sponsor and card network, plus significant compliance investment. Commercial platforms (Marqeta, Lithic, Highnote) remain the only practical path to production card programs .

---

**Made for fintech builders, embedded finance developers, product managers, and platform architects.**
Let's make card issuing infrastructure more open, transparent, and accessible.
