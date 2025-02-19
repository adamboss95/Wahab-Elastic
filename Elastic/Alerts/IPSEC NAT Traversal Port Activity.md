# IPSEC NAT Traversal Port Activity


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


**Triage and analysis**

**Investigating IPSEC NAT Traversal Port Activity**

IPSEC NAT Traversal facilitates secure VPN communication across NAT devices by encapsulating IPSEC packets in UDP, typically using port 4500. While essential for legitimate encrypted traffic, adversaries exploit this to mask malicious activities, bypassing network defenses. The detection rule identifies unusual UDP traffic on port 4500, flagging potential misuse for further investigation.



