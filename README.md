# Building and Operating a Mini SOC

## Objective

The objective of this project is to build a small Security Operations
Centre lab that demonstrates practical experience with security monitoring,
endpoint telemetry, detection engineering, incident investigation and
incident response.

## Lab Goals

- Deploy a SIEM/security monitoring platform
- Collect Windows endpoint telemetry
- Implement Sysmon logging
- Generate controlled security events
- Investigate security alerts
- Develop and tune detection rules
- Map relevant activity to MITRE ATT&CK
- Produce professional incident reports

## Technologies

- Wazuh
- Windows 11
- Ubuntu Server
- Sysmon
- Virtualization platform
- Git/GitHub

## Architecture

Architecture diagram to be added.

## Investigations

Investigations will be documented as the lab is developed.

## Skills Demonstrated

- SIEM
- Log analysis
- Windows security monitoring
- Detection engineering
- Incident response
- MITRE ATT&CK
- Technical documentation

## Phase 2 - Wazuh SIEM Deployment

Deployed a Wazuh all-in-one SIEM server on Ubuntu Server.

### Configuration

- Hostname: soc-wazuh-01
- 4 vCPU
- 8 GB RAM
- 60 GB virtual disk
- VMware NAT networking

### Wazuh Components

- Wazuh Manager
- Wazuh Indexer
- Wazuh Dashboard

All three Wazuh services were verified as active and running.
The Wazuh dashboard was successfully accessed from the host workstation.
