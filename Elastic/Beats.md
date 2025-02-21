# Beats

**Beats** are lightweight, open-source data shippers that you install on your servers to send operational data to Elasticsearch, which is part of the Elastic Stack (also known as ELK Stack). Each Beat is designed to collect specific types of data:

### Common Beats in Elastic:

1. **Packetbeat**: Captures network traffic and sends it to Elasticsearch for analysis. It helps in monitoring network activity and detecting anomalies.
    
2. **Filebeat**: Collects and ships log files and journal entries to Elasticsearch. It's useful for centralized log management and analysis.
    
3. **Auditbeat**: Gathers audit data from Linux systems, such as file access, system calls, and user activities. It's great for security and compliance monitoring.
    
4. **Winlogbeat**: Collects Windows event logs and sends them to Elasticsearch. It's specifically designed for Windows environments and helps in monitoring and analyzing Windows event logs.

5. **Metric Beat**: Metric

6. **Heart Beat**: Uptime Monitoring