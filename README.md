# Hi, I'm Zaid 👋

Cybersecurity student at the University of Petra (Amman, Jordan), building security tooling for coursework and full production systems solo on the side.

- 🔐 Rooted a VulnHub box end to end (SeedDMS exploit chain → privilege escalation) — [write-up & box](https://www.vulnhub.com/entry/hack-me-please-1,731/)
- 🛠️ Building and maintaining **Kanz Flights**, a Windows desktop booking & accounting system for a travel agency (17 releases and counting)
- 🌐 Built **kanzland-triathlon26.com** solo — the official registration/booking site for the [2026 Asia Triathlon Sprint Championships](https://triathlon.org/events/2026-asia-triathlon-sprint-championships-aqaba), a World Triathlon-sanctioned event
- 📫 Reach me at zaidnr@outlook.com

---

### Offensive security

- **PleaseHackMe: 1 (VulnHub)** — recon, exposed SeedDMS install, leaked DB creds, admin hash swap, PHP web shell RCE, sudo misconfig, root. [Box](https://www.vulnhub.com/entry/hack-me-please-1,731/)
- Identified a Cisco Umbrella phishing false-positive blocking a production domain for an international federation partner; verified it was clean via VirusTotal (0/89 vendors flagged), then filed and closed a Cisco Talos reputation-dispute ticket to get it reclassified

### Network & Security Programming (3-phase project)

A Python project spanning reconnaissance, offensive tooling, and defensive cryptography.

| Phase | Repo | What it does |
|---|---|---|
| 1 | [NetworkTool](https://github.com/Zaid-Alrefai/NetworkTool) | Multithreaded TCP port scanner (sockets, `ThreadPoolExecutor`), thread-safe logging with auto-archiving |
| 2 | [OffensiveToolkit](https://github.com/Zaid-Alrefai/OffensiveToolkit) | Automated recon (DNS/WHOIS/banner grabbing/subdomain brute-force), FTP/SSH module with brute-force-style rate limiting, sandboxed reverse-shell demo |
| 3 | [DefensiveToolkit](https://github.com/Zaid-Alrefai/DefensiveToolkit) | AES-256-GCM encrypted client-server comms layered on the Phase 1 scanner, plus a vulnerability audit tool and a steganography tool |

### Independent software

- **[Kanz Flights](https://github.com/Zaid-Alrefai/kanz-flights-updates/releases)** — travel agency block/charter booking & accounting system. Agency sub-accounts and self-service portal, running-balance statements, per-passenger tax handling, e-ticket + manifest exports (PDF/Excel/CSV), installer-based self-update. Built and maintained solo.
- **kanzland-triathlon26.com** — team registration and hotel/transfer/visa booking platform for a World Triathlon-sanctioned continental championship. Built solo; most of the engineering effort is in the admin dashboard, built for KanzLand and Triathlon Jordan to manage registrations, bookings, and event logistics.

### Also on the coursework side

- SOC/detection-engineering project — Windows endpoint monitoring with Sysmon, MITRE ATT&CK mapping, custom detection rules

---

### Stack

`Python` · `Sockets & Threading` · `AES-256-GCM / Applied Cryptography` · `OWASP ZAP` · `Sysmon & MITRE ATT&CK` · `Kali Linux` · `Git & GitHub`

![GitHub stats](https://github-readme-stats.vercel.app/api?username=Zaid-Alrefai&show_icons=true&theme=default&hide_title=false)
