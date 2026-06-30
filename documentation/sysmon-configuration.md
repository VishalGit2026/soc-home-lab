# Sysmon Configuration

## Overview

Sysmon (System Monitor) was deployed on the Windows 11 endpoint to generate detailed system activity logs for security monitoring and threat hunting.

The generated events were forwarded to the Wazuh SIEM platform for centralized monitoring and analysis.

---

# Lab Environment

| Component | Details |
|----------|---------|
| Operating System | Windows 11 |
| Monitoring Tool | Sysmon |
| SIEM Platform | Wazuh |
| Visualization | Kibana Dashboard |

---

# Objectives

- Capture detailed Windows events
- Monitor process creation
- Detect network connections
- Monitor file creation activities
- Improve endpoint visibility

---

# Important Sysmon Events

| Event ID | Description |
|----------|-------------|
| 1 | Process Creation |
| 3 | Network Connection |
| 5 | Process Terminated |
| 11 | File Create |
| 13 | Registry Value Set |

---

# Configuration

Sysmon was installed using the SwiftOnSecurity configuration file to provide enhanced visibility into Windows endpoint activities.

The generated events were collected by Wazuh for security monitoring.

---

# Learning Outcomes

- Understood Sysmon architecture
- Learned endpoint monitoring
- Generated Windows security telemetry
- Forwarded Sysmon logs to Wazuh SIEM

---

# Status

✅ Sysmon successfully configured and monitored in the Enterprise SOC Home Lab.
