# SOC Home Lab

## Overview

This project demonstrates a Security Operations Center (SOC) Home Lab built using Splunk Enterprise, Sysmon, and Splunk Universal Forwarder to collect, monitor, and analyze Windows security events.

---

## Lab Architecture

- Windows 11 Virtual Machine
- Kali Linux
- Splunk Enterprise
- Splunk Universal Forwarder
- Sysmon

---

## Technologies Used

- Splunk Enterprise
- Splunk Universal Forwarder
- Sysmon
- Windows Event Logs
- SPL (Search Processing Language)
- VirtualBox / VMware

---

## Monitoring Dashboard

The monitoring dashboard provides visibility into:

- Total Events
- Process Creation
- DNS Queries
- Network Connections
- Events Timeline
- Network Timeline
- Running Processes
- Destination Ports
- Connected Processes
- Parent Processes
- PowerShell & CMD Activity
- DNS Query Activity
- Recent Network Connections

---

## Detection Rules

The SOC Home Lab includes custom SPL detection rules for:

- PowerShell Execution
- Command Prompt Execution
- Encoded PowerShell
- Registry Persistence
- File Creation
- DNS Requests
- Network Connections
- Executables from Downloads

---

## Skills Demonstrated

- SIEM Monitoring
- Threat Detection
- Windows Event Analysis
- Sysmon Configuration
- Log Collection
- SPL Query Development
- Security Monitoring
- Incident Investigation

---

## Project Goals

- Build a functional SOC Home Lab.
- Collect Windows security telemetry.
- Monitor endpoint activity using Splunk.
- Create custom detection rules.
- Improve blue team investigation skills.

---

## Screenshots

Monitoring Dashboard

*(Screenshots will be added here.)*

Detection Dashboard

*(Screenshots will be added here.)*

---

## Future Improvements

- Windows Server
- Active Directory
- Sysmon Custom Rules
- Splunk Alerts
- MITRE ATT&CK Mapping
- Threat Hunting Dashboard

---

## Author

**Firas Saud**

Information Technology Student

Saudi Arabia
## Monitoring Dashboard

### Overview
![Monitoring 1](monitoring-1.jpeg)

### Process & Network Monitoring
![Monitoring 2](monitoring-2.jpeg)

### Activity Monitoring
![Monitoring 3](monitoring-3.jpeg)

### Recent Network Activity
![Monitoring 4](monitoring-4.jpeg)

---

## Detection Dashboard

### Detection Rules
![Detection 1](detection-1.jpeg)

### Detection Events
![Detection 2](detection-2.jpeg)

### Registry & File Detection
![Detection 3](detection-3.jpeg)
