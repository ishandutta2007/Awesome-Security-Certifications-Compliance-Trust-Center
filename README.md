# Awesome-Security-Certifications-Compliance-Trust-Center

# Awesome Security Certifications & Compliance Trust Center

> A curated list of top Security Certifications and Compliance Trust Center platforms — both SaaS/Hosted commercial solutions and open-source alternatives for publishing audit reports, certifications, and security posture to build customer trust and accelerate sales.
> 🌟 Star this repo if you find it useful! 🌟

---

## 📋 Table of Contents

- [SaaS / Hosted Platforms](#-saas--hosted-platforms)
  - [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
  - [Comparison of SaaS Platforms](#comparison-of-saas-platforms)
- [Open-Source Software](#-open-source-software)
  - [Kodus Trust Center](#kodus-trust-center)
- [Comparison at a Glance](#-comparison-at-a-glance)
- [Contributing](#-contributing)

---

## 🟦 SaaS / Hosted Platforms

Commercial, cloud-hosted Security Certifications and Compliance Trust Center platforms.

### Sector Overview & Market Dynamics
The Compliance Automation and Trust Center software market is estimated at approximately **$35B to $39B** (expanding toward $75B+ by the 2030s at a ~14% CAGR) as continuous audit reporting and customer-facing security portals become mandatory deal accelerators in B2B sales. The sector is **moderately fragmented but consolidating rapidly**, where a handful of venture-backed category leaders (e.g., OneTrust, Vanta, Drata) aggressively acquire niche point solutions (such as SafeBase and Tugboat Logic) to build end-to-end "Trust Management" ecosystems.

### Comparison of SaaS Platforms

| Platform | Company Scale (Valuation / Revenue) | Starting Pricing (Paid Tier) | Free Tier Limits / Free Trial | Key Capabilities & Highlights |
|---|---|---|---|---|
| **OneTrust Trust Center** | Valuation: ~$5.0B / ARR: ~$500M+ | ~$10,000 / year (modular baseline) | No permanent free tier; time-limited sales sandbox / trial by request only | Comprehensive privacy, security & Responsible AI portal; broad ISO/SOC/industry certifications. |
| **Vanta Trust Center** | Valuation: ~$4.2B / ARR: ~$250M+ | ~$7,500 / year (Essentials tier) | No permanent free tier; guided evaluation / demo only (no open self-serve trial) | Full compliance automation suite, Clickwrap/DocuSign NDA workflows, CTM tagging, revenue attribution reporting. |
| **Drata Trust Center** | Valuation: ~$2.0B+ / Total Funding: ~$320M+ | ~$7,500 / year (Startup / Foundation tier) | No permanent free tier; guided sandbox / trial through partner/sales demo only | SafeBase-powered Trust Center, automated CRM access requests, AI questionnaire assistance (AIQA). |
| **Druva Trust Center** | Valuation: ~$2.0B / ARR: ~$200M+ | ~$35 to $75 / user / year (or consumption-based credits) | 30-day full-featured free trial (live onboarding checklist, cloud workload testing) | Dedicated customer security & compliance portal (security.druva.com) covering SOC 2, FedRAMP, ISO 27001, GovCloud attestations. |
| **SafeBase** | Valuation: $250M (Acquired by Drata) | ~$5,000 / year (Starter / Foundation paid plans) | Free Foundation plan: 1 trust center profile, capped document/Q&A items (~15 items), limited monthly request credits | Multi-product trust center consolidation, product pill filtering, intelligent badge de-duplication, AI questionnaire automation. |
| **TrustArc Trust Center** | Private Equity majority (Main Capital) / Funding: ~$109M | ~$8,000 / year (Baseline consent/compliance module) | 30-day time-bound evaluation trial (sales-provisioned pilot; no permanent free plan) | No-code trust center hub, privacy & subprocessor disclosures, consent/DSR workflow integration, version history tracking. |
| **Secureframe Trust Center** | Valuation: ~$250M–$500M / Peak ARR: ~$20M+ | $7,500 / year (Fundamentals tier) | No permanent free tier; sales-guided demo / pilot evaluation only (no open trial) | Trust Center included from entry tier, automated NDA workflows, custom domains, Comply AI, 300+ native integrations. |
| **Panorays Trust Center** | Total Funding: ~$62M / Est. ARR: ~$13M | ~$12,000 / year (Median contract ~$21,700/yr; modular tiering) | Permanent Free Starter Plan: 1 company profile, attack surface check, limited to evaluating up to 5 vendors | Third-party risk management integration, pre-filled public security profile, multiple trust centers per use case, NDA access controls. |
| **Whistic Trust Center** | Total Funding: ~$71M / Est. ARR: ~$11.5M | ~$10,000 / year (Core AI / Standard tier) | Free Basic Profile: 1 user seat, 1 profile published to Whistic Trust Catalog, capped at 3 proactive shares total | Vendor assessment & trust sharing, Whistic Trust Catalog publishing, questionnaire view analytics, profile engagement tracking. |
| **Tugboat Logic Trust Center** | Acquired by OneTrust (~$10M–$20M ARR segment) | ~$8,000 / year (Starter compliance tier) | No permanent free tier; customized guided sales demo only (no open self-serve trial) | AI-powered questionnaire automation with iterative learning knowledge base, coupled with customer-facing trust portal. |

---

## 🟩 Open-Source Software

Self-hosted, community-driven Security Certifications and Compliance Trust Center tools. The open-source ecosystem for **dedicated trust centers** is extremely limited, with essentially one mature project.

### Kodus Trust Center
**Stack:** Next.js / TypeScript / Supabase | **License:** Open Source
Kodus Trust Center is a **free, self-hosted, YAML-driven trust center builder** that lets you paste your security program into a single YAML document and instantly expose a polished trust portal [citation:11]. Features include:
- **Public trust center** with theming (light/dark), company logo, hero commitments, metrics, compliance cards, policies, documents, infrastructure, monitoring, updates, FAQs accordion, subprocessors, and contacts
- **Document requests** via modal collecting work email and context, stored in Supabase
- **Admin dashboard** with tabs for requests and YAML editor, GitHub SSO via NextAuth
- **API endpoints** for `/api/requests` (list/create) and `/api/trust-config` (load/save YAML)
- **YAML schema** with layout control (sections can be `full`/`half` width or hidden entirely)

Everything lives in your repo or Supabase project, deployable to Vercel, Fly, Render, or any Next.js host. The project explicitly positions itself as "no paid SaaS, no vendor lock-in" with sales and security teams able to edit the YAML, save, and immediately refresh the public page [citation:11].
**Best for:** Small to mid-sized teams wanting a self-hosted trust center that can be edited via YAML by sales and security teams, without a commercial subscription.

---

## 📊 Comparison at a Glance

| Software | License | Stack | Public Trust Page | Questionnaire AI | Multi-Product | Self-Hosted | Best For |
|----------|---------|-------|-------------------|-------------------|---------------|-------------|----------|
| **SafeBase** | Proprietary | Cloud | ✅ | ✅ | ✅ Alpha | ❌ | Multi-product consolidation |
| **Vanta** | Proprietary | Cloud | ✅ | (Suite) | (CTM tags) | ❌ | Compliance + Trust Center |
| **Drata** | Proprietary | Cloud | ✅ SafeBase | ✅ AIQA | (SafeBase) | ❌ | Unified GRC + Trust |
| **OneTrust** | Proprietary | Cloud | ✅ | (Suite) | ❌ | ❌ | Privacy + security + AI |
| **Whistic** | Proprietary | Cloud | ✅ | (Suite) | ❌ | ❌ | Vendor assessment + trust |
| **Panorays** | Proprietary | Cloud | ✅ | ❌ | ✅ Multiple | ❌ | TPRM-connected trust |
| **TrustArc** | Proprietary | Cloud | ✅ | ❌ | ❌ | ❌ | Privacy-focused trust |
| **Druva** | Proprietary | Cloud | ✅ | ❌ | ❌ | ❌ | Druva certifications |
| **Tugboat Logic** | Proprietary | Cloud | ✅ | ✅ Learning KB | ❌ | ❌ | Questionnaire automation |
| **Secureframe** | Proprietary | Cloud | ✅ | (Suite) | ❌ | ❌ | Mid-market compliance |
| **Kodus Trust Center** | Open Source | Next.js/Supabase | ✅ YAML | ❌ | ❌ | ✅ | Self-hosted trust portal |

---

## 🤝 Contributing

Contributions are welcome! If you know of an open-source Security Certifications or Compliance Trust Center tool that should be listed here, please open a pull request with:

- Project name and URL
- Brief description (1–2 sentences)
- Stack and license
- Why it stands out

Please ensure the project is actively maintained (releases within the last 12 months) and genuinely open-source. Note that the open-source ecosystem for **dedicated trust centers** is essentially limited to **Kodus Trust Center**, a self-hosted YAML-driven builder that provides compliance badges, document requests, and subprocessor disclosure without commercial subscription [citation:11]. Commercial platforms like SafeBase, Vanta, and Drata offer significantly more advanced capabilities: SafeBase's multi-product consolidation with intelligent content de-duplication [citation:2], Vanta's NDA workflows and revenue attribution reporting [citation:5], and Drata's proven enterprise adoption with 97% customer satisfaction and AI questionnaire assistance [citation:6]. For organizations needing a free starting point, Kodus provides a solid foundation, but enterprise procurement will typically expect the polish and automation of commercial platforms.

---

## 📄 License

This list is released under CC0 1.0 Universal (Public Domain). The software projects listed retain their respective licenses.

---

⭐ **If this list helped you discover a useful tool, please star the repo!** ⭐
