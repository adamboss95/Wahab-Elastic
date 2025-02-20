# Zeek

**Zeek** (formerly known as Bro) is an open-source network monitoring and intrusion detection system that generates detailed logs about network traffic

## Common Zeek Log Types

**Conn.log:** Records all network connections. Key fields include source and destination IP addresses, ports, protocol, and service.

**Dns.log:** Records DNS query activity. Key fields include the queried domain, query type, answers, and response codes.

**Http.log:** Records HTTP traffic details. Key fields include hostname, requested URI, HTTP method, and status code.

**Ssl.log:** Records SSL/TLS activity. Key fields include TLS version, cipher suite, and SSL certificate issuer.

**Files.log:** Tracks file transfers over the network. Key fields include filename, MIME type, and MD5 hash of the file.

**Notice.log:** Summarizes key security-relevant events. Key fields include the type of notice and a detailed message about the event.