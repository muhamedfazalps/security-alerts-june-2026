# High-Impact Security Vulnerabilities — June 15-22, 2026

Compiled by Hermes Agent Open Source Security Monitoring

## Critical (Patch Immediately)

### Squidbleed (CVE-2026-47729)
- **Type:** Heartbleed-style memory leak in Squid Proxy
- **Affected:** Every Squid version in default configuration
- **Impact:** Session tokens, passwords, private keys extracted from memory
- **Fix:** Update Squid to latest patched version
- **Source:** r/netsec, blog.calif.io (June 19, 2026)

### FortiBleed
- **Type:** Credential leak for Fortinet devices
- **Affected:** 80,000+ Fortinet FortiGate firewalls and SSL VPN gateways
- **Impact:** Stolen credentials tested by Russian-speaking threat actors
- **Fix:** Change all passwords, enable MFA, check for unauthorized admin accounts
- **Source:** CISA, BleepingComputer (June 19-22, 2026)

### OpenBSD 27-Year Auth Bypass
- **Type:** Remote authentication bypass in PPP stack
- **Affected:** OpenBSD since July 1999
- **Impact:** Bypass authentication, intercept PPPoE traffic
- **Fix:** Update to latest OpenBSD
- **Source:** blog.argus-systems.ai (June 16, 2026)

### Splunk Enterprise (Actively Exploited)
- **Type:** Critical vulnerability being exploited in the wild
- **Affected:** Splunk Enterprise
- **Impact:** Full access to security monitoring infrastructure
- **Fix:** Apply latest security patch (CISA deadline June 22)
- **Source:** CISA, BleepingComputer (June 19, 2026)

## High (Patch This Week)

### Gravity SMTP (CVE-2026-4020)
- **Type:** Unauthenticated information disclosure
- **Affected:** Gravity SMTP WordPress plugin (100,000+ sites)
- **Impact:** API keys, secrets, OAuth tokens exposed
- **Fix:** Update or deactivate plugin
- **Source:** Wordfence (June 20, 2026)

### Mastra AI Supply Chain Attack
- **Type:** Supply chain compromise via npm packages
- **Affected:** 140+ npm packages
- **Impact:** North Korean hackers compromised dependencies
- **Fix:** Run npm audit, update all dependencies
- **Source:** BleepingComputer, Microsoft (June 20, 2026)

### AryStinger Malware
- **Type:** Router malware building reconnaissance network
- **Affected:** 4,300+ routers with Realtek RTL819X chips
- **Impact:** Routers used for scanning and traffic tunneling
- **Fix:** Update firmware or replace router
- **Source:** The Hacker News (June 22, 2026)

### Prinz Eugen Ransomware
- **Type:** New ransomware prioritizing recent files
- **Affected:** Windows systems
- **Impact:** Encrypts recently modified files first, no ransom note
- **Fix:** Maintain offline backups, enable ransomware protection
- **Source:** BleepingComputer (June 20, 2026)

## Medium (Be Aware)

### Mitsubishi MAC-577IF-2E (CVE-2026-5667)
- **Type:** Unauthenticated remote control
- **Affected:** Mitsubishi WiFi adapters
- **Impact:** Remote attackers can control adapter
- **Fix:** Update firmware, isolate on separate network
- **Source:** r/netsec (June 18, 2026)

### OXLOADER/CastleStealer
- **Type:** Malware distributed via malicious Google Ads
- **Affected:** Anyone searching for developer tools
- **Impact:** Information stealing malware
- **Fix:** Download from official sites, use ad blocker
- **Source:** The Hacker News (June 22, 2026)

### Volume Booster Chrome Extension
- **Type:** Tracking code added to 2M-user extension
- **Affected:** Volume Booster Chrome extension users
- **Impact:** Browsing tracking across all websites
- **Fix:** Remove extension if not actively used
- **Source:** r/netsec (June 17, 2026)

---

## GitHub Issues Created

45 security alerts sent to affected repositories via GitHub issues.

Each issue includes: vulnerability type, impact, fix instructions, source citation, and support link.

## Support

If this alert helped you, consider supporting:
https://www.buymeacoffee.com/muhamedfazalps

---

*Compiled by Hermes Agent Open Source Security Monitoring*
*June 22, 2026*
