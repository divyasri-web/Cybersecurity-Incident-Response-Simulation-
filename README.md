# Cybersecurity-Incident-Response-Simulation

A hands-on cybersecurity project that simulates the investigation of a suspected security incident using industry-standard incident response techniques. The project demonstrates how to collect evidence, analyze system activities, identify Indicators of Compromise (IoCs), reconstruct an attack timeline, and recommend containment and recovery actions.

---

## Project Objectives

- Understand the Incident Response Lifecycle.
- Investigate Windows security events and system activities.
- Monitor running processes and network connections.
- Capture and analyze network traffic using Wireshark.
- Identify Indicators of Compromise (IoCs).
- Reconstruct the attack timeline.
- Recommend containment and recovery measures.

---

## Tools & Technologies

- Windows 11
- Kali Linux (VirtualBox)
- Windows Event Viewer
- Process Explorer
- TCPView
- Command Prompt (netstat)
- Windows Defender
- Task Manager
- Wireshark

---

## Project Workflow

### 1. Environment Setup
- Prepared the Windows investigation environment.
- Opened all required monitoring and analysis tools.

### 2. Process Analysis
- Examined running processes using Process Explorer.
- Verified process names, PIDs, CPU usage, memory usage, company names, and parent-child relationships.

### 3. Network Connection Analysis
- Used `netstat -ano` and TCPView to inspect active network connections.
- Reviewed listening ports, established connections, and associated process IDs.

### 4. Security Log Analysis
- Investigated Windows Security and System logs using Event Viewer.
- Reviewed authentication events and important Event IDs.

### 5. Network Traffic Analysis
- Captured live packets using Wireshark in Kali Linux.
- Analyzed TCP, DNS, and ICMP traffic using protocol filters.

### 6. Indicator of Compromise (IoC) Analysis
- Correlated process, network, and log data.
- Identified whether any malicious indicators were present.

### 7. Attack Timeline Reconstruction
- Reconstructed the sequence of observed security events.
- Documented investigation findings in chronological order.

### 8. Incident Assessment
- Evaluated collected evidence.
- Determined whether the system had been compromised.

---

## Results

- Successfully analyzed Windows Security Event Logs.
- Monitored active system processes.
- Verified legitimate Microsoft system processes.
- Reviewed active TCP connections.
- Captured and analyzed network packets.
- No suspicious processes, malware, or unauthorized activities were detected.
- No confirmed Indicators of Compromise (IoCs) were identified during the investigation.

---

## Indicators of Compromise (IoCs)

| Category | Observation | Assessment |
|----------|-------------|------------|
| Windows Security Logs | Event IDs 5379, 4798, 4624 | Normal Windows activity |
| Running Processes | svchost.exe, cmdagent.exe | Legitimate processes |
| Network Connections | Active TCP connections | No malicious communication detected |
| Windows Defender | No threats detected | System secure |
| Installed Applications | No suspicious software | Normal |

---

## Containment Recommendations

- Continue monitoring Windows Security Logs.
- Perform regular malware scans.
- Monitor outbound network traffic.
- Keep Windows and applications updated.
- Enable Multi-Factor Authentication (MFA).
- Conduct periodic security audits.

---

## Recovery Recommendations

- Maintain regular system backups.
- Apply security patches promptly.
- Review user privileges periodically.
- Enable centralized log monitoring.
- Perform scheduled antivirus scans.
- Continue continuous network monitoring.

---


## Outcomes

Through this project, I gained practical experience in:

- Incident Response Lifecycle
- Windows Event Log Analysis
- Process Monitoring
- Network Traffic Analysis
- TCP Connection Analysis
- Digital Evidence Collection
- Indicators of Compromise (IoCs)
- Attack Timeline Reconstruction
- Security Incident Investigation

---

## Skills Demonstrated

- Incident Response
- Security Monitoring
- Log Analysis
- Network Analysis
- Windows Security
- Wireshark
- Process Investigation
- Threat Detection
- Digital Forensics Fundamentals

---

## Conclusion

This project provided practical experience in investigating a simulated cybersecurity incident using Windows security tools and network monitoring utilities. By correlating information from Event Viewer, Process Explorer, TCPView, Wireshark, and Windows Defender, I concluded that the observed activities represented normal operating system behavior and found no evidence of system compromise. The project reinforced the importance of validating multiple evidence sources before classifying security events as incidents.
