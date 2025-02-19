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



