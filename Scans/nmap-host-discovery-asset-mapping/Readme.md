## Host Discovery & Asset Mapping using Nmap

### Objective
Identify live hosts within an internal network to support asset inventory,
network visibility, and rogue device detection.

### Command Used
nmap -sn 192.168.100.0/24

### Environment
- Local / authorized internal network
- Private IP address range
- Defensive, blue-team use case only

### Findings
- 10 active hosts detected out of 256 scanned
- MAC addresses collected for local devices
- Vendor identification revealed Huawei and ZTE devices
- Multiple hosts with unknown vendors, indicating unmanaged or unidentified assets

### SOC Relevance
- Asset inventory and visibility
- Identification of unknown or rogue devices
- Baseline creation for incident detection
