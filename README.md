# 🛡️ SOC Home Lab

A practical Security Operations Center (SOC) Home Lab built to simulate real-world security monitoring using **Splunk Enterprise**, **Sysmon**, and **Splunk Universal Forwarder**.

This project focuses on Windows endpoint visibility, log collection, dashboard development, and custom detection rules using SPL.

---

# 📖 Project Overview

This lab demonstrates how Windows security events can be collected, forwarded, and analyzed in Splunk.

The environment includes:

- Windows 11 Virtual Machine
- Kali Linux
- Splunk Enterprise
- Splunk Universal Forwarder
- Sysmon

---

# 🏗️ Lab Architecture

```text
                 Kali Linux
                      │
                      │
        (Attack / Testing Machine)
                      │
                      ▼
           Windows 11 Virtual Machine
                + Sysmon Installed
                      │
                      ▼
       Splunk Universal Forwarder
                      │
                      ▼
            Splunk Enterprise SIEM
          ┌────────────────────────┐
          │ Monitoring Dashboard   │
          │ Detection Dashboard    │
          └────────────────────────┘
```

---

# ⚙️ Technologies Used

- Splunk Enterprise
- Splunk Universal Forwarder
- Sysmon
- Windows Event Logs
- SPL (Search Processing Language)
- Windows 11
- Kali Linux

---

# 📊 Monitoring Dashboard

The monitoring dashboard provides visibility into:

- Total Events
- Process Creation
- DNS Queries
- Network Connections
- Event Timeline
- Network Timeline
- Running Processes
- Destination Ports
- Connected Processes
- Parent Processes
- PowerShell & CMD Activity
- DNS Activity
- Recent Network Connections

---

## Dashboard Screenshots

### Monitoring Dashboard

![Monitoring 1](monitoring-1.jpeg)

![Monitoring 2](monitoring-2.jpeg)

![Monitoring 3](monitoring-3.jpeg)

![Monitoring 4](monitoring-4.jpeg)

---

# 🚨 Detection Dashboard

Custom detection rules were created for:

- PowerShell Execution
- Command Prompt Execution
- Encoded PowerShell
- Registry Persistence
- File Creation
- DNS Requests
- Network Connections
- Executable Downloads

---

## Detection Screenshots

![Detection 1](detection-1.jpeg)

![Detection 2](detection-2.jpeg)

![Detection 3](detection-3.jpeg)

---

# 🎯 Skills Demonstrated

- SIEM Monitoring
- Windows Event Analysis
- Threat Detection
- Log Collection
- Sysmon Configuration
- SPL Query Development
- Dashboard Development
- Security Monitoring
- Blue Team Fundamentals

---

# 📌 Future Improvements

- Windows Server
- Active Directory
- MITRE ATT&CK Mapping
- Splunk Alerts
- Threat Hunting Dashboard
- Detection Engineering

---

# 👨‍💻 Author

**Firas Saud**

Information Technology Student

Interested in SOC • Blue Team • Cybersecurity
