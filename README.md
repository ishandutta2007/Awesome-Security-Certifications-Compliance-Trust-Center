# Awesome-Security-Certifications-Compliance-Trust-Center

# Awesome Security Certifications & Compliance Trust Center

> A curated list of top Security Certifications and Compliance Trust Center platforms — both SaaS/Hosted commercial solutions and open-source alternatives for publishing audit reports, certifications, and security posture to build customer trust and accelerate sales.
> 🌟 Star this repo if you find it useful! 🌟

---

## 📋 Table of Contents

- [SaaS / Hosted Platforms](#-saas--hosted-platforms)
  - [SafeBase](#safebase)
  - [Vanta Trust Center](#vanta-trust-center)
  - [Drata Trust Center](#drata-trust-center)
  - [OneTrust Trust Center](#onetrust-trust-center)
  - [Whistic Trust Center](#whistic-trust-center)
  - [Panorays Trust Center](#panorays-trust-center)
  - [TrustArc Trust Center](#trustarc-trust-center)
  - [Druva Trust Center](#druva-trust-center)
  - [Tugboat Logic Trust Center (OneTrust)](#tugboat-logic-trust-center-onetrust)
  - [Secureframe Trust Center](#secureframe-trust-center)
- [Open-Source Software](#-open-source-software)
  - [Kodus Trust Center](#kodus-trust-center)
- [Comparison at a Glance](#-comparison-at-a-glance)
- [Contributing](#-contributing)

---

## 🟦 SaaS / Hosted Platforms

Commercial, cloud-hosted Security Certifications and Compliance Trust Center platforms. These are not open-source but are included as reference points for feature comparison.

### SafeBase
**Type:** Trust center platform with multi-product consolidation and AI questionnaire
SafeBase is a leading commercial trust center platform, now featuring a **Multi-Product Trust Center** (closed alpha) that consolidates security, privacy, and compliance information for multiple products onto a single page [citation:2]. Visitors can filter content by product using product pills, while identical content across products is automatically de-duplicated and rendered once with product tags [citation:2]. Compliance badges are shown as a de-duplicated list across all products, and compliance items are consolidated only if auditor, expiration date, and linked documents match [citation:2]. SafeBase remains the underlying engine for Drata's Trust Center for customers on the "New Drata experience."
**Best for:** Organizations with multiple products needing a consolidated trust center with intelligent content de-duplication and product-level filtering.

### Vanta Trust Center
**Type:** Trust center within compliance automation suite
Vanta's Trust Center helps organizations showcase compliance posture, reduce questionnaire fatigue, and accelerate sales. Key features include **compliance badges** for frameworks like SOC 2, ISO 27001, and GDPR; **NDA workflows** supporting both Clickwrap (lightweight checkbox) and DocuSign (formal e-signature); **access approvals** routing requests to internal approvers; and **CTM Tagging** (Custom Trust Metadata) for categorizing content by product, region, or audience [citation:5]. A **Revenue Influenced Report** tracks how the Trust Center accelerated or supported sales opportunities, demonstrating ROI [citation:5]. Branding is fully customizable with logos, fonts, colors, and custom domains [citation:5].
**Best for:** Vanta compliance customers wanting a well-integrated trust center with strong NDA workflows and revenue attribution reporting.

### Drata Trust Center
**Type:** Trust center powered by SafeBase with AI questionnaire assistance
Drata bundles its Trust Center through the SafeBase acquisition, providing a self-serve security hub for buyers with instant access to compliance documents and certifications [citation:6]. CrowdStrike processed nearly **7,000 access requests across 4,400 unique customer accounts** since mid-2025, with CRM integration automating nearly 90% of incoming requests, and **97% of customers** reporting the Trust Center answered most or all of their questions [citation:6]. The platform includes **AI Questionnaire Assistance** that drafts source-cited answers from approved Trust content and routes them to SMEs for review [citation:6].
**Best for:** Organizations wanting a unified GRC and Trust Center platform with proven enterprise adoption and AI-assisted questionnaire workflows.

### OneTrust Trust Center
**Type:** Privacy and compliance trust center within OneTrust suite
OneTrust's Trust Center provides access to certifications, audit reports, security documentation, privacy materials, Responsible AI resources, and system status in one place [citation:3]. It covers **ISO certifications** (information security, privacy, cloud security, quality), **SOC 2 Type II** audit reports, industry certifications (payment, healthcare, automotive), and trust/assurance certifications (public sector, regional, self-assessment, sustainability) [citation:3]. Security documentation includes penetration test reports, while privacy materials cover data transfers and contractual documentation. A dedicated **Responsible AI** section explains governance, ethical principles, and transparency practices [citation:3].
**Best for:** Organizations already in the OneTrust ecosystem wanting a comprehensive trust center covering privacy, security, and responsible AI in one portal.

### Whistic Trust Center
**Type:** Vendor assessment and trust sharing platform
Whistic's Trust Center consolidates standard questionnaires, audits, and certifications in one place, saving InfoSec teams hours previously spent answering questionnaires [citation:14]. The **August 2025 release** added a comprehensive analytics dashboard showing profile views, content engagement, visitor behavior, and key performance metrics, plus **questionnaire view tracking** (logged-in and anonymous viewers) [citation:4]. Questionnaires can be filtered by completed, in-progress, pending requests, and updated versions [citation:4]. Sharing options include publishing to the **Trust Center Exchange** (visible to Whistic customers) or direct share links, with a limit of three shares per month on free accounts [citation:14].
**Best for:** Organizations wanting a trust center integrated with vendor assessment workflows, particularly those already using Whistic for questionnaire management.

### Panorays Trust Center
**Type:** Trust center with pre-filled public information
Panorays Trust Center lets organizations share a ready-made security profile with potential customers, pre-filling publicly available information to save time [citation:8]. Features include inviting collaborators, adding NDAs, Salesforce integration, and creating **multiple Trust Centers for different use cases** [citation:8]. Sharing options include private links (email-specific or company-wide with optional expiration and NDA) and public links for websites. Engagement tracking shows date shared, NDA status, and last viewed date [citation:8].
**Best for:** Organizations already using Panorays for third-party risk management wanting a connected trust center with multiple sharing configurations.

### TrustArc Trust Center
**Type:** Privacy-focused trust center with no-code customization
TrustArc's Trust Center centralizes policies, disclosures, and trust-building information in a customizable no-code hub [citation:9]. Features include easy logo/color upload for branding, templates purpose-built for legal/security/compliance/availability information, draft/publish/preview updates, subprocessor disclosure templates, document visibility toggles (internal vs. external), certification badge display, email subscriptions for updates, version history control, and linking of privacy requests (consents, preferences, data subject forms) in one place [citation:9].
**Best for:** Organizations prioritizing privacy compliance wanting a trust center that integrates with consent and data subject request workflows.

### Druva Trust Center
**Type:** Data protection vendor trust center
Druva's Trust Center (security.druva.com) provides self-service access to its certifications and compliance attestations [citation:12]. Druva is certified or compliant with **SOC 2 Type II, HIPAA, CSA Level 1 and 2, ISO 27001:2022, FIPS 140-2 (GovCloud), FedRAMP Moderate ATO (GovCloud), Dubai Electronic Security Control (DESC), and Australian Government IRAP (Public Cloud)** [citation:12]. The trust center serves as the self-service portal for accessing these certifications, reflecting Druva's approach of achieving attestations for its cloud service rather than relying solely on CSP certifications [citation:12].
**Best for:** Druva customers and prospects needing direct access to Druva's security certifications and compliance documentation.

### Tugboat Logic Trust Center (OneTrust)
**Type:** AI-powered questionnaire automation with trust portal
Tugboat Logic (acquired by OneTrust) combines a customer-facing trust portal with AI-powered security questionnaire automation [citation:7]. The platform builds a knowledge base from previous questionnaire responses, policies, and compliance documentation, then uses AI to suggest answers for new questionnaires, reducing response time from days to hours [citation:7]. Each completed questionnaire improves the system's understanding, making future responses faster and more consistent. Pricing starts around **$8,000/year** [citation:7]. **Consideration:** OneTrust acquisition uncertainty creates questions about the long-term standalone product roadmap, and market visibility has decreased since the acquisition [citation:7].
**Best for:** Organizations wanting AI-powered questionnaire automation with a learning knowledge base, particularly those already in the OneTrust ecosystem.

### Secureframe Trust Center
**Type:** Compliance automation trust center
Secureframe's Fundamentals plan ($7,500/year) includes a Trust Center alongside evidence collection, policy management, and continuous control monitoring [citation:10]. The Complete tier adds advanced Trust Center features (custom domains, automated NDA workflow), advanced questionnaire automation (15,000 questions/year), and SSO/SCIM [citation:10]. Secureframe offers 300+ native integrations and a Comply AI layer for policies and remediation. Certifications supported include SOC 2 Type II, ISO 27001, HIPAA, PCI DSS, GDPR, NIST 800-53, NIST 800-171, CMMC, NIST CSF, ISO 42001, and FedRAMP [citation:10].
**Best for:** Mid-market organizations wanting a comprehensive compliance platform with a Trust Center included from the entry tier and broad certification support.

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
