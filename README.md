# secbyte-enterprise-identity-azure-gpo-drift-architecture-ctf-labs
A practical collection of cybersecurity CTF labs covering enterprise identity security, Azure/Entra ID investigations (PIM, Token Trails, Phantom Tenants, Federation), single sign-on (SSO) drift, GPO/EDR blindspots, asset inventory drift, and enterprise security architecture design.
# Enterprise Identity Security, Azure Entra ID, GPO Drift & Architecture Design CTF Labs

Welcome to the **Enterprise Identity Security, Azure Entra ID, GPO Drift & Architecture Design CTF Lab Collection**. This repository serves as an organized, searchable catalog of practical cybersecurity labs hosted on Learn SecByte.

This collection focuses on enterprise-scale identity governance, cloud directory security, operational policy drift, and defensive architectural design—spanning **Azure & Cloud Identity Security (Azure PIM, OAuth/OIDC token trails, identity federation, phantom tenants)**, **Enterprise Access Control & SSO Drift (Enterprise SSO drift, policy drift, GPO/EDR blindspots, inventory drift)**, and **Enterprise Defense & Security Architecture Design (Meridian Health Group incident, SentinelGrid breach simulation, blueprint review, lateral movement tracking)**.

---

## Lab Collection Index

### 1. Azure & Cloud Identity Security Operations
* **Azure Identity Investigation: Phantom Tenant**  
  *Lab Link:* [https://learn.secbyte.org/ctf/azure-identity-investigation-phantom-tenant](https://learn.secbyte.org/ctf/azure-identity-investigation-phantom-tenant)  
  *Focus:* Investigating unauthorized multi-tenant cross-tenant synchronization, detecting shadow Azure AD/Entra ID tenants, and analyzing cross-tenant access settings.

* **Azure PIM: The Just-In-Time Identity Incident**  
  *Lab Link:* [https://learn.secbyte.org/ctf/azure-pim-the-just-in-time-identity-incident](https://learn.secbyte.org/ctf/azure-pim-the-just-in-time-identity-incident)  
  *Focus:* Auditing Privileged Identity Management (PIM) role activations, detecting unauthorized activation requests, enforcing approval workflows, and triaging JIT access anomalies.

* **Identity Federation: Broken Trust**  
  *Lab Link:* [https://learn.secbyte.org/ctf/identity-federation-broken-trust](https://learn.secbyte.org/ctf/identity-federation-broken-trust)  
  *Focus:* Analyzing identity provider (IdP) federation trust relationships, detecting SAML token forging (Golden SAML), and fixing certificate drift in ADFS and external IdPs.

<Image src="image_agent_tag_3104369198736806922" alt="Federated identity authentication flow between on-premises Active Directory and Azure Active Directory" caption="Enterprise Identity Federation & Cloud SSO Trust Architecture" />

---

* **Azure Authentication Flow: Token Trails**  
  *Lab Link:* [https://learn.secbyte.org/ctf/azure-authentication-flow-token-trails](https://learn.secbyte.org/ctf/azure-authentication-flow-token-trails)  
  *Focus:* Tracking OAuth2 and OpenID Connect (OIDC) token flows in Azure/Entra ID, analyzing refresh token theft, detecting Family-of-Client-IDs (FOCI) abuse, and triaging sign-in logs.

### 2. Enterprise Access Control, SSO & Configuration Drift
* **Enterprise Access Management: SSO Drift Incident**  
  *Lab Link:* [https://learn.secbyte.org/ctf/enterprise-access-management-sso-drift-incident](https://learn.secbyte.org/ctf/enterprise-access-management-sso-drift-incident)  
  *Focus:* Triaging single sign-on configuration drift, uncovering unmapped enterprise SaaS applications, and reconciling orphaned user access permissions across Okta/Entra ID.

* **Policy Drift: Boardroom Breach**  
  *Lab Link:* [https://learn.secbyte.org/ctf/policy-drift-boardroom-breach](https://learn.secbyte.org/ctf/policy-drift-boardroom-breach)  
  *Focus:* Investigating executive account compromises resulting from unaligned security policies, auditing Conditional Access policy bypasses, and restoring policy baselines.

* **Inventory Drift: The Missing Asset**  
  *Lab Link:* [https://learn.secbyte.org/ctf/inventory-drift-the-missing-asset](https://learn.secbyte.org/ctf/inventory-drift-the-missing-asset)  
  *Focus:* Reconciling active network assets against CMDB records, discovering unmanaged shadow infrastructure, and remediating inventory coverage gaps.

* **Endpoint Sentinel: GPO Drift & EDR Blindspots**  
  *Lab Link:* [https://learn.secbyte.org/ctf/endpoint-sentinel-gpo-drift-edr-blindspots](https://learn.secbyte.org/ctf/endpoint-sentinel-gpo-drift-edr-blindspots)  
  *Focus:* Auditing Active Directory Group Policy Objects (GPO) for unauthorized security changes, detecting EDR agent tamper events, and closing endpoint coverage blindspots.

### 3. Enterprise Defense, Incident Response & Security Architecture
* **Blueprint Breach: Security Architecture Design**  
  *Lab Link:* [https://learn.secbyte.org/ctf/blueprint-breach-security-architecture-design](https://learn.secbyte.org/ctf/blueprint-breach-security-architecture-design)  
  *Focus:* Auditing corporate security architecture blueprints, evaluating Zero Trust network segmentation boundaries, and identifying architectural single points of failure.

<Image src="image_agent_tag_3104369198736808637" alt="Zero Trust Security Architecture roadmap and access control principles" caption="Zero Trust Enterprise Access Control Architecture" />

---

* **Enterprise Risk Assessment: Meridian Health Group Incident Response**  
  *Lab Link:* [https://learn.secbyte.org/ctf/enterprise-risk-assessment-meridian-health-group-incident-re](https://learn.secbyte.org/ctf/enterprise-risk-assessment-meridian-health-group-incident-re)  
  *Focus:* Conducting an enterprise-wide risk assessment following a major healthcare network breach, evaluating blast radius pathways, and designing containment strategies.

* **Enterprise Network Defense: Identity Logs and Lateral Movement**  
  *Lab Link:* [https://learn.secbyte.org/ctf/enterprise-network-defense-identity-logs-and-lateral-movemen](https://learn.secbyte.org/ctf/enterprise-network-defense-identity-logs-and-lateral-movemen)  
  *Focus:* Correlating Active Directory Kerberos/NTLM authentication logs (Event IDs 4624, 4672, 4768) to trace lateral movement vectors (Pass-the-Hash, Overpass-the-Hash) across host boundaries.

* **Enterprise Security: SentinelGrid Breach Simulation**  
  *Lab Link:* [https://learn.secbyte.org/ctf/enterprise-security-sentinelgrid-breach-simulation](https://learn.secbyte.org/ctf/enterprise-security-sentinelgrid-breach-simulation)  
  *Focus:* Running a full-scale enterprise red/blue breach simulation, triaging multi-vector attacks against hybrid environments, and enforcing defense-in-depth controls.

---

## Learning Path

### Path A: Azure & Entra ID Security Specialist
1. **Cloud Identity & Auth:** Start with [Azure Authentication Flow: Token Trails](https://learn.secbyte.org/ctf/azure-authentication-flow-token-trails) and [Identity Federation: Broken Trust](https://learn.secbyte.org/ctf/identity-federation-broken-trust).
2. **PIM & Cross-Tenant Security:** Master cloud access controls in [Azure PIM: The Just-In-Time Incident](https://learn.secbyte.org/ctf/azure-pim-the-just-in-time-identity-incident) and [Azure Identity Investigation: Phantom Tenant](https://learn.secbyte.org/ctf/azure-identity-investigation-phantom-tenant).

### Path B: Enterprise Access Management & Policy Drift Specialist
1. **Access Controls & SSO:** Triage corporate access issues in [Enterprise Access Management: SSO Drift Incident](https://learn.secbyte.org/ctf/enterprise-access-management-sso-drift-incident) and [Policy Drift: Boardroom Breach](https://learn.secbyte.org/ctf/policy-drift-boardroom-breach).
2. **Endpoint & Inventory Drift:** Audit infrastructure health in [Inventory Drift: The Missing Asset](https://learn.secbyte.org/ctf/inventory-drift-the-missing-asset) and [Endpoint Sentinel: GPO Drift & EDR Blindspots](https://learn.secbyte.org/ctf/endpoint-sentinel-gpo-drift-edr-blindspots).

### Path C: Enterprise Security Architecture & Threat Defense Specialist
1. **Architecture & Design:** Review infrastructure boundaries in [Blueprint Breach: Security Architecture Design](https://learn.secbyte.org/ctf/blueprint-breach-security-architecture-design).
2. **Incident Response & Defense:** Analyze complex enterprise attacks in [Enterprise Risk Assessment: Meridian Health Group](https://learn.secbyte.org/ctf/enterprise-risk-assessment-meridian-health-group-incident-re), [Enterprise Network Defense](https://learn.secbyte.org/ctf/enterprise-network-defense-identity-logs-and-lateral-movemen), and [SentinelGrid Breach Simulation](https://learn.secbyte.org/ctf/enterprise-security-sentinelgrid-breach-simulation).

---

## How to Use the Labs

1. Select a practice scenario from the **Lab Collection Index**.
2. Click the corresponding direct link to launch the exercise environment hosted on Learn SecByte.
3. Review scenario directives, Azure sign-in telemetry logs, Active Directory GPO exports, or security architecture diagrams.
4. Audit PIM role activations, trace OAuth token abuse in Azure logs, detect GPO tamper events, analyze lateral movement Kerberos tickets, or evaluate Zero Trust architecture boundaries to capture flags.

---

## Target Audience

* **Enterprise Identity Administrators & Cloud Security Engineers:** Manage Azure/Entra ID PIM policies, audit SAML federation trusts, secure OAuth token flows, and manage SSO access drift.
* **SOC Analysts & Incident Response Teams:** Correlate Active Directory event logs to detect lateral movement, investigate Azure cross-tenant intrusions, and triage EDR coverage blindspots.
* **Security Architects & GRC Managers:** Design Zero Trust enterprise network architectures, conduct post-breach risk assessments, and enforce GPO/policy alignment across large organizations.
* **Cybersecurity Students:** Acquire practical skills in enterprise identity management, Azure security, active directory logging, and operational security drift.

---

## Disclaimer

All lab links provided in this repository direct to official training environments hosted on Learn SecByte. All materials and exercises are provided strictly for educational purposes, defensive skill building, and authorized security research. Unauthorized testing, auditing, or probing against external tenant infrastructure is strictly prohibited.
