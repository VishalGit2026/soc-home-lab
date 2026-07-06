# Windows Security Event IDs

## Overview

Windows Security Event IDs are essential for detecting suspicious activities, investigating incidents, and monitoring endpoint security within the SOC Home Lab.

---

# Authentication Events

| Event ID | Description |
|----------|-------------|
| 4624 | Successful Logon |
| 4625 | Failed Logon |
| 4634 | Logoff |
| 4648 | Logon with Explicit Credentials |

---

# Account Management

| Event ID | Description |
|----------|-------------|
| 4720 | User Account Created |
| 4722 | User Account Enabled |
| 4725 | User Account Disabled |
| 4726 | User Account Deleted |
| 4732 | User Added to Privileged Group |

---

# Process Monitoring

| Event ID | Description |
|----------|-------------|
| 4688 | Process Creation |
| 4689 | Process Termination |

---

# Sysmon Events

| Event ID | Description |
|----------|-------------|
| 1 | Process Creation |
| 3 | Network Connection |
| 5 | Process Terminated |
| 11 | File Created |
| 13 | Registry Value Modified |

---

# Usage in SOC

These Event IDs were monitored in the Enterprise SOC Home Lab using:

- Wazuh SIEM
- Kibana Dashboard
- Windows Event Viewer
- Sysmon

---

# Learning Outcome

- Learned Windows Event Monitoring
- Investigated authentication events
- Monitored endpoint activities
- Practiced log analysis

---

# Status

✅ Windows Event IDs documented successfully.
