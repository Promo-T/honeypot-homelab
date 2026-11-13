# T-Pot Honeypot in an Isolated Homelab
 
A multi-honeypot ([T-Pot](https://github.com/telekom-security/tpotce)) deployed in an isolated network segment behind an OPNsense firewall, exposed to the internet through a WireGuard tunnel from a VPS. The goal: collect real attack data safely, and document the network design, the problems I hit and what the data shows.
 
**Data period:** `[08.11.2026 - DD.MM.2026]` (update in progress)  
**Stack:** Proxmox, OPNsense, WireGuard, T-Pot 24.04, Elasticsearch/Kibana, nftables, VPS (Hetzner)

---