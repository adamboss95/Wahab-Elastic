### agent.name

**Description**: `agent.name` signifies the name or identifier of the agent responsible for generating the log event

**Example**: If you have multiple Filebeat instances running, you might name them `filebeat_instance_1` and `filebeat_instance_2` to differentiate their data.

### agent.type

**Description**: `agent.type` field specifies the type of agent that collected or created the event. This field helps in identifying the nature and origin of the data collected, making it easier to manage and analyze different types of data within the Elastic Stack.

It can be from the type below:
- `filebeat`: For Filebeat agents collecting and shipping log files.
- `metricbeat`: For Metricbeat agents collecting system and service metrics.
- `heartbeat`: For Heartbeat agents monitoring system availability.
- `packetbeat`: For Packetbeat agents capturing and analyzing network traffic.
- `auditbeat`: For Auditbeat agents tracking user activity and system integrity.
- `winlogbeat`: For Winlogbeat agents collecting Windows event logs.

**Example**: `agent.type: "metricbeat"`
### event.action
The action captured by the event.

### event.code

**Description**: `event.code` contains a specific code that uniquely identifies the type of event that occurred. It is used to categorize and differentiate various events, such as security incidents, errors, or system actions.

**Example**: A login failure might be represented by the code `4625` in Windows Event Logs.

### event.outcome

**Description**: `event.outcome` Indicates the result of the event, specifying whether it was successful, failed, or resulted in an unknown outcome. This field helps in quickly assessing the nature of the event.

**Example**: `success`, `failure`, `unknown`.

### host.hostname

**Description**: `host.hostname` is the hostname of the machine on which the event occurred. This helps in identifying the specific host involved in generating the event.

**Example**: `webserver01`, `database-server`.

### host.ip

**Description**: `host.ip` is the IP address of the host where the event originated. It provides additional context for network-related events and helps in tracing the source.

**Example**: `192.168.1.10`, `2001:0db8:85a3:0000:0000:8a2e:0370:7334`.

### host.os.family

**Description**: `host.os.family` describes the family of the operating system running on the host. This field categorizes the OS into broader groups such as `Windows`, `Linux`, or `macOS`.

**Example**: `Windows`, `Linux`, `macOS`.

### kibana.alert.rule.name

**Description**: `kibana.alert.rule.name` is the name of the rule in Kibana that triggered the alert. This helps in identifying which specific detection rule caused the alert to be generated.

**Example**: `Unauthorized Access Attempt`, `High CPU Usage Alert`.

### kibana.alert.original_event.category

**Description**: `kibana.alert.original_event.category` is the category of the original event that led to the generation of the alert. This categorization helps in understanding the nature of the event that triggered the alert.

**Example**: `authentication`, `process`, `network`.

### kibana.alert.rule.threat.tactic.name

**Description**: `kibana.alert.rule.threat.tactic.name` is the name of the MITRE ATT&CK tactic associated with the rule that triggered the alert. This provides context about the high-level objective of the adversary's actions.

**Example**: `Privilege Escalation`, `Initial Access`.

### kibana.alert.rule.threat.technique

**Description**: `kibana.alert.rule.threat.technique` is the specific MITRE ATT&CK technique associated with the rule that triggered the alert. This provides detailed insight into the methods used by the adversary.

**Example**: `T1078 - Valid Accounts`, `T1059 - Command and Scripting Interpreter`.

### message

**Description**: `message` is a textual description of the event, providing detailed information about what happened. This field is often used to store the raw log message.

**Example**: `User 'admin' failed to log in from IP address 192.168.1.100`.

### related.ip

**Description**: `related.ip` contains IP addresses that are related to the event, such as source, destination, or intermediary IPs involved in the event.

**Example**: `[192.168.1.100, 10.0.0.1]`.

### winlog.event_data.status

**Description**: `winlog.event_data.status` provides status information about the Windows event, indicating whether the event resulted in success, failure, or other status codes specific to the event type.

**Example**: `0x0` (success), `0xC000006D` (failure).

### winlog.event_data.substatus

**Description**: `winlog.event_data.substatus` additional substatus information related to the Windows event, providing more granular details about the outcome of the event.

**Example**: `0xC0000064` (user name does not exist), `0xC000006A` (incorrect password).

These detailed explanations should give you a clearer understanding of the tags used in Elastic and how they can be leveraged for better data management and analysis. If you have any more questions or need further details, feel free to ask!
