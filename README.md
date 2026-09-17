### Kyle Budd
*Aspiring IT/Cybersecurity Professional — Omni Lead @ Dick's Sporting Goods*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Kyle_Budd-blue)](https://www.linkedin.com/in/kyle-budd-7b8130424)
[![CompTIA Security+](https://img.shields.io/badge/CompTIA_Security+-In_Progress-orange)]()

---

> **Portfolio Note**
> I'm transitioning from a retail operations background into IT/cybersecurity. This portfolio documents the hands-on systems I'm building to develop and prove real skills — Active Directory administration, help desk ticketing workflows, LDAP integration, SIEM monitoring, and hybrid identity — while I work toward CompTIA Security+.

## Home Lab — Active Directory & Help Desk Infrastructure

| Project | Notes | Stack | Status |
|---|---|---|---|
| [Active Directory Domain Setup](https://github.com/thekyletechnique/Kyles-IT-Home-Lab) | Built a DC (Windows Server 2022) and joined a Windows 11 client to the domain. [Watch the full video walkthrough](https://www.youtube.com/). | VMware Workstation · Windows Server 2022 · AD DS | ![status](https://img.shields.io/badge/status-Complete-brightgreen) |
| osTicket Help Desk Deployment | Deployed a ticketing system on Ubuntu Server as a help desk simulation. | Ubuntu Server 24.04 · osTicket | ![status](https://img.shields.io/badge/status-Complete-brightgreen) |
| osTicket ↔ Active Directory (LDAP) Integration | Integrated ticketing auth with AD via LDAP; resolved network/firewall connectivity between hosts; ran a full ticket lifecycle end-to-end. | AD · LDAP · Windows Firewall | ![status](https://img.shields.io/badge/status-Complete-brightgreen) |
| [SIEM Deployment (Wazuh)](https://github.com/thekyletechnique/Kyles-IT-Home-Lab/blob/main/SIEM-Wazuh.md) | Deployed Wazuh (manager, indexer, dashboard) to monitor the AD and osTicket environment in real time; deployed agents to a Windows domain controller and a Linux server; validated with a live detection scenario — failed logon attempts parsed, classified, and surfaced in the dashboard within seconds. | Wazuh · Ubuntu Server · Windows Server 2022 · netplan/LVM troubleshooting | ![status](https://img.shields.io/badge/status-Complete-brightgreen) |
| Hybrid Identity (Microsoft Entra ID) | Connecting the on-premises AD domain to Microsoft Entra ID via hybrid sync; plans to layer in Conditional Access and feed Entra sign-in/audit logs into the existing Wazuh SIEM. | Microsoft Entra Connect · Entra ID · Conditional Access | ![status](https://img.shields.io/badge/status-In_Progress-orange) |

> **Focus area:** Simulating a small business IT environment end-to-end — domain services, client management, help desk ticketing, security monitoring, and hybrid identity — to build practical troubleshooting and sysadmin/security experience.

---

## Scripting & Automation Projects

| Project | Notes | Stack |
|---|---|---|
| AI YouTube Automation Agent | Multi-agent Python pipeline: trend research, scripting, voiceover, video assembly, thumbnail generation, upload, analytics | Python · FFmpeg · ElevenLabs · DALL-E 3 · YouTube API |

> **Focus area:** Independent project demonstrating Python scripting, API integration, and automation of multi-step workflows — skills that carry directly into IT automation and security tooling.

---

## Certifications

**In Progress**

[![CompTIA Security+](https://img.shields.io/badge/CompTIA_Security+-In_Progress-orange)]()

---

[Connect on LinkedIn](https://www.linkedin.com/in/kyle-budd-7b8130424)
