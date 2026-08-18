# 💀 Ransomware

**Who this is for:** Security learners, IT professionals, and general users who want to understand how ransomware works, how to prevent it, and what to do in the event of such incident.  

---

## Overview
Ransomware is a form of **malware that encrypts files** on a system or network, rendering them inaccessible until a ransom is paid (often in cryptocurrency). 
It’s one of the most disruptive cyber threats to organizations, with variants targeting individuals, enterprises, and critical infrastructure.

---

## How Ransomware Works
1. **Attack Vector:**  
   Attackers deliver ransomware via phishing emails, malicious downloads, drive-by attacks, or Remote Desktop Protocol (RDP) brute-force attempts.  

2. **Execution:**  
   Once executed, the malware encrypts files, deletes backups, and may disable recovery options.  

3. **Communication:**  
   Some variants contact command-and-control (C2) servers for encryption keys or to exfiltrate data before encryption.  

4. **Ransom Demand:**  
   The attacker demands payment (usually in cryptocurrency) in exchange for the decryption key.  

5. **Double Extortion:**  
   Newer ransomware campaigns also steal sensitive data and threaten to leak it if payment is not made.
   Some go as far as leaking it, whether or not payment is made (there is no guarantee that the attacker will release the decryption key after payment has been made)

---

## Common Ransomware Families
- **CryptoLocker / CryptoWall:** Early widespread encryptors.  
- **Locky / WannaCry / NotPetya:** Propagated rapidly across networks via SMB vulnerabilities.  
- **Ryuk / Conti / REvil:** Enterprise-targeted ransomware-as-a-service (RaaS) variants.  
- **BlackCat (ALPHV):** Modern RaaS known for double extortion and data leaks.  

---

## Ransomware Attack Vectors
- **Phishing emails** with malicious attachments or links.  
- **Exposed RDP ports** and weak credentials.  
- **Exploiting unpatched software vulnerabilities** (e.g., EternalBlue).  
- **Drive-by downloads** from compromised websites.  
- **Malvertising,** and
- Infected USB drives.  

---

## Prevention & Hardening
- **User Awareness Training:** Teach staff to recognize phishing attempts and suspicious files.  
- **Patch Management:** Keep OS, browsers, and applications updated.  
- **Network Segmentation:** Limit lateral movement by isolating critical systems.  
- **Access Control:** Follow the principle of least privilege (no local admin rights).  
- **Endpoint Protection:** Deploy EDR (Endpoint Detection & Response) tools capable of ransomware behavior detection.  
- **Disable Macros:** Prevent Office macros from running automatically.  
- **Secure Backups:** Maintain offline or immutable backups stored separately from production data.  
- **Restrict RDP Access:** Use VPN + MFA or disable RDP if unnecessary.  

---

## Incident Response
1. **Isolate the infected system** immediately to stop the spread.  
2. **Preserve forensic evidence** (don’t wipe the system yet).  
3. **Notify your security/incident response team** and relevant stakeholders.  
4. **Identify the ransomware strain** using tools like *ID Ransomware*.  
5. **Check for decryptors** from trusted sources (No More Ransom project).  
6. **Do not pay the ransom**; there’s no guarantee of recovery and it funds more crime.  
7. **Restore from clean backups** after confirming the system is clean.  
8. **Perform a post-incident review** to identify and fix gaps exploited during the attack.  

---

## Recovery & Post-Incident Actions
- Verify the **integrity of backups** before restoring.  
- **Change all credentials** potentially exposed.  
- Update endpoint detection rules to catch the variant earlier next time.  
- Report to **law enforcement or CERT** if required by regulations.  

---

## Tools & Resources
| Purpose | Tools / Sites |
|----------|---------------|
| Identification | ID Ransomware, MalwareBazaar |
| Decryption | No More Ransom (nomoreransom.org) |
| Backup | Veeam, Acronis, Duplicati, Windows Backup |
| Detection / EDR | CrowdStrike Falcon, Microsoft Defender, SentinelOne |
| Threat Intelligence | VirusTotal, Any.Run, Hybrid Analysis |

---

## Quick Checklist
- [ ] RDP secured or disabled  
- [ ] Regular offline backups exist and are tested  
- [ ] All systems patched and up to date  
- [ ] Endpoint protection with ransomware behavior detection  
- [ ] Users trained to recognize phishing attempts  
- [ ] Incident response plan for ransomware tested  

---

## Further Reading
- *MITRE ATT&CK* — Techniques: T1486 (Data Encrypted for Impact)  
- *No More Ransom Project* — Free decryptor repository and prevention tips  

---

## **Author**

👩‍💻 **Chukwu PraiseGod**  
Follow my journey: [X](https://x.com/chukwupg) | [LinkedIn](https://linkedin.com/in/chukwupg)  
