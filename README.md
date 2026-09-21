# Gabriel Quero

---

<p align="left">
  <img src="https://img.shields.io/badge/CompTIA-Security%2B-red?logo=comptia&logoColor=white" />
  <img src="https://img.shields.io/badge/CompTIA-Network%2B-red?logo=comptia&logoColor=white" />
  <img src="https://img.shields.io/badge/Microsoft-AZ--900-blue?logo=microsoft&logoColor=white" />
  <img src="https://img.shields.io/badge/Cisco-CCNA%20Candidate-1BA0D7?logo=cisco&logoColor=white" />
  <img src="https://img.shields.io/badge/Active%20Directory-AD%20DS-003366?logo=windows&logoColor=white" />
  <img src="https://img.shields.io/badge/Microsoft-Entra%20ID-0078D4?logo=microsoftazure&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-Ubuntu%20%7C%20RHEL-E95420?logo=linux&logoColor=white" />
</p>

---

CompTIA Security+ | CompTIA Network+ | Microsoft Azure Fundamentals (AZ-900) | Cisco CCNA Candidate, exam scheduled Dec. 13, 2026

**Cybersecurity • Networking • Identity • Cloud • Infrastructure**

I work across cybersecurity and IT infrastructure in production environments while continuing to build deeper skills in networking, cloud, identity, Linux, and automation.

At Empire State University, I support cybersecurity operations using Tenable and Microsoft Defender. My responsibilities include evaluating vulnerability data through CSV analysis and assisting with phishing-related security activities.

I also support a multi-site healthcare environment spanning 20+ locations, where I deploy endpoints, troubleshoot Layer 1–3 connectivity, manage assets, and resolve technical issues in active patient-care environments.

My projects extend that production experience into Azure governance, Microsoft Entra ID, enterprise networking, Active Directory, and Linux. I document the technical decisions, troubleshooting, mistakes, and fixes behind the finished environment rather than presenting only the final configuration.

---

## Start Here

If you're reviewing my work, these projects best demonstrate what I can do:

### ☁️ Azure Governance Guardrails – 52 Logistics

Designed and deployed a repeatable Azure governance and security baseline using Terraform and PowerShell. The environment implements RBAC, Azure Policy, resource locks, Defender for Cloud, and automated validation to control how Azure resources are deployed and managed.

The project goes beyond deploying controls by testing whether those controls actually work, including independent validation, configuration-drift detection, CI/CD with GitHub Actions, and documented evidence of enforcement.

https://github.com/GQueroIT/Azure-Governance-Guardrails-52Logistics

### 🔐 Identity Security with Entra

Inheriting and securing a Microsoft Entra ID tenant end to end — Conditional Access, Identity Protection, Privileged Identity Management, and Identity Governance, documented against actual tenant evidence rather than a tutorial walkthrough.

https://github.com/GQueroIT/Identity-Security-with-Entra

### 🌐 Network Operations Gauntlet

A CCNA-focused enterprise network built incrementally in Cisco Modeling Labs, with troubleshooting methodology, MTTR tracking, and incident-response practice incorporated alongside routing and switching development.

https://github.com/GQueroIT/Network-Operations-Gauntlet

### 🖥️ Enterprise Active Directory

Windows Server domain deployment covering OU architecture, DNS, Group Policy, and AGDLP-based access control, including troubleshooting and resolution of DNS-related authentication failures.

https://github.com/GQueroIT/Enterprise-Active-Directory

---

# Professional Experience

## Cybersecurity Work-Study

**Empire State University**  
June 2026 – Present

- Support vulnerability management activities using Tenable, reviewing vulnerability scan data and evaluating CSV exports to identify and document findings
- Use Microsoft Defender to support security monitoring and investigation of endpoint and user security events
- Assist with phishing-related security activities by evaluating suspicious messages and indicators of potential phishing attempts
- Analyze vulnerability and security data to document findings and support remediation efforts
- Build and administer SharePoint Online and Submittable solutions for a university-wide career services event
- Manage conference planning workflows, form consolidation, and stakeholder-driven redesigns
- Produce implementation documentation detailed enough for another administrator to reproduce the work

## IT Field Technician

**Reforge Tech LLC**

- Support clinical and corporate users across 20+ healthcare locations, resolving endpoint, hardware, printer, connectivity, and access issues in active patient-care environments
- Deploy, image, and domain-join Windows endpoints; manage asset records in Asset Panda
- Diagnose Layer 1–3 connectivity issues across patch panels, cabling, and switch ports, escalating ISP and network issues with clear technical evidence
- Support eClinicalWorks environments and hardware refresh/deployment initiatives

---

# Technical Skills

## Security

Tenable · Microsoft Defender · Vulnerability Management · Vulnerability Assessment · Phishing Analysis · Security Alert Investigation · Splunk (log ingestion & querying) · Access Control · Zero Trust / Least-Privilege Design

## Identity & Cloud

Microsoft Entra ID · Conditional Access · Identity Protection · Privileged Identity Management (PIM) · Identity Governance · Microsoft Graph API/PowerShell SDK · Azure · Microsoft 365 Admin Center

## Networking

Cisco IOS · VLANs · Inter-VLAN Routing · OSPF · NAT/PAT · TCP/IP · DNS/DHCP · Wireshark · Structured Cabling & Patch Panel Diagnostics

## Infrastructure

Active Directory · Group Policy · Windows Server · Red Hat Enterprise Linux · Ubuntu

## Automation & Programmability

Python · PowerShell · Terraform · Git/GitHub · GitHub Actions

## Endpoint & Asset Management

Imaging · Device Deployment · Printer Support · Asset Panda · Hardware Troubleshooting

---

# Featured Work

## Azure Governance Guardrails – 52 Logistics

**Azure · Terraform · PowerShell · GitHub Actions**

A governance and security baseline designed to control how Azure resources are deployed and managed while providing evidence that the implemented controls function as intended.

The project was structured around several operational questions:

- Who is allowed to manage Azure resources?
- Where does that access apply?
- What resources are users allowed to deploy?
- How are critical resources protected from accidental deletion?
- What happens if someone removes a governance control?
- Can configuration drift be detected and corrected?
- Can the deployed governance baseline be independently validated?

Implementation includes:

- Infrastructure and governance controls deployed through Terraform
- Role-Based Access Control (RBAC) to define administrative boundaries
- Azure Policy to enforce resource requirements
- Resource locks to protect critical infrastructure
- Microsoft Defender for Cloud security controls
- PowerShell-based validation
- Configuration-drift testing
- CI/CD and automated validation using GitHub Actions
- Evidence collection documenting whether implemented controls behaved as expected
- Architecture and implementation documentation designed to make the environment reproducible

https://github.com/GQueroIT/Azure-Governance-Guardrails-52Logistics

---

## Identity Security with Entra

**Microsoft Entra ID · SC-300-aligned**

A simulation of inheriting and securing a real Microsoft Entra ID tenant for a fictional logistics company, built on a live Microsoft 365 developer tenant rather than a sandbox. Findings and fixes were performed against real configuration, including deliberately generated risk signals rather than staged results.

- Assessed a tenant with over-broad privileged access, limited Conditional Access coverage, and SSPR disabled tenant-wide
- Built role-differentiated Conditional Access policies, activated Entra ID P2, and configured risk-based access
- Configured three PIM activation models based on role risk
- Implemented access reviews, entitlement management, and Lifecycle Workflows for identity lifecycle management
- Documented configuration mistakes and unexpected platform behavior as part of the technical evidence rather than hiding failed attempts

**Status:** Phases 00–07 complete and documented; additional workload identity, incident response, and compliance work in progress.

https://github.com/GQueroIT/Identity-Security-with-Entra

---

## Network Operations Gauntlet

**Cisco Modeling Labs (CML) · CCNA 200-301**

A single enterprise network built incrementally using Cisco IOS virtual devices in CML rather than isolated one-off labs. The project combines CCNA development with troubleshooting methodology, packet analysis, incident documentation, and change management.

- Designed a multi-VLAN enterprise topology with Layer 2 and Layer 3 switching, routing, management segmentation, and edge connectivity
- Implemented VLANs, 802.1Q trunks, EtherChannel, Rapid PVST+, HSRP, and Layer 3 inter-switch connectivity
- Built redundant distribution and access-layer paths while intentionally observing STP behavior and failover
- Integrated routing and edge connectivity while troubleshooting end-to-end reachability
- Track Mean Time to Resolution (MTTR), root cause analysis, and troubleshooting methodology during incidents
- Use the environment as an evolving platform for CCNA study rather than rebuilding isolated topologies for individual topics

**Status:** Active build and CCNA study environment.

https://github.com/GQueroIT/Network-Operations-Gauntlet

---

## Enterprise Active Directory

**Windows Server · Active Directory Domain Services**

- Deployed a Windows Server domain with structured Organizational Units, DNS, and centralized identity management
- Implemented AGDLP-based role access to separate users, global groups, domain local groups, and resource permissions
- Created Group Policy Objects for access control and system configuration
- Diagnosed and resolved DNS-related authentication failures affecting domain functionality

https://github.com/GQueroIT/Enterprise-Active-Directory

---

## Enterprise Network Infrastructure

**Cisco Packet Tracer**

- Built structured CCNA-aligned labs covering VLANs, trunking, inter-VLAN routing, OSPF, NAT/PAT, DHCP, and DNS
- Designed a multi-site enterprise WAN capstone connecting headquarters, branch, and ISP infrastructure
- Implemented dynamic routing and documented troubleshooting during connectivity failures
- Used packet-level and device-level verification to validate network behavior rather than relying only on successful pings

https://github.com/GQueroIT/Enterprise-Network-Infrastructure

---

## SharePoint – Pathways to Possibilities

**Real Deliverable for Empire State University Career & Experiential Learning Services**

Planning, implementation, and administration record for the digital solutions supporting a university-wide career summit in October 2026, spanning SharePoint, Submittable, and SUNY Empire Connects.

- Consolidated multiple individual event forms into a unified Call for Proposals with conditional branching by submission type
- Built and refined solutions through an actual stakeholder-review process
- Documented changes made after committee feedback rather than presenting only the final implementation
- Produced documentation so another administrator can understand and reproduce the implemented solutions

**Status:** Iterative implementation and stakeholder-review phase, ongoing.

https://github.com/GQueroIT/SharePoint-Pathways-to-Possibilities

---

## Linux Network Troubleshooting Case Study

**Ubuntu · Linux · Driver Diagnostics**

- Diagnosed a real Wi-Fi failure during an Ubuntu deployment and isolated the issue to unsupported MediaTek hardware
- Replaced the adapter with an Intel AX210 and verified Linux compatibility
- Documented the troubleshooting lifecycle from symptoms and hypothesis through hardware replacement and validation

https://github.com/GQueroIT/Linux-Network-Troubleshooting

---

# Certifications

- CompTIA Security+ (SY0-701)
- CompTIA Network+ (N10-009)
- Microsoft Certified: Azure Fundamentals (AZ-900)
- Google IT Support Professional Certificate
- Cisco CCNA 200-301 — Candidate, exam scheduled Dec. 13, 2026
- EPA 608 Universal (HVAC)

---

# Education

**Empire State University**  
Bachelor of Science in Information Technology  
In Progress

**Empire State University**  
Associate of Science in General Studies 
Complete

---

# Portfolio

GitHub: https://github.com/GQueroIT

LinkedIn: https://linkedin.com/in/gabriel-quero-6678a384

---

# Current Focus

I am currently developing deeper skills across cybersecurity, networking, and cloud infrastructure while working toward the Cisco CCNA.

My focus is on understanding how these areas connect in real environments: how networks are designed and troubleshot, how identities and access are secured, how cloud infrastructure is governed, and how security teams identify and respond to risk.

The goal is to keep building the technical depth needed to move into roles where networking, cloud infrastructure, and security intersect.