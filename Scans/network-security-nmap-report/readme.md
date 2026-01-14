# network-security-nmap-report
# TCP & Network Discovery Analysis using Nmap

## Objective
Identify active hosts, network services, and web/application configurations on the internal network to assess potential security risks, misconfigurations, and attack surface.

---

## Command Used
```bash
nmap -sS -sV -p 22,23,53,80,8022 192.168.100.1 \
  --script=http-security-headers,http-enum,http-headers,ssl-cert,broadcast-ping,broadcast-dhcp-discover,broadcast-upnp-info,eap-info
