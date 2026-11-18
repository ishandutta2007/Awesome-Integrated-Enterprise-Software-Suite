# Awesome-Integrated-Enterprise-Software-Suite

## Top Inactive User Data Archiving & Offboarding Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Inactive User Detection, Offboarding Workflows, Data Retention, Mailbox Archiving & Identity Lifecycle*

**Last updated: November 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Inactive User Data Archiving & Offboarding**. These tools detect inactive accounts, run structured offboarding (revoke access, transfer ownership, archive data), apply retention policies, and manage identity lifecycle from leave of absence through termination.

---

## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

---

## Sector Overview & Market Dynamics

The combined market covering Identity Governance and Administration (IGA) and SaaS Management Platforms (SMP) is estimated at **$14B – $27B in 2026**, expanding rapidly at an estimated 10%–15% CAGR driven by strict compliance mandates (GDPR, DORA, HIPAA) and zero-trust security postures. The sector exhibits **moderate fragmentation with ongoing platform consolidation**: while horizontal hyperscalers and identity giants (Microsoft, Alphabet, Okta, SailPoint) dominate core identity lifecycle contracts, specialized pure-play vendors (BetterCloud, Torii, Lumos, Druva) continue to capture significant market share around multi-SaaS shadow-IT discovery, granular offboarding workflows, and automated cross-app data archiving.

---

## SaaS/Hosted Platforms

The table below lists leading SaaS products for inactive user archiving, automated deprovisioning, and identity offboarding, sorted in descending order by enterprise company size (market valuation / market capitalization).

| Product | Company Valuation / Market Cap | Pricing (Starting Tier) | Free Tier / Free Trial Limits | Key Offboarding & Archiving Capabilities |
| :--- | :--- | :--- | :--- | :--- |
| **[Microsoft 365 Inactive Mailbox](https://www.microsoft.com/en-us/microsoft-365)** | ~$3.84T (Market Cap) | $8.00/user/month (Exchange Online Plan 2) | No direct standalone trial for Plan 2; standard 30-day trial available via Microsoft 365 E3/E5 suites (up to 25 licenses) | Places departing user mailboxes on Litigation/Retention Hold; upon deleting account, mailbox converts to an Inactive Mailbox retaining all data without ongoing license cost. |
| **[Google Workspace Inactive User Policy](https://workspace.google.com/)** | ~$3.50T (Market Cap) | $2.00/user/month (Business Starter Archived User - AU License) | 14-day free trial on primary Google Workspace plans (up to 10 users); no standalone free trial for AU licenses | Retains departing user data, files in Google Drive, and Gmail under Google Vault retention policies at reduced licensing costs without active user access. |
| **[Okta Lifecycle Management](https://www.okta.com/)** | ~$31.0B (Market Cap) | $14.00/user/month (Core Essentials tier, $1,500 annual contract minimum) | 30-day free trial (Workforce Identity Cloud environment supporting up to 10 test users and workflow executions) | Automated Joiner-Mover-Leaver (JML) provisioning and deprovisioning, inactivity detection, and Okta Workflows for triggering custom revocation scripts across SaaS apps. |
| **[Rippling Offboarding](https://www.rippling.com/)** | ~$16.0B (Valuation) | $8.00/user/month (+ $35.00/month base platform fee; IT Cloud add-on starts at additional $5.00/user/month) | No standard self-service free trial for core HR; 14-day evaluation trial available for standalone IT/Device management modules | Automatically detects termination/leave in HRIS to instantly revoke SSO/SaaS logins, retrieve corporate hardware, and initiate file transfer/delegation. |
| **[SailPoint Lifecycle Management](https://www.sailpoint.com/)** | ~$12.8B (Valuation) | ~$5.00 – $7.50/identity/month (~$60–$90/identity/year; software subscription entry starts at ~$75,000/year minimum) | No public self-service free trial; scoped 30-day to 90-day enterprise Proof of Concept (PoC) available via direct sales | Enterprise IGA platform delivering end-to-end joiner-mover-leaver lifecycle controls, automated deprovisioning, role revocation, and audit certification reporting. |
| **[Druva Inactive User Retention](https://www.druva.com/)** | ~$2.0B (Valuation) | ~$4.00 – $8.00/user/month (Druva inSync SaaS/Endpoint Protection) | 30-day free trial (Full-featured access for cloud apps and endpoint backup, no credit card required) | Comprehensive cloud backup for Google Workspace, M365, and laptops; preserves inactive user snapshots and enables legal holds without keeping native SaaS licenses active. |
| **[BambooHR Offboarding](https://www.bamboohr.com/)** | ~$1.9B (Valuation) | $10.00/employee/month (Core Plan for >25 employees; $250/month flat fee for ≤25 employees) | 7-day free trial (Full platform sandbox access, no credit card required) | Structured offboarding checklists, task assignments, and webhook/API triggers for IT deprovisioning and asset handover when an employee departs. |
| **[BetterCloud](https://www.bettercloud.com/)** | ~$400M (Valuation) | Custom quote based on seats & connectors; starting tiers entry ~$3.00 – $6.00/user/month (~$5,000/year minimum) | Spend Optimization Free tier available ($0/month for basic spend and contract tracking); 14-day free trial for File Governance/SaaS management modules | No-code SaaS operations automation that listens for inactive accounts, deprovisions multi-SaaS access, transfers Google Drive/OneDrive files, and forwards email. |
| **[Torii](https://www.toriihq.com/)** | ~$350M (Valuation) | Entry tiers start at ~$2.00 – $2.50/employee/month (billed annually, custom enterprise plans based on total employee count) | Free trial / Proof-of-concept (PoC) available upon request (14 to 30 days guided evaluation) | Discovers shadow IT and inactive SaaS licenses; triggers automated multi-app offboarding workflows to revoke access and reallocate or cancel unused seat licenses. |
| **[Lumos](https://www.lumos.com/)** | ~$250M (Valuation) | Custom quote based on identity volume; mid-market deployments typically start around ~$3.00/user/month ($10,000 annual entry) | No public self-serve free trial; 30-day guided Proof of Concept (PoC) pilot available upon enterprise request | Unified AppStore and Identity Governance platform automating access revocation, software license reclamation, and inactive user privilege cleanups. |

---

## Open-Source GitHub Projects

The following open-source identity governance platforms, directories, access brokers, and automation frameworks provide building blocks for self-hosted inactive user detection, access deprovisioning, and data archiving. Entries are sorted in descending order by GitHub star count.

| Project | GitHub Stars | Focus / Role in Offboarding & Archiving |
| :--- | :--- | :--- |
| **[Ansible](https://github.com/ansible/ansible)** | [![Stars](https://img.shields.io/github/stars/ansible/ansible?style=social&color=white)](https://github.com/ansible/ansible/stargazers) | Playbooks and automation roles that disable target accounts, revoke SSH keys, transfer data ownership, and archive user home directories. |
| **[Keycloak](https://github.com/keycloak/keycloak)** | [![Stars](https://img.shields.io/github/stars/keycloak/keycloak?style=social&color=white)](https://github.com/keycloak/keycloak/stargazers) | Standard enterprise open-source IdP; provides REST admin APIs and event listeners to trigger account deactivation and downstream offboarding webhooks. |
| **[Authelia](https://github.com/authelia/authelia)** | [![Stars](https://img.shields.io/github/stars/authelia/authelia?style=social&color=white)](https://github.com/authelia/authelia/stargazers) | Lightweight authentication and authorization server; centralizes session revocation and access cutoff across reverse proxy-protected internal apps. |
| **[Authentik](https://github.com/goauthentik/authentik)** | [![Stars](https://img.shields.io/github/stars/goauthentik/authentik?style=social&color=white)](https://github.com/goauthentik/authentik/stargazers) | Modern IdP featuring rich configurable flows, SCIM provider/consumer support, and stage bindings to coordinate automated user suspension and access revocation. |
| **[Ory Hydra](https://github.com/ory/hydra)** | [![Stars](https://img.shields.io/github/stars/ory/hydra?style=social&color=white)](https://github.com/ory/hydra/stargazers) | Hardened OAuth 2.0 and OpenID Connect engine with administrative endpoints to revoke access/refresh tokens and terminate active client sessions during offboarding. |
| **[Zitadel](https://github.com/zitadel/zitadel)** | [![Stars](https://img.shields.io/github/stars/zitadel/zitadel?style=social&color=white)](https://github.com/zitadel/zitadel/stargazers) | Cloud-native identity infrastructure with multi-tenancy, granular audit logs, and APIs designed to programmatically lock accounts and automate leaver flows. |
| **[Casdoor](https://github.com/casdoor/casdoor)** | [![Stars](https://img.shields.io/github/stars/casdoor/casdoor?style=social&color=white)](https://github.com/casdoor/casdoor/stargazers) | Modern UI-first identity and access management (IAM) platform supporting SCIM, LDAP synchronization, and Webhooks for event-driven offboarding hooks. |
| **[Ory Kratos](https://github.com/ory/kratos)** | [![Stars](https://img.shields.io/github/stars/ory/kratos?style=social&color=white)](https://github.com/ory/kratos/stargazers) | Headless identity and user management system supporting explicit account states (`active`, `inactive`) and identity deletion APIs for lifecycle handling. |
| **[mailcow: dockerized](https://github.com/mailcow/mailcow-dockerized)** | [![Stars](https://img.shields.io/github/stars/mailcow/mailcow-dockerized?style=social&color=white)](https://github.com/mailcow/mailcow-dockerized/stargazers) | Self-hosted mailserver suite with API-driven mailbox archiving, quarantine controls, alias reassignment, and account deactivation for departing staff. |
| **[Dex IdP](https://github.com/dexidp/dex)** | [![Stars](https://img.shields.io/github/stars/dexidp/dex?style=social&color=white)](https://github.com/dexidp/dex/stargazers) | Pluggable OpenID Connect identity provider that acts as a portal to upstream directories (LDAP, SAML, GitHub), enabling global access cutoff at the root directory level. |
| **[Kanidm](https://github.com/kanidm/kanidm)** | [![Stars](https://img.shields.io/github/stars/kanidm/kanidm?style=social&color=white)](https://github.com/kanidm/kanidm/stargazers) | Rust-based identity management system with strong authentication, strict POSIX/OAuth2/LDAP controls, and deterministic account suspension rules. |
| **[FreeIPA](https://github.com/freeipa/freeipa)** | [![Stars](https://img.shields.io/github/stars/freeipa/freeipa?style=social&color=white)](https://github.com/freeipa/freeipa/stargazers) | Integrated Linux/Unix identity and domain management with host-based access control (HBAC), sudo policies, and user locking for infrastructure offboarding. |
| **[Janssen Project](https://github.com/JanssenProject/jans)** | [![Stars](https://img.shields.io/github/stars/JanssenProject/jans?style=social&color=white)](https://github.com/JanssenProject/jans/stargazers) | High-performance open-source IAM and identity governance components (from Gluu) for identity lifecycle and high-throughput SCIM operations. |
| **[midPoint](https://github.com/Evolveum/midpoint)** | [![Stars](https://img.shields.io/github/stars/Evolveum/midpoint?style=social&color=white)](https://github.com/Evolveum/midpoint/stargazers) | Flagship open-source Identity Governance and Administration (IGA) platform featuring complete Joiner-Mover-Leaver (JML) lifecycle workflows, role mining, and automated connector deprovisioning. |
| **[Apache Syncope](https://github.com/apache/syncope)** | [![Stars](https://img.shields.io/github/stars/apache/syncope?style=social&color=white)](https://github.com/apache/syncope/stargazers) | Enterprise open-source digital identity management system handling synchronization, identity lifecycle workflows, and automated deprovisioning connectors. |

---

### Implementation Patterns & Architecture

- **Full Open IGA Lifecycle**: **midPoint** functions as the direct open-source counterpart to enterprise solutions like SailPoint, providing native Joiner-Mover-Leaver (JML) state management, automated entitlement revocation, and inactive user reconciliation.
- **IdP-Driven Deprovisioning**: Deploy **Keycloak**, **Authentik**, **Zitadel**, or **Casdoor** as the central identity broker. Suspending an account at the IdP instantly severs SSO access across all SAML/OIDC federated enterprise apps.
- **SCIM Protocol Automation**: Using open SCIM 2.0 connectors ensures that deactivating an account in the primary identity directory propagates real-time suspension and license revocation to downstream cloud services.
- **Data Archiving & Mailbox Preservation**: Infrastructure orchestration via **Ansible** alongside self-hosted services like **mailcow** allows organizations to snapshot user mailboxes, archive home directories to immutable S3 storage, and reassign critical mailbox aliases before purging active identities.

---

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow the table formats and include pricing, trial limits, and valuation/stars).
3. Include factual descriptions and link to official documentation or source repositories.
4. Submit a pull request with a concise summary of updates.

---

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Offboarding and data archiving involve personal data, access control, and legal retention obligations. Ensure compliance with applicable employment, privacy, and records laws. This list is not legal, HR, or security advice.

---

**Made for identity teams, IT ops, HR tech, and open-source advocates.**
