# 🧱 Firewalls & Intrusion Detection Systems (IDS)

**Who this is for:** Cybersecurity students, administrators, and analysts learning how firewalls and IDS protect networks from attacks.

---

## Overview
Firewalls and IDS/IPS are **frontline defenses** that filter, monitor, and alert on malicious or unauthorized traffic.

- **Firewalls:** Control incoming/outgoing traffic based on security rules.
- **IDS/IPS:** Detect/block malicious activities.

Together, they form a strong perimeter defense layer in any network.

---

## Firewall Fundamentals
- Operates at **Layer 3/4** (Network/Transport).
- Rules are based on **IP, port, and protocol**.
- Modern next-gen firewalls (NGFW) include **application-layer** filtering and threat intelligence integration.

### Firewall Types
| Type | Description |
|------|--------------|
| Packet Filtering | Basic filtering by IP and port |
| Stateful Inspection | Tracks session states for better accuracy |
| Proxy Firewall | Intermediary between users and servers |
| Next-Gen Firewall (NGFW) | Deep packet inspection + application control |

### Firewall Best Practices
- Default **deny-all** outbound and inbound policies.  
- Regularly review and clean unused rules.  
- Implement **zone-based** segmentation (DMZ, internal, external).  
- Log all traffic and analyze anomalies.  
- Enable **alerting** for repeated failed connections.  

---

## Intrusion Detection & Prevention Systems
- **IDS:** Monitors network or host traffic for suspicious patterns.  
- **IPS:** Takes action automatically to block or mitigate threats.

### Detection Methods
- **Signature-based:** Matches known attack patterns.  
- **Anomaly-based:** Detects deviations from normal behavior.  
- **Hybrid:** Combines both methods for better accuracy.  

### Common Tools
| Category | Tools |
|-----------|-------|
| Network IDS | Snort, Suricata, Zeek (Bro) |
| Host-based IDS | OSSEC, Wazuh |
| Managed / Cloud | Cisco Secure IPS, CrowdStrike Falcon |

---

## Integration Example
- Firewall blocks known bad IPs.  
- IDS alerts when unusual traffic bypasses policy.  
- SIEM correlates events and triggers an incident response alert.  

---

## Quick Checklist
- [ ] Firewall configured with least privilege  
- [ ] IDS/IPS deployed and tuned  
- [ ] Logs centralized and monitored  
- [ ] Regular rule audits performed  
- [ ] Alerts reviewed and correlated in SIEM  

---

## Further Reading
- *NIST SP 800-41 Rev.1* — Guidelines on Firewalls and Firewall Policy  
- *CISA: Intrusion Detection Overview*  
- *Cisco Firepower Configuration Guide*  
- *Zeek Documentation*  

## ✍ **Author**

👩‍💻 **Chukwu PraiseGod**  
Follow my journey: [X](https://x.com/chukwupg) | [LinkedIn](https://linkedin.com/in/chukwupg)  
