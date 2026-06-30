# Lab Architecture

## Overview

The Enterprise SOC Home Lab was designed to simulate a real-world enterprise environment for learning Security Operations Center (SOC) concepts, threat detection, log analysis, and incident response.

---

## Lab Components

| System | Purpose |
|---------|---------|
| Ubuntu Server | Hosts Wazuh Manager |
| Windows Server 2019 | Active Directory Domain Controller |
| Windows 11 | Client Endpoint |
| Sysmon | Advanced Windows Event Logging |
| Wazuh SIEM | Security Monitoring Platform |
| Elasticsearch | Log Storage |
| Kibana | Dashboards and Visualization |
| VMware Workstation | Virtualization Platform |

---

## Data Flow

Windows 11
↓
Sysmon
↓
Wazuh Agent
↓
Wazuh Manager
↓
Elasticsearch
↓
Kibana Dashboard

---

## Learning Objectives

- Build a virtual SOC environment
- Collect Windows Event Logs
- Monitor endpoint activity
- Perform threat hunting
- Analyze security alerts
- Practice incident investigation

---

## Status

✅ Architecture implemented successfully in the home lab.
