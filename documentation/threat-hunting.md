# Threat Hunting

## Overview

Threat hunting is the proactive process of searching for indicators of compromise (IOCs), suspicious activities, and potential threats within an organization's environment.

---

## Objective

The objective of this lab is to practice identifying malicious activities using Wazuh SIEM, Sysmon, Windows Event Logs, and the MITRE ATT&CK Framework.

---

## Tools Used

- Wazuh SIEM
- Sysmon
- Windows Event Viewer
- Kibana
- MITRE ATT&CK Framework

---

## Threat Hunting Activities

- Monitor Windows Event Logs
- Detect failed login attempts
- Identify suspicious process creation
- Analyze PowerShell execution
- Monitor network connections
- Detect privilege escalation attempts

---

## Event IDs Monitored

| Event ID | Description |
|----------|-------------|
| 4624 | Successful Logon |
| 4625 | Failed Logon |
| 4688 | Process Creation |
| 4720 | User Account Created |
| 4732 | User Added to Privileged Group |

---

## Learning Outcome

- Improved understanding of Windows Event Logs
- Learned to investigate suspicious activities
- Practiced threat hunting techniques using SIEM

---

## Status

✅ Threat hunting exercises completed successfully.
