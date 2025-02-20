# Alert Descriptions, Investigation & Mitigation

## [Privileged Account Brute Force](https://www.elastic.co/guide/en/security/current/privileged-account-brute-force.html#_investigation_guide_824)

Identifies multiple consecutive logon failures targeting an Admin account from the same source address and within a short time interval. Adversaries will often brute force login attempts across multiple users with a common or known password, in an attempt to gain access to accounts.

**Rule type**: eql

**Severity**: medium

**Risk score**: 47

**Tags**:

- *Domain:* Endpoint
- *OS:* Windows
- *Use Case:* Threat Detection
- *Tactic:* Credential Access
- *Resources:* Investigation Guide
- *Data Source:* System

### Investigation Guide

#### Triage and analysis

**Investigating Privileged Account Brute Force**

Adversaries with no prior knowledge of legitimate credentials within the system or environment may guess passwords to attempt access to accounts. Without knowledge of the password for an account, an adversary may opt to guess the password using a repetitive or iterative mechanism systematically. More details can be found [here](https://attack.mitre.org/techniques/T1110/001/).

This rule identifies potential password guessing/brute force activity from a single address against an account that contains the `admin` pattern on its name, which is likely a highly privileged account.

**Possible investigation steps**

Identify whether these attempts are coming from the internet or are internal.

Identify the source and the target computer and their roles in the IT environment.

Investigate other alerts associated with the involved users and source host during the past 48 hours.

If this activity is suspicious, contact the account owner and confirm whether they are aware of it.
#### Mitigation

Isolate the source host to prevent further post-compromise behavior.

Run a full antimalware scan. This may reveal additional artifacts left in the system, persistence mechanisms, and malware components.

Determine the initial vector abused by the attacker and take action to prevent reinfection through the same vector.

Using the incident response data, update logging and audit policies to improve the mean time to detect (MTTD) and the mean time to respond (MTTR).

## [IPSEC NAT Traversal Port Activity](https://www.elastic.co/guide/en/security/current/ipsec-nat-traversal-port-activity.html#_investigation_guide_420)


This rule detects events that could be describing IPSEC NAT Traversal traffic. IPSEC is a VPN technology that allows one system to talk to another using encrypted tunnels. NAT Traversal enables these tunnels to communicate over the Internet where one of the sides is behind a NAT router gateway. This may be common on your network, but this technique is also used by threat actors to avoid detection.

**Rule type**: query

**Severity**: low

**Risk score**: 21

**Tags**:

- Tactic: Command and Control
- Domain: Endpoint
- Use Case: Threat Detection
- Data Source: PAN-OS
- Resources: Investigation Guide

### Investigation guide

#### Triage and analysis

**Investigating IPSEC NAT Traversal Port Activity**

IPSEC NAT Traversal facilitates secure VPN communication across NAT devices by encapsulating IPSEC packets in UDP, typically using port 4500. While essential for legitimate encrypted traffic, adversaries exploit this to mask malicious activities, bypassing network defenses. The detection rule identifies unusual UDP traffic on port 4500, flagging potential misuse for further investigation.

**Possible investigation steps**

Review the source and destination IP addresses associated with the UDP traffic on port 4500 to determine if they are known or expected within your network environment.

Analyze the volume and frequency of the detected traffic to assess whether it aligns with typical IPSEC NAT Traversal usage or if it appears anomalous

Check for any associated network traffic events in the same timeframe that might indicate a pattern of suspicious activity, such as unusual data transfer volumes or connections to known malicious IP addresses.

Investigate the endpoint or device generating the traffic to verify if it is authorized to use IPSEC NAT Traversal and if it has any history of security incidents or vulnerabilities.

#### Mitigation

Immediately isolate the affected system from the network to prevent further potential malicious activity and lateral movement.

Conduct a thorough analysis of the isolated system to identify any signs of compromise, such as unauthorized access or data exfiltration, focusing on logs and network traffic related to UDP port 4500.

Review and update firewall and intrusion detection/prevention system (IDS/IPS) rules to ensure they effectively block unauthorized IPSEC NAT Traversal traffic, particularly on UDP port 4500.

Restore the affected system from a known good backup if any signs of compromise are confirmed, ensuring that all security patches and updates are applied before reconnecting to the network.

## [Unusual Windows Username](https://www.elastic.co/guide/en/security/current/ipsec-nat-traversal-port-activity.html#_investigation_guide_420)

A machine learning job detected activity for a username that is not normally active, which can indicate unauthorized changes, activity by unauthorized users, lateral movement, or compromised credentials. In many organizations, new usernames are not often created apart from specific types of system activities, such as creating new accounts for new employees. These user accounts quickly become active and routine. Events from rarely used usernames can point to suspicious activity. Additionally, automated Linux fleets tend to see activity from rarely used usernames only when personnel log in to make authorized or unauthorized changes, or threat actors have acquired credentials and log in for malicious purposes. Unusual usernames can also indicate pivoting, where compromised credentials are used to try and move laterally from one host to another.

**Rule type**: machine_learning

**Severity**: low

**Risk score**: 21

**Tags**:

- Domain: Endpoint
- OS: Windows
- Use Case: Threat Detection
- Rule Type: ML
- Rule Type: Machine Learning
- Tactic: Initial Access
- Resources: Investigation Guide

### Investigation guide

**Triage and analysis**

**Investigating Unusual Windows Username**

Detection alerts from this rule indicate activity for a Windows user name that is rare and unusual.

*Here are some possible avenues of investigation:*

Consider the user as identified by the username field. Is this program part of an expected workflow for the user who ran this program on this host? Could this be related to occasional troubleshooting or support activity? 

Examine the history of user activity. If this user only manifested recently, it might be a service account for a new software package. If it has a consistent cadence (for example if it runs monthly or quarterly), it might be part of a monthly or quarterly business process.

Examine the process arguments, title and working directory. These may provide indications as to the source of the program or the nature of the tasks that the user is performing.

Consider the same for the parent process. If the parent process is a legitimate system utility or service, this could be related to software updates or system management. If the parent process is something user-facing like an Office application, this process could be more suspicious.

## [Rare User Logon](https://www.elastic.co/guide/en/security/current/rare-user-logon.html)

A machine learning job found an unusual user name in the authentication logs. An unusual user name is one way of detecting credentialed access by means of a new or dormant user account. An inactive user account (because the user has left the organization) that becomes active may be due to credentialed access using a compromised account password. Threat actors will sometimes also create new users as a means of persisting in a compromised web application.

**Rule type**: machine_learning

**Severity**: low

**Risk score**: 21

**Tags**:

- Use Case: Identity and Access Audit
- Use Case: Threat Detection
- Rule Type: ML
- Rule Type: Machine Learning
- Tactic: Initial Access
- Resources: Investigation Guide

### Investigation guide

#### Triage and analysis

**Investigating Rare User Logon**

This rule uses a machine learning job to detect an unusual user name in authentication logs, which could detect new accounts created for persistence.

**Possible investigation steps**

Check if the user was newly created and if the company policies were followed.

Identify the user account that performed the action and whether it should perform this kind of action.

Investigate other alerts associated with the involved users during the past 48 hours.

Investigate any abnormal account behavior, such as command executions, file creations or modifications, and network connections.

#### Mitigation

Initiate the incident response process based on the outcome of the triage.

Investigate credential exposure on systems compromised or used by the attacker to ensure all compromised accounts are identified. 

Reset passwords for these accounts and other potentially compromised credentials, such as email, business systems, and web services.

Using the incident response data, update logging and audit policies to improve the mean time to detect (MTTD) and the mean time to respond (MTTR).

## [SMTP on Port 26/TCP](https://www.elastic.co/guide/en/security/current/smtp-on-port-26-tcp.html)

This rule detects events that may indicate use of SMTP on TCP port 26. This port is commonly used by several popular mail transfer agents to deconflict with the default SMTP port 25. This port has also been used by a malware family called BadPatch for command and control of Windows systems.

**Rule type**: query

**Severity**: low

**Risk score**: 21

**Tags**:

- Tactic: Command and Control
- Domain: Endpoint
- Use Case: Threat Detection
- Data Source: PAN-OS
- Resources: Investigation Guide

**Investigating SMTP on Port 26/TCP**

SMTP, typically operating on port 25, is crucial for email transmission. However, port 26 is often used to avoid conflicts or restrictions on port 25. Adversaries exploit this by using port 26 for covert command and control, as seen with the BadPatch malware. The detection rule identifies suspicious SMTP activity on port 26 by analyzing network traffic patterns, helping to uncover potential threats.

### Investigation guide

#### Triage and analysis

**Investigating SMTP on Port 26/TCP**

SMTP, typically operating on port 25, is crucial for email transmission. However, port 26 is often used to avoid conflicts or restrictions on port 25. Adversaries exploit this by using port 26 for covert command and control, as seen with the BadPatch malware. The detection rule identifies suspicious SMTP activity on port 26 by analyzing network traffic patterns, helping to uncover potential threats.

**Possible investigation steps**

Review the network traffic logs to identify any unusual patterns or anomalies associated with TCP port 26, focusing on the event.dataset fields such as network_traffic.flow or zeek.smtp

Analyze the source and destination IP addresses involved in the alert to determine if they are known or associated with any previous suspicious activities.

Check for any additional alerts or logs related to the same source or destination IP addresses to identify potential patterns or repeated attempts of communication on port 26.

Assess the risk and impact on the affected systems by determining if any sensitive data or critical systems are involved in the communication on port 26.

#### Mitigation

Immediately isolate the affected system from the network to prevent further command and control communication via port 26.

Conduct a thorough scan of the isolated system using updated antivirus and anti-malware tools to identify and remove the BadPatch malware or any other malicious software.

Review and analyze network logs to identify any other systems that may have communicated with the same command and control server, and isolate those systems as well.

Change all passwords and credentials that may have been compromised or accessed by the affected system to prevent unauthorized access.

## [Spike in Network Traffic](https://www.elastic.co/guide/en/security/current/spike-in-network-traffic.html)

A machine learning job detected an unusually large spike in network traffic. Such a burst of traffic, if not caused by a surge in business activity, can be due to suspicious or malicious activity. Large-scale data exfiltration may produce a burst of network traffic; this could also be due to unusually large amounts of reconnaissance or enumeration traffic. Denial-of-service attacks or traffic floods may also produce such a surge in traffic.

**Rule type**: machine_learning

**Severity**: low

**Risk score**: 21

### Investigation guide

#### Triage and analysis

**Investigating Spike in Network Traffic**

Machine learning models analyze network traffic patterns to identify anomalies, such as unexpected spikes. These spikes may indicate malicious activities like data exfiltration or denial-of-service attacks. Adversaries exploit network vulnerabilities to flood traffic or extract data. The _Spike in Network Traffic_ rule leverages ML to flag unusual traffic surges, aiding in early threat detection and response.

**Possible investigation steps**

Review the timestamp and duration of the traffic spike to determine if it correlates with any scheduled business activities or known events.

Analyze the source and destination IP addresses involved in the traffic spike to identify any unfamiliar or suspicious entities.

Examine the types of network protocols and services involved in the spike to assess if they align with typical network usage patterns.

Check for any recent changes in network configurations or security policies that might explain the unusual traffic patterns.

#### Mitigation

Immediately isolate affected systems from the network to prevent further data exfiltration or traffic flooding.

Conduct a thorough analysis of network logs to identify the source and destination of the traffic spike, focusing on any unauthorized or suspicious IP addresses.

Block identified malicious IP addresses and domains at the firewall and update intrusion prevention systems to prevent further access.

If data exfiltration is suspected, perform a data integrity check to assess any potential data loss or compromise.

## [Anomalous Windows Process Creation](https://www.elastic.co/guide/en/security/current/anomalous-windows-process-creation.html)


Identifies unusual parent-child process relationships that can indicate malware execution or persistence mechanisms. Malicious scripts often call on other applications and processes as part of their exploit payload. For example, when a malicious Office document runs scripts as part of an exploit payload, Excel or Word may start a script interpreter process, which, in turn, runs a script that downloads and executes malware. Another common scenario is Outlook running an unusual process when malware is downloaded in an email. Monitoring and identifying anomalous process relationships is a method of detecting new and emerging malware that is not yet recognized by anti-virus scanners.

**Rule type**: machine_learning

**Severity**: low

**Risk score**: 21

**Tags**:

- Domain: Endpoint
- OS: Windows
- Use Case: Threat Detection
- Rule Type: ML
- Rule Type: Machine Learning
- Tactic: Persistence
- Resources: Investigation Guide

### Investigation guide

#### Triage and analysis

**Investigating Anomalous Windows Process Creation**

Searching for abnormal Windows processes is a good methodology to find potentially malicious activity within a network. Understanding what is commonly run within an environment and developing baselines for legitimate activity can help uncover potential malware and suspicious behaviors.

This rule uses a machine learning job to detect an anomalous Windows process with an unusual parent-child relationship, which could indicate malware execution or persistence activities on the host machine.

**Possible investigation steps**

If the parent process is a legitimate system utility or service, this could be related to software updates or system management. If the parent process is something user-facing like an Office application, this process could be more suspicious.

Investigate the process metadata — such as the digital signature, directory, etc. — to obtain more context that can indicate whether the executable is associated with an expected software vendor or package.

Validate if the activity has a consistent cadence (for example, if it runs monthly or quarterly), as it could be part of a monthly or quarterly business process.

Retrieve the files' SHA-256 hash values using the PowerShell `Get-FileHash` cmdlet and search for the existence and reputation of the hashes in resources like VirusTotal.

#### Mitigation

If the triage identified malware, search the environment for additional compromised hosts.

Stop suspicious processes.

Immediately block the identified indicators of compromise (IoCs).

Inspect the affected systems for additional malware backdoors like reverse shells or droppers that attackers could use to reinfect the system.

Remove and block malicious artifacts identified during triage.

## [Unusual Hour for a User to Logon](https://www.elastic.co/guide/en/security/current/unusual-hour-for-a-user-to-logon.html)

A machine learning job detected *a user logging in at a time of day that is unusual for the user.* This can be due to credentialed access via a compromised account when the user and the threat actor are in different time zones. In addition, unauthorized user activity often takes place during non-business hours.

**Rule type**: machine_learning

**Severity**: low

**Risk score**: 21

**Tags**:

- Use Case: Identity and Access Audit
- Use Case: Threat Detection
- Rule Type: ML
- Rule Type: Machine Learning
- Tactic: Initial Access
- Resources: Investigation Guide

### Investigation guide

#### Triage and analysis

**Investigating Unusual Hour for a User to Logon**

This rule uses a machine learning job to detect a user logging in at a time of day that is unusual for the user. This can be due to credentialed access via a compromised account when the user and the threat actor are in different time zones. It can also indicate unauthorized user activity, as it often occurs during non-business hours.

**Possible investigation steps**

Identify the user account that performed the action and whether it should perform this kind of action.

Contact the account owner and confirm whether they are aware of this activity.

Investigate any abnormal account behavior, such as command executions, file creations or modifications, network connections, data access, and logon events.

Investigate other alerts associated with the involved users during the past 48 hours.

#### Mitigation

Initiate the incident response process based on the outcome of the triage.

Investigate credential exposure on systems compromised or used by the attacker to ensure all compromised accounts are identified. Reset passwords for these accounts and other potentially compromised credentials, such as email, business systems, and web services.

Using the incident response data, update logging and audit policies to improve the mean time to detect (MTTD) and the mean time to respond (MTTR).

## [Unusual Process For a Windows Host](https://www.elastic.co/guide/en/security/current/unusual-process-for-a-windows-host.html)

Identifies rare processes that do not usually run on individual hosts, which can indicate execution of unauthorized services, malware, or persistence mechanisms. Processes are considered rare when they only run occasionally as compared with other processes running on the host

**Rule type**: machine_learning

**Severity**: low

**Risk score**: 21

**Tags**:

- Domain: Endpoint
- OS: Windows
- Use Case: Threat Detection
- Rule Type: ML
- Rule Type: Machine Learning
- Tactic: Persistence
- Resources: Investigation Guide

## Investigation guide

#### Triage and analysis

**Investigating Unusual Process For a Windows Host**

Searching for abnormal Windows processes is a good methodology to find potentially malicious activity within a network. Understanding what is commonly run within an environment and developing baselines for legitimate activity can help uncover potential malware and suspicious behaviors.

This rule uses a machine learning job to detect a Windows process that is rare and unusual for an individual Windows host in your environment.

**Possible investigation steps**

Investigate the process execution chain (parent process tree) for unknown processes. Examine their executable files for prevalence, whether they are located in expected locations, and if they are signed with valid digital signatures.

If the parent process is a legitimate system utility or service, this could be related to software updates or system management. If the parent process is something user-facing like an Office application, this process could be more suspicious.

Investigate the process metadata — such as the digital signature, directory, etc. — to obtain more context that can indicate whether the executable is associated with an expected software vendor or package.

Investigate other alerts associated with the user/host during the past 48 hours.

#### Mitigation

Isolate the involved hosts to prevent further post-compromise behavior.

If the triage identified malware, search the environment for additional compromised hosts.

Implement temporary network rules, procedures, and segmentation to contain the malware.

Stop suspicious processes.

## Multiple Alerts in Different ATT&CK Tactics on a Single Host

This rule uses alert data to determine *when multiple alerts in different phases of an attack involving the same host are triggered*. Analysts can use this to prioritize triage and response, as these hosts are more likely to be compromised.

**Rule type**: threshold

**Severity**: high

**Risk score**: 73

**Tags**:

- Use Case: Threat Detection
- Rule Type: Higher-Order Rule
- Resources: Investigation Guide
 

> [!NOTE] Higher Order Rule
> Combines multiple alerts or conditions to identify more complex attack patterns or behaviors.

## Investigation guide

#### Triage and analysis

**Investigating Multiple Alerts in Different ATT&CK Tactics on a Single Host**

The detection rule identifies hosts with alerts across various attack phases, indicating potential compromise. Adversaries exploit system vulnerabilities, moving through different tactics like execution, persistence, and exfiltration. This rule prioritizes hosts with diverse tactic alerts, aiding analysts in focusing on high-risk threats by correlating alert data to detect complex attack patterns.

**Possible investigation steps**

Review the alert details to identify the specific host involved and the different ATT&CK tactics that triggered the alerts.

Examine the timeline of the alerts to understand the sequence of events and determine if there is a pattern or progression in the tactics used.

Correlate the alert data with other logs and telemetry from the host, such as process creation, network connections, and file modifications, to gather additional context.

Check for any indicators of compromise (IOCs) associated with the alerts, such as suspicious IP addresses, domains, or file hashes, and search for these across the network.

#### 