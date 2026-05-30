# Homelab
![Status](https://img.shields.io/badge/status-active-brightgreen)
![Phase](https://img.shields.io/badge/current_phase-00_--_lab_environment_setup-blue)
![Last Commit](https://img.shields.io/github/last-commit/jonahplourde/homelab)
![License](https://img.shields.io/badge/license-CC%20BY--NC--ND%204.0-lightgrey)


## I. OVERVIEW
The lab host is running EndeavourOS with KVM/QEMU and virt-manager configured. Six VMs are staged for deployment: a pfSense firewall, Windows Server 2025 domain controller, Windows 11 Pro endpoint, Ubuntu Server running Splunk, a Kali attack platform, and a Metasploitable2 target.

The lab will progress through four structured phases. Each phase will inherit from the one prior.

1. Phase 01 will establish core infrastructure
    - Networking
    - Directory services
    - General endpoint management
    
2. Phase 02 will build security operations on top of that foundation:
    - SIEM deployment
    - Detection engineering
    - Incident response
    - Threat intelligence
    
3. Phase 03 will cover cloud and infrastructure engineering:
    - IaC
    - Containerization
    - DevSecOps
    
4. Phase 04 will address security governance:
    - Policy
    - Risk management
    - Compliance


## II. STATUS
`PHASE 00 — Lab Environment` in progress — host OS and hypervisor configured. VM deployment underway.


## III. QUICK NAVIGATION
| Phase | Domain | Description |
|---|---|---|
| 00 | Lab environment | Hardware, network design, VM inventory |


## IV. ENVIRONMENT
| Component | Specs |
|---|---|
| Host OS | EndeavourOS |
| Hypervisor | KVM/QEMU via virt-manager |
| CPU | Intel Core i9-275HX, 24 cores |
| RAM | 32GB |
| Disk | 2TB SSD |
| GPU | RTX 5060 |


## V. VM STACK
| VM | OS | Role |
|---|---|---|
| pfsense | pfSense | Firewall and network gateway |
| winserver | Windows Server 2025 | Domain controller and AD DS |
| win11 | Windows 11 Pro | Endpoint |
| ubuntu | Ubuntu Server | Splunk SIEM |
| kali | Kali Linux | Attack platform |
| meta2 | Metasploitable2 | Vulnerable target |
