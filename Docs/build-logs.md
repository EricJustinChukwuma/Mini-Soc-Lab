# Mini SOC Build Log

## Project Overview

This document records the build process for my Mini Security Operations Centre (SOC) lab.

The purpose of the lab is to gain hands-on experience with:

- SIEM deployment and administration
- Endpoint monitoring
- Windows security telemetry
- Detection engineering
- Log analysis
- Incident investigation
- MITRE ATT&CK mapping
- Incident response
- Technical documentation

The lab is being built using VMware Workstation Pro and Wazuh.

---

# Phase 1 - Project Setup

## GitHub Repository


#

Created a GitHub repository named:

`mini-soc-lab`

The repository is being used to document the lab build, detection rules, investigations, screenshots, and incident reports.

Initial project structure:

```text
mini-soc-lab/
│
├── README.md
├── architecture/
├── detections/
├── docs/
│   └── build-log.md
├── incident-reports/
├── investigations/
├── screenshots/
└── scripts/ 

# Phase 3 - Windows Endpoint Deployment

## Endpoint

Created a Windows 11 virtual machine in VMware Workstation Pro.

### Configuration

- Hostname/Endpoint: SOC-WIN11-01
- Operating System: Windows 11
- Network: VMware NAT
- Wazuh Manager/Server: SOC-WAZUH-01

## Network Validation

Confirmed that the Windows endpoint could communicate with the
Wazuh manager.

Wazuh agent communication and enrollment ports were tested using:

  powershell
Test-NetConnection 192.168.133.210 -Port 1514
Test-NetConnection 192.168.133.210 -Port 1515