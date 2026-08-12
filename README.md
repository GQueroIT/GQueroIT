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

CompTIA Security+ | CompTIA Network+ | Microsoft Azure Fundamentals (AZ-900) | Cisco CCNA Candidate, exam scheduled Oct 24, 2026
IT Field Technician | Systems Administration • Networking • Identity • Cloud • Automation

I build and maintain lab and simulation environments that mirror real enterprise IT operations, then document the actual reasoning, mistakes, and fixes behind them, not just the finished result.

Outside of labs, I support a multi-site healthcare environment (20+ locations) by deploying endpoints, managing assets, resolving incidents, and troubleshooting network connectivity in production.

---

## Start Here

If you're reviewing my work, these projects best demonstrate what I can do:

🔐 **Identity Security with Entra**
Inheriting and securing a real Microsoft Entra ID tenant end to end — Conditional Access, Identity Protection, Privileged Identity Management, and Identity Governance, documented against actual tenant evidence, not a tutorial walkthrough.
https://github.com/GQueroIT/Identity-Security-with-Entra

🌐 **Network Operations Gauntlet**
A CCNA-focused enterprise network built incrementally in Cisco Modeling Labs, with troubleshooting methodology, MTTR tracking, and incident response practice built in alongside exam prep.
https://github.com/GQueroIT/Network-Operations-Gauntlet

🖥️ **Enterprise Active Directory**
Windows Server domain setup, OU structure, GPOs, and AGDLP-based access control.
https://github.com/GQueroIT/Enterprise-Active-Directory

🐍 **Python Network & Cloud Automation**
A self-built curriculum and application for automating Cisco IOS device state collection and Azure resource management with Python.
https://github.com/GQueroIT/Python-Network-Automation-Engineer

---

# Professional Experience

## IT Field Technician
Reforge Tech LLC

- Support clinical and corporate users across 20+ healthcare locations, resolving endpoint, hardware, printer, connectivity, and access issues in active patient-care environments
- Deploy, image, and domain-join Windows endpoints; manage asset records in Asset Panda
- Diagnose Layer 1–3 connectivity issues across patch panels, cabling, and switch ports, escalating ISP and network issues with clear technical evidence
- Support eClinicalWorks environments and hardware refresh/deployment initiatives

## IT Systems Administrator (Work Study)
Empire State University

- Building and administering SharePoint Online and Submittable solutions for a university-wide career services event
- Managing conference planning workflows, form consolidation, and stakeholder-driven redesigns
- Producing implementation documentation detailed enough for another administrator to reproduce the work

---

# Technical Skills

## Identity & Cloud
Microsoft Entra ID · Conditional Access · Identity Protection · Privileged Identity Management (PIM) · Identity Governance · Microsoft Graph API/PowerShell SDK · Azure · Microsoft 365 Admin Center

## Networking
Cisco IOS · VLANs · Inter-VLAN Routing · OSPF · NAT/PAT · TCP/IP · DNS/DHCP · Wireshark · Structured Cabling & Patch Panel Diagnostics

## Infrastructure
Active Directory · Group Policy · Windows Server · Red Hat Enterprise Linux · Ubuntu

## Automation & Programmability
Python · PowerShell · REST/RESTCONF/NETCONF/YANG · pyATS/Genie · Git/GitHub

## Security
Security+ · Splunk (log ingestion & querying) · Authentication Troubleshooting · Access Control · Zero Trust / Least-Privilege Design

## Endpoint & Asset Management
Imaging · Device Deployment · Printer Support · Asset Panda · Hardware Troubleshooting

---

## Featured Work

### Identity Security with Entra
*Microsoft Entra ID · SC-300-aligned*

A simulation of inheriting and securing a real Microsoft Entra ID tenant for a fictional logistics company, built on a live Microsoft 365 developer tenant rather than a sandbox. Every finding and fix happened against real configuration, including deliberately generated risk signals (Tor Browser sign-ins, on-demand Graph API workflow runs) rather than staged results.

- Assessed a tenant with over-broad privileged access, no Conditional Access beyond Microsoft's baseline, and SSPR disabled tenant-wide
- Built role-differentiated Conditional Access policies, activated Entra ID P2 and configured risk-based access, and set up three distinct PIM activation models based on actual role risk
- Closed the loop with access reviews, entitlement management, and Lifecycle Workflows automating onboarding/offboarding
- Documents real mistakes as evidence, not hidden failures — including a sequencing error that revealed how Microsoft auto-deploys managed Conditional Access policies as a safety net

**Status:** Phases 00–07 complete and documented; phases 08–12 (workload identities, incident response, compliance mapping) in progress.
https://github.com/GQueroIT/Identity-Security-with-Entra

---

### Network Operations Gauntlet
*Cisco Modeling Labs (CML) · CCNA 200-301 prep*

A single enterprise network built incrementally over an 11-week study plan using real Cisco IOS virtual devices in CML, rather than isolated one-off labs. Structured around troubleshooting methodology, packet analysis, MTTR tracking, incident response, and change management, not just configuration practice.

- 10-VLAN, two-site topology with a dedicated DMZ, firewall placement, and management VLAN designed upfront
- Tracks Mean Time To Resolution, root cause analysis write-ups, and full ticket lifecycle per incident
- Built to prepare for the CCNA 200-301 exam, scheduled October 24, 2026

**Status:** Early build phase, started August 2026.
https://github.com/GQueroIT/Network-Operations-Gauntlet

---

### Enterprise Active Directory
*Windows Server AD DS*

- Deployed a Windows Server domain with OU structure, DNS, and AGDLP-based role access
- Implemented Group Policy Objects for access control and system configuration
- Diagnosed and resolved DNS-related authentication failures

https://github.com/GQueroIT/Enterprise-Active-Directory

---

### Enterprise Network Infrastructure
*Cisco Packet Tracer*

- Structured, CCNA-aligned labs spanning VLANs, trunking, inter-VLAN routing, OSPF, NAT/PAT, and DNS
- Multi-site enterprise WAN capstone (HQ, Branch, ISP) with OSPF redistribution and documented troubleshooting log

https://github.com/GQueroIT/Enterprise-Network-Infrastructure

---

### Python Network & Cloud Automation
*Python · Cisco IOS · Azure*

A combined curriculum and application: the `learning/` tree is day-by-day instruction, the `network/` and `azure/` trees are where finished lessons become reusable automation tooling.

- Automates multi-device Cisco IOS state collection over SSH, with validation against expected interface/OSPF/routing state
- Covers structured network data via REST/RESTCONF/NETCONF/YANG and pyATS/Genie
- Azure automation phase covers Entra-based authentication and resource inventory/lifecycle management for VNets, NSGs, and VMs
- Built around a read-only-by-default safety model, with configuration changes limited to disposable lab environments

https://github.com/GQueroIT/Python-Network-Automation-Engineer

---

### SharePoint – Pathways to Possibilities
*Real deliverable for Empire State University Career & Experiential Learning Services*

Planning, implementation, and administration record for the digital solutions behind a university-wide career summit (Oct 2026), spanning SharePoint, Submittable, and SUNY Empire Connects.

- Consolidated multiple individual event forms into a unified Call for Proposals with conditional branching by submission type
- Documents the actual stakeholder-review process, including changes made after committee feedback, not just the final state
- Written so another administrator could understand and reproduce every implemented solution

**Status:** Iterative implementation and stakeholder-review phase, ongoing.
https://github.com/GQueroIT/SharePoint-Pathways-to-Possibilities

---

### Linux Network Troubleshooting Case Study
*Ubuntu · Driver Diagnostics*

- Diagnosed a real Wi-Fi failure during Ubuntu deployment, traced to unsupported MediaTek hardware
- Replaced the adapter with an Intel AX210 and documented the full troubleshooting lifecycle

https://github.com/GQueroIT/Linux-Network-Troubleshooting

---

## Certifications

- CompTIA Security+ (SY0-701)
- CompTIA Network+ (N10-009)
- Microsoft Certified: Azure Fundamentals (AZ-900)
- Google IT Support Professional Certificate
- Cisco CCNA 200-301 — Candidate, exam scheduled October 24, 2026
- EPA 608 Universal (HVAC)

---

## Portfolio

GitHub: https://github.com/GQueroIT
LinkedIn: https://linkedin.com/in/gabriel-quero-6678a384

---

## Goal

To grow within systems administration, identity, and network engineering, building toward CCNA and beyond, while contributing to environments that value real hands-on problem solving over theory alone.