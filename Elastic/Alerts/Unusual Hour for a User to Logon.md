# Unusual Hour for a User to Logon

A machine learning job detected a user logging in at a time of day that is unusual for the user. This can be due to credentialed access via a compromised account when the user and the threat actor are in different time zones. In addition, unauthorized user activity often takes place during non-business hours.

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

**Triage and analysis**

**Investigating Unusual Hour for a User to Logon**

This rule uses a machine learning job to detect a user logging in at a time of day that is unusual for the user. This can be due to credentialed access via a compromised account when the user and the threat actor are in different time zones. It can also indicate unauthorized user activity, as it often occurs during non-business hours.

**Possible investigation steps**

- Identify the user account that performed the action and whether it should perform this kind of action.
- Contact the account owner and confirm whether they are aware of this activity.
- Investigate any abnormal account behavior, such as command executions, file creations or modifications, network connections, data access, and logon events.
- Investigate other alerts associated with the involved users during the past 48 hours.


**Response and remediation**

- Initiate the incident response process based on the outcome of the triage.
- Investigate credential exposure on systems compromised or used by the attacker to ensure all compromised accounts are identified. Reset passwords for these accounts and other potentially compromised credentials, such as email, business systems, and web services.
- Using the incident response data, update logging and audit policies to improve the mean time to detect (MTTD) and the mean time to respond (MTTR).