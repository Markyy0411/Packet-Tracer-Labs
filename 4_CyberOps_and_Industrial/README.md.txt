# 🖥️ Virtual Machine Environment Setup

This document outlines the local VirtualBox infrastructure used to execute the Cybersecurity, CyberOps, and Network Administration laboratory exercises in this repository. 

The environment includes customized penetration testing distributions, dedicated network monitoring tools, vulnerable target machines, and official Cisco NetAcad workstations.

## 🛡️ CyberOps & Network Monitoring

- CyberOps Security Onion
  - RAM: 4096 MB
  - Storage: 20.00 GB (.vdi)
  - Network: Dual Adapters (Internal Network 'dmz')

- Security Onion (Standard)
  - RAM: 4096 MB
  - Storage: 20.00 GB (.vdi)
  - Network: NAT

## 🗡️ Ethical Hacking & Penetration Testing

- Kali Linux (2025.2 Clone)
  - RAM: 4096 MB
  - Storage: 50.00 GB (.vdi)
  - Network: NAT
  - Purpose: Dedicated environment for practicing ethical hacking.

- Parrot OS (7.1 KDE Security Edition)
  - RAM: 4096 MB
  - Storage: 64.00 GB (.vdi)
  - Network: NAT

- BlackArch
  - RAM: 4096 MB
  - Storage: 80.00 GB (.vdi)
  - Network: Internal Network ('CyberLab')

## 🎯 Vulnerable Target Machines

- Metasploitable2
  - RAM: 2048 MB
  - Storage: 8.00 GB (.vmdk)
  - Network: NAT

- OWASP-BWA (Broken Web Apps)
  - RAM: 1024 MB
  - Storage: 8.00 GB (.vmdk)
  - Network: NAT

## 💻 Cisco Networking Academy Workstations

- DEVASC-LABVM
  - RAM: 4096 MB
  - Storage: 31.25 GB (.vdi)
  - Network: NAT
  - Description: Official Cisco NetAcad Lab VM for the DevNet Associate course.

- Cybersecurity LabVM Workstations (20230210 & 20250409)
  - RAM: 2048 MB (Each)
  - Storage: 23.44 GB (.vdi) (Each)

## 🖧 Infrastructure & Endpoints

- pfSense Router
  - RAM: 1024 MB
  - Network: Adapter 1 (Bridged), Adapter 2 (Internal Network 'LAN')

- Windows 7 Client
  - RAM: 4096 MB
  - Storage: 32.00 GB (.vdi)
  - Network: NAT

- NAS-Final-Project
  - RAM: 2048 MB
  - Storage: 26.21 GB (.vdi)
  - Network: NAT