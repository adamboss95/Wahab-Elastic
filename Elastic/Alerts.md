# Privileged Account Brute Force

Identifies multiple consecutive logon failures targeting an Admin account from the same source address and within a short time interval. Adversaries will often brute force login attempts across multiple users with a common or known password, in an attempt to gain access to accounts.

### **Rule type**: eql
- EQL is a special language used to search through event data, like logs and metrics, in Elasticsearch.
- Helps find patterns or sequences of events that might indicate something important, like a security threat.

### **Severity**: medium

### **Risk score**: 47


**Tags**:

- Domain: Endpoint
- OS: Windows
- Use Case: Threat Detection
- Tactic: Credential Access
- Resources: Investigation Guide
- Data Source: System


**Triage and analysis**

**Investigating Privileged Account Brute Force**

Adversaries with no prior knowledge of legitimate credentials within the system or environment may guess passwords to attempt access to accounts. Without knowledge of the password for an account, an adversary may opt to guess the password using a repetitive or iterative mechanism systematically.

This rule identifies potential password guessing/brute force activity from a single address against an account that contains the `admin` pattern on its name, which is likely a highly privileged account.

**Possible investigation steps**

