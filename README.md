# Awesome-Collaborative-Commerce

# Awesome-Collaborative-Commerce

**Top Collaborative Commerce (Opensource) 🌟 Star if you like it! 🌟**



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Multi-Vendor Marketplaces, Dropship Networks, Supplier Onboarding & Commission Management*

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Collaborative Commerce**. These tools enable brands, retailers, and suppliers to sell together—through curated marketplaces, dropship networks, and affiliate-style product exchanges—without building the infrastructure from scratch. The commercial space is dominated by managed platforms that handle vendor onboarding, commission splits, and order routing; the open-source space is thinner, but several mature commerce frameworks now ship native multi-vendor modules.



**Examples** include Shopify Collective, Mirakl, Canal, Convictional, Nautical Commerce, Marketplacer, balance, Tradera, TradeRunner, and VTEX Marketplace (the category leaders in commercial space).



**Open-source emphasis**: This section is expanded with every relevant project for self-hosting, multi-vendor commerce, and open marketplace infrastructure. **Critical note**: True open-source collaborative commerce—a turnkey platform where vendors self-onboard and commissions split automatically—does not exist as a drop-in SaaS replacement. The projects below are **commerce frameworks with marketplace modules** that you operate yourself, owning vendor governance, payouts, and compliance.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The digital commerce and collaborative marketplace platform sector represents an estimated global market size of approximately **$9B to $16B** (expanding toward **$28B+** in specialized commerce cloud infrastructure, projected at a 12%–15% CAGR). The market is **moderately to highly fragmented** rather than winner-take-all, divided across enterprise digital commerce giants, specialized B2B marketplace infrastructure engines, and niche composable/open-source frameworks.

## SaaS/Hosted Platforms

| Platform | Revenue / Valuation (Scale) | Starting Pricing | Free Tier / Free Trial Limits | Focus & Best For |
| :--- | :--- | :--- | :--- | :--- |
| **[Shopify Collective](https://www.shopify.com/collective)** | Market Cap: ~$125B+ (Shopify Inc.) / ~$8B+ Ann. Rev | Free add-on on standard plans (Shopify plans start at $39/mo billed monthly or $29/mo annually; standard transaction fees apply) | 3-day free trial on Shopify (followed by $1/mo promo for first 3 months); Collective itself has no additional subscription fee, but live checkouts require an active paid Shopify plan | Curated product exchange for Shopify merchants enabling cross-selling with inventory sync and automated order routing without holding inventory. |
| **[Mirakl](https://www.mirakl.com/)** | Valuation: $3.5B (Series E) / $15B+ GMV processed | Starts at ~$7,500/mo ($90,000–$100,000+/year base license) + ~1%–4.5% GMV take rate | No free tier or self-serve trial; custom proof-of-concept (PoC) and sales-guided demos only | Enterprise-scale multi-vendor marketplace platform for tier-1 retailers and distributors managing high seller counts. |
| **[balance](https://www.getbalance.com/)** | Valuation: ~$365M (Series B) / Rev: ~$15M–$50M | Starts at ~$2,000/mo base SaaS subscription + per-transaction fees (typically 1.5%–3% on net terms/invoicing) | No free tier or self-serve trial; live sandbox environment and enterprise demo available upon sales qualification | B2B payment, automated invoice processing, and instant net terms/financing infrastructure for marketplaces and wholesale trade. |
| **[VTEX Marketplace](https://vtex.com/)** | Market Cap: ~$650M (NYSE: VTEX) / Rev: ~$240.5M (FY2025) | Starts at ~$1,500–$2,000/mo base enterprise subscription + 1%–3% GMV variable success fee | No free tier or self-serve trial; demo and sandbox testing environments provided during enterprise sales scoping | Native enterprise marketplace engine embedded inside VTEX composable digital commerce suite. |
| **[Tradera](https://www.tradera.com/)** | Valuation: ~SEK 915M (~$85M) / Rev: ~€56.7M (~SEK 650M+) | Private sellers: 10% commission per sold item (min SEK 3, max SEK 200). Business stores: 0 SEK/mo (8% commission) or store plans from SEK 275/mo | Private sellers get 100 free listings/month (SEK 3–10 fee per unsold listing applied from 101st listing onwards); businesses get 500 free listings on basic tier | Nordic circular economy and consumer/B2B marketplace for second-hand, overstock, and new goods. |
| **[Marketplacer](https://marketplacer.com/)** | Funding: ~$85M–$100M total raised (Series C) / Est. Rev: ~$20M+ | Starts at ~$3,500–$5,000/mo (~$40,000–$60,000/year base SaaS license) + volume/take rate and implementation fees | No free tier or self-serve trial; guided software demonstrations and pilot scoping upon consultation | Scalable multi-vendor marketplace engine with catalog management and dropship connectivity for mid-to-large enterprises. |
| **[Convictional](https://www.convictional.com/)** | Funding: ~$49M (Series B) / Est. Rev: ~$8M–$12M | Starts at ~$2,000/mo base subscription fee + tiered transaction/order processing fees | No free tier or self-serve trial; custom enterprise pilot program and guided demonstrations only | Enterprise supplier enablement, automated dropship, and marketplace integration for omnichannel retailers. |
| **[Nautical Commerce](https://www.nauticalcommerce.com/)** | Funding: ~$32.2M (Series A, acquired by Traide) / Est. Rev: ~$4M+ | Starts at ~$1,500–$2,500/mo base platform license + transaction fees based on GMV | No free tier or self-serve trial; product demonstrations and sandbox evaluation upon request | Marketplace-as-a-service platform managing vendor onboarding, split checkout, and distributed catalog routing. |
| **[Canal](https://www.canal.com/)** | Funding / Valuation: Acquired by Rokt (July 2025; prior ARR ~$5.8M) | Starter: $0/mo install fee + 5% transaction fee on marketplace sales; Enterprise custom contract | Free plan available (Starter tier with $0 monthly platform fee, limited to 5% per-transaction fee on sales) | Collaborative commerce network allowing DTC brands and retailers to cross-sell products without inventory risk. |
| **[TradeRunner](https://www.traderunner.com/)** | Powered by Omnivore / City Beach Software (Est. Rev: ~$5M+) | Starts at $74.95/mo (Scale Up, up to $7,500/mo GMV) or 0.8% GMV (Pro tier, min $74.95/mo); Enterprise from $199.95/mo | Free plan available: $0/month for stores processing up to $1,000 USD in monthly sales revenue | Specialized marketplace integration connector syncing e-commerce stores (Shopify, WooCommerce, Magento) to Trade Me. |

## Open-Source GitHub Projects



- **[Mercur](https://github.com/mercurjs/mercur)**

  **Open-source enterprise marketplace platform** (license per repo; core built on Medusa) — **the most purpose-built open-source project for collaborative commerce** in this list. **Features**: Multi-vendor governance with sellers, offers against master products, order splitting per seller, policy-based commission rules, and **Stripe Connect payouts** for automated vendor disbursement; role-based access with auditable change pipeline; both admin and vendor panels; composable, API-first architecture . **Tech stack**: Medusa engine (Node.js, TypeScript), PostgreSQL, Stripe. **Deploy**: Self-hosted on your own infrastructure. **Trade-off**: **Commerce marketplace engine, not a turnkey SaaS**—you own deployment, vendor onboarding policy, and payment processor relationships. Commission and payout logic is configurable but requires setup. **Best for**: operators wanting full source control over a multi-vendor marketplace with automated commissions and payouts, without per-transaction platform fees.



- **[Spree Commerce](https://github.com/spree/spree)**

  **Open-source eCommerce framework with native marketplace module** (AGPL-3.0 for Community; Enterprise adds automations) — **the most battle-tested open-source option**, validated at scale by Maisonette (65,000+ products from hundreds of brands) . **Features (Community Edition)**: Vendor onboarding and approval workflows; vendor dashboard for self-service product management and fulfillment; **configurable commission rates per vendor, category, or product**; split-shipment tracking across vendors. **Enterprise Edition adds**: Stripe Connect payouts, Adyen for Platforms, promotion commission overrides, and two-way product/inventory/order sync for vendor migration . **Tech stack**: Ruby on Rails. **Deploy**: Self-hosted (Docker-first in 5.6; Redis no longer required, single image runs web and jobs) . **Trade-off**: **Framework, not a SaaS**—you operate the platform. Community Edition lacks automated payouts; Enterprise is licensed. **Best for**: developers and operators wanting a proven marketplace foundation with a clear upgrade path to automated payouts.



- **[Bagisto](https://github.com/bagisto/bagisto)**

  **Open-source Laravel eCommerce and multi-vendor marketplace platform** (license per repo) — **a full-stack option with a dedicated Multi Vendor Marketplace extension**. **Features**: Admin manages sellers, commissions, product approvals, and order handling; vendors get a dedicated dashboard for catalog, orders, and transactions; also supports B2B, multi-tenant SaaS marketplaces, POS, and headless commerce . **Tech stack**: Laravel (PHP), Vue.js. **Deploy**: Self-hosted (Docker one-liner: `docker run -d --name bagisto -p 80:80 webkul/bagisto:latest`) . **Trade-off**: **Full platform adoption required**—the marketplace is an extension, not a bolt-on to an existing store. Commission and payout automation depth varies by configuration. **Best for**: Laravel developers wanting a batteries-included commerce platform with native multi-vendor capabilities.



- **[GrandNode](https://github.com/grandnode/grandnode2)**

  **Open-source cross-platform eCommerce platform** (GPL-3.0) — **supports multi-vendor business models on .NET Core and MongoDB**. **Features**: Explicitly supports B2B, B2C, Multi-Store, **Multi-Vendor**, Multi-Tenant, Multi-Language, and Multi-Currency models; built for ASP.NET Core with MongoDB/NoSQL storage . **Tech stack**: C# (.NET Core), MongoDB / Azure CosmosDB / Amazon DocumentDB / LiteDB. **Deploy**: Self-hosted. **Trade-off**: **.NET ecosystem-specific**—multi-vendor support is a business model option, but vendor governance and commission automation depth requires evaluation against your requirements. **Best for**: .NET teams wanting an open-source commerce platform with multi-vendor support in a NoSQL stack.



- **[Liberu Ecommerce](https://github.com/liberusoftware/ecommerce-laravel)**

  **Open-source Laravel eCommerce platform** (MIT) — **a modern full-stack option positioned for multi-vendor marketplaces**. **Features**: The project explicitly states it provides the foundation for "launching a small online shop or building a multi-vendor marketplace"; includes reactive checkout, Stripe/PayPal, dropshipping via DropXL, and B2B wholesale pricing . **Tech stack**: Laravel 13, PHP 8.5, Filament 5, Livewire 4. **Deploy**: Self-hosted (interactive `./setup.sh`). **Trade-off**: **Early-stage for marketplace specifically**—multi-vendor is a stated use case, not a shipped module with vendor onboarding and commissions. Dropshipping is supplier-integration-oriented, not vendor self-service. **Best for**: Laravel developers wanting a modern, MIT-licensed foundation to build a marketplace upon, with dropship capabilities built in.



- **[flexcommerce-marketplace](https://pypi.org/project/flexcommerce-marketplace/)**

  **Django marketplace module for FlexCommerce** (MIT) — **a modular, Africa-focused marketplace backend** for Django + DRF. **Features**: Vendor applications with KYC and bank details; staff approval; **orders split per vendor inside checkout with commission snapshotted**; vendors manage their own catalog and shipping; refunds charged back to the correct vendor; **payouts generated after the hold period** . **Tech stack**: Python (Django), Django REST Framework. **Deploy**: Self-hosted (`pip install flexcommerce-marketplace`; add to `INSTALLED_APPS`). **Trade-off**: **Modular backend, not a full storefront**—you build the frontend and integrate with other FlexCommerce apps (core, orders). Designed with Nigerian/African payment and banking context. **Best for**: Django developers wanting a marketplace commission and payout engine as a composable package rather than a monolith.



### Additional Strong Open-Source Options



- **VendorBridge AI** — AI-powered procurement ERP (license per repo) with vendor management, RFQ, quotation comparison, approval workflows, and purchase orders . **Note**: **Procurement and vendor management**, not consumer-facing collaborative commerce—it governs supplier relationships for an organization's own purchasing, not multi-vendor sales. **Best for**: enterprises wanting AI-assisted supplier procurement, not marketplace operations.

- **SevenSquare Vendor Management** — Laravel + Electron vendor management system (license per repo) for supplier profiles, contracts, and purchase orders . **Note**: Same limitation as VendorBridge—internal procurement, not marketplace commerce.



**Frameworks for building custom systems**: Combine **Mercur** for purpose-built marketplace governance and Stripe Connect payouts with **Spree Commerce** for a battle-tested catalog and order engine (or its Enterprise edition for automated payouts), **Bagisto** for a Laravel-native full-stack marketplace, and **flexcommerce-marketplace** as a composable Django commission engine—creating a collaborative commerce stack matched to your existing technology and operational capacity. **None of these provide managed hosting or vendor support**—you own the infrastructure and vendor relationships.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, license (for open-source), and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Collaborative commerce platforms handling vendor data, commissions, and payouts must comply with data protection regulations (GDPR, CCPA, etc.), payment processor rules (PCI DSS where applicable), and marketplace tax obligations.

- **The "managed marketplace SaaS" vs. "commerce framework with marketplace module" distinction is absolute.** **Mirakl, Canal, Convictional, Nautical, Marketplacer, VTEX, Shopify Collective, Tradera, and TradeRunner** are **managed platforms**—they provide hosting, support, and often vendor networks. **Mercur, Spree, Bagisto, GrandNode, Liberu, and flexcommerce-marketplace** are **frameworks or modules**—you operate the infrastructure, onboard vendors yourself, and own compliance. **No open-source project provides a turnkey collaborative commerce network.**

- **Mercur is the most purpose-built open-source marketplace engine** for the core collaborative commerce problem—vendor governance, offers against master products, order splitting, commissions, and Stripe Connect payouts . **The trade-off**: it is built on Medusa and requires you to operate the stack. It does not provide vendor discovery or a ready-made supplier network.

- **Spree Commerce is the most battle-tested open-source marketplace foundation.** Maisonette runs 65,000+ products from hundreds of brands on Spree . The **Community Edition** includes vendor onboarding, dashboards, and commission configuration but **lacks automated payouts**; **Enterprise Edition** adds Stripe Connect and Adyen for Platforms . **Choose based on whether you need automated disbursement out of the box.**

- **Procurement tools are not collaborative commerce.** **VendorBridge AI** and **SevenSquare** manage suppliers for an organization's own purchasing . They do not enable multiple vendors to sell through a shared storefront. **Do not confuse internal vendor management with marketplace operations.**

- **Pricing opacity is universal across commercial marketplace platforms.** Mirakl, Canal, Convictional, Nautical, Marketplacer, VTEX, and TradeRunner require sales contact. Shopify Collective is included with Shopify. Tradera has transaction fees. **Validate with direct vendor conversations against your expected GMV and vendor count.**

- Self-hosted open-source solutions require proper server setup, payment processor configuration, security hardening, and ongoing maintenance. **Marketplace platforms handle vendor funds and commissions**—ensure your deployment meets payment processor requirements and your organization's security standards before processing live transactions.



---



**Made for developers, marketplace operators, and organizations building transparent collaborative commerce solutions.**

Let's make Collaborative Commerce more open, data-driven, and vendor-friendly.
