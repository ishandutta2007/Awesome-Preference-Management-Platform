# Awesome-Preference-Management-Platform

## Top Preference Management Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Consent Management, Preference Centers, Cookie Compliance, Privacy Signals & Data Subject Preferences*
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Preference Management** (also called Consent & Preference Management). These systems capture, store, and enforce user consent and communication preferences across websites, apps, and enterprise systems to support privacy regulations (GDPR, CCPA/CPRA, ePrivacy, etc.).

**Examples** include OneTrust PreferenceChoice, Didomi, Usercentrics, TrustArc, Transcend, Osano, Sourcepoint, Consentmo, Cookie Information, and WireWheel (the category leaders).

**Open-source emphasis**: Full enterprise preference centers and multi-channel consent platforms are largely commercial. Strong open options exist for website consent banners and client-side CMPs (**Klaro** and similar). This section lists the best available open tools and is realistic about the gap in enterprise preference management.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[OneTrust PreferenceChoice / Consent & Preferences](https://www.onetrust.com/)**  
  Enterprise consent and preference management platform supporting websites, apps, and cross-channel preference centers within the broader OneTrust privacy suite.

- **[Didomi](https://www.didomi.io/)**  
  Consent and preference management platform with strong developer focus, multi-channel support, and compliance features.

- **[Usercentrics](https://usercentrics.com/)**  
  Consent management and preference platform focused on privacy compliance, user experience, and marketing optimization.

- **[TrustArc](https://trustarc.com/)**  
  Privacy and compliance platform offering consent and preference management capabilities for enterprises.

- **[Transcend](https://transcend.io/)**  
  Data privacy infrastructure platform with consent management, preference centers, and automated data rights enforcement.

- **[Osano](https://www.osano.com/)**  
  Consent and privacy platform designed for simplified compliance and preference management workflows.

- **[Sourcepoint](https://www.sourcepoint.com/)**  
  Consent management platform particularly strong for publishers and advertising-related consent use cases.

- **[Consentmo](https://www.consentmo.com/)**  
  Consent and cookie compliance solution commonly used for e-commerce and website preference management.

- **[Cookie Information](https://cookieinformation.com/)**  
  Consent management and cookie compliance platform focused on transparency and regulatory requirements.

- **[WireWheel](https://wirewheel.io/)**  
  Privacy and data governance platform that includes preference and consent management capabilities.

## Open-Source GitHub Projects
- **[Klaro](https://github.com/KIProtect/klaro)**  
  Popular open-source consent management platform (CMP) and privacy tool for websites. Lightweight, self-hosted, multilingual, and designed for GDPR/ePrivacy compliance.

- **[ConsentStack CMP and similar open CMPs](https://github.com/ConsentStack/cmp)**  
  Open-source, developer-focused consent management platform projects aiming for human-centric consent experiences.

- **[Cookie consent and banner open libraries](https://github.com/)**  
  Numerous lightweight open-source cookie consent banners and scripts (e.g., variants of Cookie Consent, Orejime, and related projects).

- **[IAB TCF and GPP open reference implementations](https://github.com/)**  
  Open tools and libraries supporting Transparency & Consent Framework and Global Privacy Platform signals.

- **[Preference center open prototypes](https://github.com/)**  
  Community experiments for building self-hosted preference centers where users manage marketing and data-use choices.

- **[Consent storage and API open backends](https://github.com/)**  
  Simple open services for recording and serving consent and preference records.

- **[Google Consent Mode and signal open helpers](https://github.com/)**  
  Tools that help implement Consent Mode v2 and related privacy signals in a transparent way.

- **[Privacy policy and notice open generators](https://github.com/)**  
  Supporting open tools for generating or managing privacy notices that accompany preference interfaces.

- **[Mobile consent SDK open experiments](https://github.com/)**  
  Early-stage open libraries for capturing consent in mobile applications.

- **[Audit and logging open components](https://github.com/)**  
  Tools for recording consent events and maintaining basic audit trails.

### Additional Strong Open-Source Options
- Using **Klaro** (or similar self-hosted CMPs) for website cookie and third-party consent when full enterprise features are not required.
- Combining open consent banners with a custom or lightweight backend for preference storage.
- Implementing IAB TCF/GPP open libraries when working in advertising ecosystems.
- Accepting that multi-brand preference centers, enterprise integrations, automated scanning, cross-channel enforcement, and advanced compliance reporting still favor commercial platforms (OneTrust, Didomi, Usercentrics, Transcend, Osano, etc.).
- Self-hosting open CMPs to keep consent data under your control while using commercial tools for complex preference orchestration.

**Frameworks for building custom systems**: Deploy Klaro or another open CMP on websites → configure services and purposes → store consent in first-party storage or a simple backend → expose a basic preference center → propagate signals to tags and APIs. Suitable for smaller sites or privacy-conscious teams. Commercial platforms remain the practical choice for large organizations that need unified preference management across web, app, CRM, and marketing systems with strong compliance support.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Consent and preference management is subject to privacy laws (GDPR, CCPA/CPRA, ePrivacy, and others). Incorrect implementation can create legal and regulatory risk. Open-source tools require careful configuration, testing, and ongoing maintenance to remain compliant. This list is not legal or compliance advice.

---
**Made for privacy, marketing, and engineering teams who need transparent and compliant preference management.**
Let's keep user choices respected, enforceable, and as open as practical.
