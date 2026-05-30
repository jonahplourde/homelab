# Homelab
![Status](https://img.shields.io/badge/status-active-brightgreen)
![Phase](https://img.shields.io/badge/current_phase-00_--_lab_environment_setup-blue)
![Last Commit](https://img.shields.io/github/last-commit/jonahplourde/homelab)
![License](https://img.shields.io/badge/license-CC%20BY--NC--ND%204.0-lightgrey)


## I. OVERVIEW
This lab simulates a simplified enterprise environment built and operated by a single engineer. It covers topics from simple troubleshooting and helpdesk functions to network infrastructure and directory services through security operations to cloud engineering to governance.

The environment is built on KVM/QEMU on EndeavourOS, with a VM stack that mirrors a small enterprise network: a pfSense firewall handling segmentation and routing, Windows Server 2025 running Active Directory, a Splunk SIEM ingesting logs across the environment, and a dedicated attack platform paired with a vulnerable target for simulated adversarial activity.

Each phase of the lab builds on the last. Infrastructure decisions made in Phase 01 are inherited by the security operations work in Phase 02. Detection rules written in Phase 02 are tested against real simulated attacks. Governance documentation in Phase 04 reflects the actual environment, not a hypothetical one. The result is a body of work that demonstrates how these disciplines connect in practice rather than in isolation.


## II. STATUS
`PHASE 00 — Lab Environment` in progress — host OS and hypervisor configured. VM deployment underway.


## III. QUICK NAVIGATION
| Phase | Domain | Description |
|---|---|---|
| 00 -- Lab Environment | Hardware, network design, VM inventory |


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
| meta2 | Metasploitable | Vulnerable target |
