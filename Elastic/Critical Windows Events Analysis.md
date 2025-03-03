# 🚨 Critical Windows Event IDs Every SOC Analyst Must Monitor! 🚨

## 🔍 Authentication & Account Monitoring
- **Failed Login Attempts**  
  **Event ID:** 4625  
  **Description:** Brute-force attack indicator

- **Account Lockouts**  
  **Event ID:** 4740  
  **Description:** Possible attack or misconfigured account

- **Successful Login Outside Business Hours**  
  **Event ID:** 4624  
  **Description:** Potential insider threat

- **New User Creation**  
  **Event ID:** 4720  
  **Description:** Privilege escalation risk

- **Privileged Account Usage**  
  **Event ID:** 4672  
  **Description:** Administrative actions tracking

- **User Account Changes**  
  **Event IDs:** 4722, 4723, 4724, 4725, 4726  
  **Description:** Monitor critical modifications

- **Logon from Unusual Locations**  
  **Event ID:** 4624  
  **Description:** Requires geolocation correlation

- **Dormant Account Usage**  
  **Event ID:** 4624  
  **Description:** Rarely used accounts being accessed

## 🔐 Access & Privilege Escalation Monitoring
- **Group Membership Changes**  
  **Event IDs:** 4727, 4731, 4735, 4737  
  **Description:** Potential privilege escalation

- **Excessive Logon Failures**  
  **Event ID:** 4625  
  **Description:** Brute-force detection

- **Disabled Account Activity**  
  **Event ID:** 4725  
  **Description:** Unauthorized account reactivation

- **Service Account Activity**  
  **Event IDs:** 4624, 4672  
  **Description:** Monitor service account usage

- **RDP Access Monitoring**  
  **Event ID:** 4624  
  **Description:** Filter for RDP connections

- **Lateral Movement Detection**  
  **Event ID:** 4648  
  **Description:** Network logon tracking

## 🛡️ Endpoint & System Security
- **File and Folder Access**  
  **Event ID:** 4663  
  **Description:** Unauthorized file access detection

- **Unauthorized File Sharing**  
  **Event IDs:** 5140, 5145  
  **Description:** Suspicious SMB activity

- **Registry Changes**  
  **Event ID:** 4657  
  **Description:** Malware persistence attempts

- **Application Installation & Removal**  
  **Event IDs:** 11707, 1033  
  **Description:** Potential unauthorized installs

- **USB Device Usage**  
  **Event IDs:** 20001, 20003  
  **Description:** Detect unauthorized device usage

- **Windows Firewall Changes**  
  **Event IDs:** 4946, 4947, 4950, 4951  
  **Description:** Potential backdoor attempts

- **Scheduled Task Creation**  
  **Event ID:** 4698  
  **Description:** Persistence mechanism used by attackers

- **Process Execution Monitoring**  
  **Event ID:** 4688  
  **Description:** Malicious process detection

- **System Restart or Shutdown**  
  **Event IDs:** 6005, 6006, 1074  
  **Description:** Unexpected shutdowns

- **Event Log Clearing**  
  **Event ID:** 1102  
  **Description:** Indicators of log tampering

## 🦠 Threat Intelligence & Malware Indicators
- **Malware Execution**  
  **Event IDs:** 4688, 1116  
  **Description:** Monitor suspicious process execution

- **Shadow Copy Deletion**  
  **Event ID:** 524  
  **Description:** Ransomware indicator

- **Execution of Suspicious Scripts**  
  **Event ID:** 4688  
  **Description:** Monitor PowerShell, cmd, etc.

- **Service Installation or Modification**  
  **Event ID:** 4697  
  **Description:** Persistence method for malware

## 🌐 Network & Active Directory Security
- **Unusual Network Connections**  
  **Event ID:** 5156  
  **Description:** Monitor suspicious outbound connections

- **Unauthorized Access to Shared Files**  
  **Event ID:** 5145  
  **Description:** Potential data exfiltration

- **DNS Query for Malicious Domains**  
  **Event ID:** 5158  
  **Description:** Requires DNS logs

- **LDAP Search Abuse**  
  **Event ID:** 4662  
  **Description:** AD enumeration attempts
