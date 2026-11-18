# Awesome-Integrated-Enterprise-Software-Suite

## Top Inactive User Data Archiving & Offboarding Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Inactive User Detection, Offboarding Workflows, Data Retention, Mailbox Archiving & Identity Lifecycle*

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Inactive User Data Archiving & Offboarding**. These tools detect inactive accounts, run structured offboarding (revoke access, transfer ownership, archive data), apply retention policies, and manage identity lifecycle from leave of absence through termination.



**Examples** include Druva Inactive User Retention, Google Workspace Inactive User Policy, Microsoft 365 Inactive Mailbox, BetterCloud Inactive User Offboarding, Torii Offboarding, Lumos Identity Offboarding, Rippling Offboarding, BambooHR Offboarding, SailPoint Lifecycle Management, and Okta Lifecycle Management (the category leaders).



**Open-source emphasis**: Full commercial offboarding suites are mostly SaaS, but strong open building blocks exist for identity lifecycle, access revocation, and archival workflows—especially **midPoint**, **Keycloak**, **Authentik**, SCIM-based automation, and infrastructure-as-code offboarding. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Druva Inactive User Retention](https://www.druva.com/)**  

  Cloud data protection with controls for retaining and managing data belonging to inactive or departed users.



- **[Google Workspace Inactive User Policy](https://workspace.google.com/)**  

  Admin policies and tools to identify inactive users, suspend accounts, and manage data retention within Google Workspace.



- **[Microsoft 365 Inactive Mailbox](https://www.microsoft.com/en-us/microsoft-365)**  

  Inactive mailbox and retention features in Exchange Online / Microsoft 365 for preserving departed-user email under compliance policies.



- **[BetterCloud](https://www.bettercloud.com/)**  

  SaaS operations platform with automated offboarding workflows across many cloud apps (deprovision, transfer, archive).



- **[Torii](https://www.toriihq.com/)**  

  SaaS management platform focused on discovery, optimization, and structured employee offboarding across the app stack.



- **[Lumos](https://www.lumos.com/)**  

  Identity and access platform with offboarding and lifecycle workflows to revoke and transfer access at scale.



- **[Rippling Offboarding](https://www.rippling.com/)**  

  HR + IT platform with integrated offboarding that ties employment status to account deprovisioning and device/data handling.



- **[BambooHR Offboarding](https://www.bamboohr.com/)**  

  HR system with offboarding checklists and workflows that trigger downstream IT and access actions.



- **[SailPoint Lifecycle Management](https://www.sailpoint.com/)**  

  Enterprise identity governance with joiner-mover-leaver (JML) processes, access certification, and automated deprovisioning.



- **[Okta Lifecycle Management](https://www.okta.com/)**  

  Identity lifecycle features (including Workflows) for provisioning and deprovisioning users across connected applications.



## Open-Source GitHub Projects

- **[midPoint](https://github.com/Evolveum/midpoint)**  

  Leading open-source identity governance and administration (IGA) platform with full joiner-mover-leaver lifecycle, roles, and automated provisioning/deprovisioning.



- **[Keycloak](https://github.com/keycloak/keycloak)**  

  Open-source IdP with admin APIs, user federation, and event hooks that can drive disable/delete flows and integrate with offboarding automation.



- **[Authentik](https://github.com/goauthentik/authentik)**  

  Modern open-source identity provider with flows and policies useful for deactivating users and coordinating access revocation.



- **[Apache Syncope](https://github.com/apache/syncope)**  

  Open-source identity management system supporting provisioning, reconciliation, and lifecycle-oriented workflows.



- **[Ory Kratos](https://github.com/ory/kratos)**  

  Open-source identity management with account states and APIs that support disable/delete and self-service or admin-driven lifecycle actions.



- **[Zitadel](https://github.com/zitadel/zitadel)**  

  Open-source identity infrastructure with multi-tenancy and APIs suitable for automating user suspension and offboarding.



- **[FreeIPA](https://github.com/freeipa/freeipa)**  

  Integrated open-source identity management (Linux/Unix) with user lifecycle controls, HBAC, and sudo policies for on-prem offboarding.



- **[SCIM-related tools & libraries](https://github.com/search?q=scim)**  

  Open SCIM server/client implementations used to standardize create/update/deactivate of users across apps during offboarding.



- **[Ansible / automation offboarding roles](https://github.com/search?q=offboarding+ansible)**  

  Community playbooks and roles that disable accounts, revoke keys, transfer ownership, and archive home directories or mail.



- **[Kanidm](https://github.com/kanidm/kanidm)**  

  Modern open-source identity platform with strong auth and administrative controls that can support structured account lifecycle.



- **[Janssen / Gluu-related projects](https://github.com/JanssenProject)**  

  Open-source identity components useful in custom lifecycle and deprovisioning pipelines.



- **[Documentation and JML patterns](https://docs.evolveum.com/midpoint/)**  

  Guides for implementing joiner-mover-leaver processes, inactivity policies, and archival hand-offs with open identity platforms.



### Additional Strong Open-Source Options

- Full open IGA lifecycle with **midPoint** (closest OSS counterpart to SailPoint-style JML).

- IdP-driven disable/deprovision via **Keycloak**, **Authentik**, **Zitadel**, or **Ory Kratos**.

- Directory-centric offboarding with **FreeIPA** and delegated admin rights.

- Cross-app consistency through **SCIM** servers/clients and event-driven scripts.

- Infrastructure automation (**Ansible**, custom APIs) for mailbox archive, file transfer, and secret revocation.

- Pairing open identity tools with self-hosted mail/file platforms (e.g. archive then suspend) for data retention.

- Accepting that commercial suites (BetterCloud, Torii, Lumos, Rippling, SailPoint, Okta, Microsoft 365, Google Workspace, Druva) still lead in breadth of SaaS connectors, HRIS integration, and turnkey compliance reporting.



**Frameworks for building custom systems**: Run **midPoint** (or Keycloak + automation) as the lifecycle engine → detect inactivity via last-login/HR signals → disable IdP account → SCIM/API deprovision apps → archive mail/files to immutable or long-term storage → transfer ownership. Suitable for teams that want transparent, self-hosted control over offboarding. Many organizations still use commercial offboarding and retention products for multi-SaaS coverage and audit requirements.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Offboarding and data archiving involve personal data, access control, and legal retention obligations. Ensure compliance with applicable employment, privacy, and records laws. This list is not legal, HR, or security advice.



---

**Made for identity teams, IT ops, HR tech, and open-source advocates.**

Let's keep inactive-user handling secure, auditable, and as open as practical.
