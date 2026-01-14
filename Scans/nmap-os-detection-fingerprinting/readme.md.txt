## OS Detection & Fingerprinting

### Objective
Attempt to identify the operating system of an internal network device
to support asset classification and incident triage.

### Observations
- Nmap was unable to identify an exact OS match
- TCP/IP fingerprinting data was collected but did not map to a known OS
- This behavior is common for embedded or network appliances

### Analysis
- The device is likely running a vendor-specific embedded OS
- OS fingerprinting is limited due to hardened network stack behavior
- Network-based OS detection should not be solely relied upon for asset identification

### SOC Relevance
- Demonstrates understanding of tool limitations
- Highlights the need for asset inventory correlation
- Prevents false assumptions during incident response