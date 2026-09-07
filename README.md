# Daily-Hunt

**IOCs collected during day-to-day cyber threat investigations**

A living collection of Indicators of Compromise (IOCs) and related intelligence gathered while tracking ransomware groups, malware families, threat actors, and ongoing campaigns.

> Maintained by [The Raven File](https://theravenfile.com)

---

## What's Inside

This repository contains structured notes and observables for dozens of ransomware families, loaders, backdoors, and campaigns.  

Each entry typically includes:

- **Hashes** (mostly MD5, sometimes others)
- **TOR / Onion domains** (DLS, negotiation panels, etc.)
- **IP addresses** and related infrastructure
- **Technical observations** (encryption methods, mutexes, file extensions, compile paths, etc.)
- **Victimology / activity notes**
- **Contact methods** used by the groups (TOX, Session, email, Telegram, etc.)
- Occasional links to deeper analysis on [theravenfile.com](https://theravenfile.com)

Most entries are individual files named after the threat (e.g. `Nightspire Ransomware`, `LockBit 5.0 Ransomware`, `Lumma C2`). Some campaigns have their own folders.

---

## How to Use

- Browse the file list to find a specific ransomware family or malware.
- Copy hashes, domains, or IPs into your detection tools, threat intel platforms, or blocklists.
- Cross-reference with your own telemetry.
- Check the linked blog posts on [theravenfile.com](https://theravenfile.com) for fuller context and analysis.

**Tip:** Sort the repository by "Last updated" to see the most recently observed threats first.

---

## Important Disclaimer

- These IOCs are collected from open-source research, public samples, and day-to-day investigations.
- They are shared **as-is** for defensive and research purposes only.
- Always verify indicators in your own environment before taking action.
- False positives are possible. Use with proper context and validation.
- This repository is **not** affiliated with any commercial threat intelligence vendor.

---

## Related Work

- Main blog & deeper investigations: [theravenfile.com](https://theravenfile.com)
- Other repositories by the same author:
  - [YARA-RULES](https://github.com/TheRavenFile/YARA-RULES)
  - [IOC](https://github.com/TheRavenFile/IOC)
  - [LEAKS](https://github.com/TheRavenFile/LEAKS)
  - [THREAT-ACTORS](https://github.com/TheRavenFile/THREAT-ACTORS)

---

## Updates

This repository is updated regularly as new samples and infrastructure are observed.  

Feel free to star or watch the repo if you find it useful.

---

## Contact

- Website: [theravenfile.com](https://theravenfile.com)
- Email: theravenfile@gmail.com

---

**Stay sharp. Hunt daily.**
