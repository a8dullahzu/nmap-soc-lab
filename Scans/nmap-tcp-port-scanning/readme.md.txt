## TCP Port Scanning using Nmap

### Objective
Identify open, closed, and filtered TCP ports on an internal network host
to assess exposed services and security controls.

### Command Used
nmap 192.168.100.1

### Environment
- Authorized internal network
- Private IP address space
- Defensive, blue-team use case

### Findings
- Open ports: 53 (DNS), 80 (HTTP)
- Filtered ports: 22 (SSH), 23 (Telnet)
- Majority of TCP ports were closed

### SOC Relevance
- Identifying exposed services
- Validating firewall and access control rules
- Supporting incident investigation and attack surface analysis