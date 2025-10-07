# 🌐 Safe Browsing

**Who this is for:** Anyone who uses the web — from casual browsers to professionals.  
This guide covers how to spot unsafe sites, harden your browser, and manage downloads safely.

---

## Overview
Browsing the web is routine, but attackers use websites, ads, and links to spread malware, steal credentials, or trick you into exposing personal info. Practicing safe browsing habits reduces the risk of drive-by downloads, malvertising, typosquatting, and other web-based threats.

---

## Common threats
- **Malicious websites & drive-by downloads:** Websites that automatically attempt to install malware.  
- **Malvertising:** Ads that deliver malware or redirect to malicious pages.  
- **Typosquatting / homograph attacks:** Domains that look like real sites (e.g., g00gle.com, or using similar Unicode).  
- **Fake downloads / bundles:** Software installers that include unwanted programs or malware.  
- **Phishing pages:** Sites that mimic real services to harvest credentials.  
- **Untrusted certificates / mixed content:** Sites that appear secure but contain insecure elements.

---

## Practical safe-browsing habits
1. **Check the URL before you click or enter credentials.**  
   - Look for subtle typos, extra words, or unexpected domains.  
   - If a message claims to be from a bank, confirm the official domain via a separate search or your bookmarks.

2. **Prefer HTTPS (the padlock).**  
   - HTTPS protects data in transit. A padlock alone doesn’t guarantee safety, but absence of HTTPS is a red flag.

3. **Hover links to preview destinations.**  
   - On desktop, hover to see the actual link. On mobile, long-press to preview if available.

4. **Avoid downloading software from unknown sites.**  
   - Use official vendor pages or trusted app stores. Verify checksums when provided.

5. **Be cautious with pop-ups and fake system dialogs.**  
   - Legitimate sites rarely ask you to install system-level software via pop-ups. Close suspicious pop-ups, don’t accept unexpected prompts.

6. **Use bookmarks for important sites.**  
   - Avoid clicking links in email for critical services (banking, government) — use bookmarks.

7. **Keep your browser and extensions updated.**  
   - Updates frequently patch security flaws.

8. **Use a separate browser/profile for sensitive tasks.**  
   - Consider a clean browser profile for banking and another for general browsing to reduce exposure.

---

## Browser hardening (settings to check)
- **Auto-update enabled** for browser and extensions.  
- **Block third-party cookies** (or at least block trackers).  
- **Enable pop-up blocking** and disable auto-downloads.  
- **Disable Flash and legacy plugins** (if still available).  
- **Enable site isolation / sandbox features** if offered.  
- **Clear cache & cookies periodically**, or use private mode for one-off sessions.

---

## Helpful extensions & tools
*(Only install from official extension stores and review permissions)*  
- **uBlock Origin** — blocks ads and many malicious scripts.  
- **Privacy Badger** — blocks invisible trackers.  
- **HTTPS Everywhere** or use built-in HTTPS upgrades in modern browsers.  
- **Password manager extension** — for filling unique credentials safely (see `general/passwords.md`).  
- **NoScript (advanced users)** — blocks JavaScript by default (high security, needs configuration).  
- **Browser’s built-in password breach alerts** — enable if available.

---

## VPNs, Proxies, and Tor — short guide
- **VPN:** Encrypts traffic to the VPN provider. Good for using untrusted networks but choose a reputable provider. VPN does not make you anonymous from the sites you visit.  
- **Tor Browser:** For stronger anonymity and censorship resistance; it’s slower and some sites block Tor exit nodes. Use the official Tor Browser and follow its guidelines.  
- **Proxy:** Often less secure than VPNs and may not encrypt traffic.

---

## Safe download practices
- Download from **official vendor pages** or trusted repositories.  
- Avoid freeware bundles that add additional software.  
- Scan suspicious downloads with your antivirus or upload to an online scanner (if comfortable sharing the file).
- Check **digital signatures or checksums** (SHA256/MD5) if provided.

---

## Recognizing compromised or phishing pages
- Domain mismatch (e.g., service.example-login.com versus example.com).  
- Misspellings, poor grammar, or low-quality images.  
- Fake SSL warnings or self-signed certificates for sites that should have valid certs.  
- Unexpected credential prompts from sites you were already logged into.

---

## If you suspect your browser or system is compromised
1. Disconnect from the network (temporarily) to stop further communication.  
2. Run a full antivirus/malware scan with reputable tools.  
3. Clear browser cache, cookies, and saved site data.  
4. Reset the browser to default settings or reinstall if needed.  
5. Change passwords (preferably from another device you trust) and enable 2FA.  
6. Restore from clean backups if malware persists.

---

## Quick checklist
- [ ] Verify URLs before entering credentials  
- [ ] Only download from official sources and verify checksums when possible  
- [ ] Enable browser & extensions auto-update  
- [ ] Use a trusted content blocker/anti-tracking extension  
- [ ] Avoid using public Wi-Fi for sensitive tasks (or use a trusted VPN)  
- [ ] If you suspect a breach, act fast.

---
