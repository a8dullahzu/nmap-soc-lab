## UDP Service Analysis using Nmap

### Objective
Identify exposed UDP services on an internal network device to assess
potential amplification and information disclosure risks.

### Command Used
nmap -sU -p 53,123,161 192.168.100.1

### Environment
- Authorized internal network
- Private IP address space
- Defensive, SOC-focused use case

### Findings
- UDP 53 (DNS) is open and accessible
- UDP 123 (NTP) is closed
- UDP 161 (SNMP) is closed

### Security Implications
- Closed NTP and SNMP reduce amplification and information leakage risks
- Open DNS should be monitored for abuse or misconfiguration

### SOC Relevance
- Detection of exposed UDP services
- Validation of secure service configurations
- Support for incident detection and prevention
