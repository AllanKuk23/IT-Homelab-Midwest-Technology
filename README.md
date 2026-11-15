
# IT Homelab | Midwest Technology

### Windows Server 2022 | Hyper-V | Active Directory | Enterprise Networking

## Project Overview

I created a homelab to simulate a small business environment and named it Midwest Technology. I was interested in how an actual IT infrastructure works and this was a great way for me to build practical experience with Windows Server, virtualization, networking, and system administration.

Using Windows Server 2022 and Hyper-V, I built a simulated small-business environment where I can configure and manage servers, Active Directory, network services, user accounts, and security policies.

My goal is to apply what I am learning in school to real-world IT scenarios, improve my troubleshooting skills, and document my progress as I work toward a career in IT support and network administration.

---

# 👇 Start Here | Click a Colored Phase Below to Explore 👇

Each phase contains documentation, configuration details, verification steps, screenshots, and lessons learned as the project develops.


<a href="./Phase-01-Infrastructure/README.md"><img src="https://img.shields.io/badge/01-Infrastructure-2879CF?style=for-the-badge" height="40" alt="Phase 01 Infrastructure"></a>
<a href="./Phase-02-Business-Environment/README.md"><img src="https://img.shields.io/badge/02-Business%20Environment-238750?style=for-the-badge" height="40" alt="Phase 02 Business Environment"></a>
<a href="./Phase-03-Group-Policy-Security/README.md"><img src="https://img.shields.io/badge/03-Group%20Policy%20%26%20Security-8555BC?style=for-the-badge" height="40" alt="Phase 03 Group Policy and Security"></a>
<a href="./Phase-04-Monitoring-AI/README.md"><img src="https://img.shields.io/badge/04-Monitoring%20%26%20AI-CB8A21?style=for-the-badge" height="40" alt="Phase 04 Monitoring and AI"></a>
<a href="./Phase-05-Backup-Recovery/README.md"><img src="https://img.shields.io/badge/05-Backup%20%26%20Recovery-CA514D?style=for-the-badge" height="40" alt="Phase 05 Backup and Recovery"></a>
<a href="./Phase-06-Secure-Remote-Access/README.md"><img src="https://img.shields.io/badge/06-Secure%20Remote%20Access-778394?style=for-the-badge" height="40" alt="Phase 06 Secure Remote Access"></a>

**Quick Navigation**

- [Current Infrastructure](#current-infrastructure)
- [Technologies and Hardware](#technologies-and-hardware)
- [Project Progress](#project-progress)
- [Documentation and Evidence](#documentation-and-evidence)

*Phase documentation links will become active as their folders and README files are added.*

---

## Current Infrastructure

My homelab runs Windows Server 2022 Standard on a physical computer configured with the Hyper-V role. The physical host runs virtual machines used to simulate a small-business network.

**Current verified environment:**

- **LAB-HV1:** Physical Windows Server 2022 host running Hyper-V
- **DC1:** Windows Server 2022 virtual machine providing Active Directory Domain Services and DNS
- **CLIENT1:** Windows 11 virtual machine used for domain and workstation testing
- **ALLANPC:** Windows 11 Pro workstation used for remote administration
- **Domain:** lab.local
- **Networking:** External Hyper-V virtual switch connected to the existing home network

DC1 holds all five FSMO roles following migration of domain controller services from the original physical server. DHCP services are currently inactive to prevent conflicts with the home router.

The next infrastructure milestone is to create an isolated virtual network with its own addressing, NAT, and DHCP services.

---

## Technologies and Hardware

**Technologies**

- Windows Server 2022
- Hyper-V virtualization
- Active Directory Domain Services
- DNS and DHCP
- Windows 11
- Remote Desktop
- Group Policy (planned)
- Cisco switching and VLANs (planned)
- Zabbix monitoring (planned)
- Backup and disaster recovery (planned)

**Physical Homelab Server**

- AMD Ryzen 5 5500
- 16 GB DDR4 RAM
- 256 GB NVMe SSD
- Windows Server 2022 Standard

**Additional Equipment**

- Cisco Catalyst 2960 switch
- Windows 11 Pro administration workstation

---

## Project Progress


| Phase | Focus | Status |
|---|---|---|
| ![01](https://img.shields.io/badge/01-Infrastructure-2879CF?style=flat-square) | Infrastructure, Hyper-V, AD DS, DNS, DHCP and Network Isolation | ![In Progress](https://img.shields.io/badge/Status-In%20Progress-2879CF?style=flat-square) |
| ![02](https://img.shields.io/badge/02-Business%20Environment-238750?style=flat-square) | Business Environment, File Services and Departmental VLANs | ![Planned](https://img.shields.io/badge/Status-Planned-777777?style=flat-square) |
| ![03](https://img.shields.io/badge/03-Group%20Policy%20%26%20Security-8555BC?style=flat-square) | Group Policy and Security | ![Planned](https://img.shields.io/badge/Status-Planned-777777?style=flat-square) |
| ![04](https://img.shields.io/badge/04-Monitoring%20%26%20AI-CB8A21?style=flat-square) | Monitoring and AI | ![Planned](https://img.shields.io/badge/Status-Planned-777777?style=flat-square) |
| ![05](https://img.shields.io/badge/05-Backup%20%26%20Recovery-CA514D?style=flat-square) | Backup and Disaster Recovery | ![Planned](https://img.shields.io/badge/Status-Planned-777777?style=flat-square) |
| ![06](https://img.shields.io/badge/06-Secure%20Remote%20Access-778394?style=flat-square) | Secure Remote Access | ![Planned](https://img.shields.io/badge/Status-Planned-777777?style=flat-square) |
  

---

## Documentation and Evidence

I am documenting each phase with:

- Project objectives and implementation steps
- Configuration explanations
- Verification and testing results
- Screenshots from my actual homelab
- Troubleshooting notes and lessons learned

This repository will continue to develop as I complete additional infrastructure, networking, security, and administration projects.

## Project Status

**Status: Currently In Progress**

I'm still working on building and improving this homelab as I continue learning more about IT. As I complete new configurations and projects, I'll be updating this repository with screenshots, documentation, and what I've learned along the way.

Some parts of the homelab are already up and running, while others are still being worked on. I'll continue adding to this project as I gain more hands-on experience.
