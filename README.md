# 🛡️ SOC Home Lab using Splunk Enterprise

> A hands-on Security Operations Center (SOC) Home Lab built using Splunk Enterprise, Sysmon, and Splunk Universal Forwarder for Windows endpoint monitoring and threat detection.

---

## 📌 Project Summary

This project demonstrates how Windows endpoint telemetry can be collected, forwarded, monitored, and investigated using Splunk Enterprise.

The goal was to simulate a real SOC environment and develop practical skills in security monitoring, log analysis, and detection engineering.

---

## 🏗️ Lab Environment

| Component | Purpose |
|----------|---------|
| Windows 11 VM | Endpoint |
| Kali Linux | Testing Machine |
| Sysmon | Endpoint Telemetry |
| Splunk Universal Forwarder | Log Forwarding |
| Splunk Enterprise | SIEM Platform |

---

## 🔍 Monitoring Dashboard

The Monitoring Dashboard provides visibility into:

- Total Events
- Process Creation
- DNS Queries
- Network Connections
- Event Timeline
- Running Processes
- Parent Processes
- PowerShell Activity
- Recent Network Connections

### Screenshots

![Monitoring](monitoring-1.jpeg)

![Monitoring](monitoring-2.jpeg)

![Monitoring](monitoring-3.jpeg)

![Monitoring](monitoring-4.jpeg)

---

## 🚨 Detection Dashboard

Detection rules were created using SPL to identify:

- PowerShell Execution
- Command Prompt Execution
- Encoded PowerShell
- Registry Changes
- File Creation
- DNS Requests
- Network Connections
- Executable Downloads

### Screenshots

![Detection](detection-1.jpeg)

![Detection](detection-2.jpeg)

![Detection](detection-3.jpeg)

---

## 🛠 Skills Gained

- Splunk Enterprise
- SPL Queries
- Sysmon Configuration
- Windows Event Analysis
- SIEM Monitoring
- Detection Engineering
- Threat Hunting Fundamentals

---

## 🚀 Future Improvements

- Active Directory
- Windows Server
- MITRE ATT&CK Mapping
- Splunk Alerts
- Incident Response Playbooks

---

## 👨‍💻 Author

**Firas Saud**

Information Technology Student

Saudi Arabia
