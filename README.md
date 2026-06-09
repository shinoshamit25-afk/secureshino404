# shinoshamit.dev — Cybersecurity Portfolio

> *"Findings don't get buried. The SIEM would have caught it on day one."*

A personal portfolio and professional presence for **Shino Shamit** — IT & Cybersecurity graduate, SOC analyst, detection engineer, and aspiring penetration tester based in Australia.

**[→ View Live Site](https://www.shinoshamit.online)**

---

## About This Project

This isn't a template. Built from scratch — hand-coded HTML and CSS, no frameworks, no dependencies, no bloat. Every design decision was intentional: monospaced typography to signal the discipline, terminal-green accent used exactly once as a signature, editorial grid layout that reads like a security report rather than a marketing page.

The goal: a portfolio that a cybersecurity recruiter can open, scan in 30 seconds, and know exactly who they're looking at and what that person can do.

---

## Featured Work

| # | Project | Stack |
|---|---------|-------|
| 01 | **Microsoft Sentinel SOC Monitoring Lab** — Cloud-native SOC on Azure, KQL detection queries, Windows Event Log analysis, threat intel dashboards | Azure · Sentinel · KQL · Log Analytics |
| 02 | **Critical Infrastructure Monitoring Lab** — Simulated brute-force & PowerShell abuse, ATT&CK-mapped detection rules | KQL · Windows Server · MITRE ATT&CK |
| 03 | **Cybersecurity Job Intelligence System** — Automated pipeline harvesting and ranking AU security roles via n8n, Google APIs, SerpAPI | n8n · OAuth2 · REST APIs · Automation |
| 04 | **Web & Network Security Labs** — SQLi, XSS, broken access control, PCAP analysis and IOC extraction | Burp Suite · Wireshark · OWASP Top 10 |
| 05 | **Penetration Testing Methodologies** — Structured study of industry frameworks via TryHackMe | Cyber Kill Chain · PTES · OSSTMM · OWASP WSTG · NIST SP 800-115 · ISSAF · MITRE ATT&CK |

---

## Technical Skills

```
Security Operations    →  Alert triage, incident investigation, threat hunting,
                          KQL detection engineering, STRIDE threat modelling,
                          MITRE ATT&CK mapping, NIST CSF, vulnerability assessment

Cloud & SIEM           →  Microsoft Sentinel, Microsoft Azure,
                          Log Analytics Workspace, Windows Event Logs

Offensive Tools        →  Burp Suite, Nmap, Wireshark, Metasploit, SQLmap

Languages & Scripting  →  PowerShell, KQL, SQL, REST APIs, OAuth2, n8n

IT & Infrastructure    →  Windows 10/11, macOS, Microsoft 365, TCP/IP, DNS, DHCP,
                          Linux & Windows Administration, Identity & Access Management
```

---

## Certifications & Community

- 🎓 **Master of Cybersecurity** — RMIT University (2024–2025)
- 🎓 **Bachelor of Computer Science** — Rajagiri School of Engineering and Technology (2019–2023)
- 📋 **CompTIA CySA+** — Currently preparing
- 🛡️ **Member** — Australian Information Security Association (AISA)
- 🎤 **Session Host** — Australian Cybersecurity Conference 2025, Canberra & Melbourne
- 💻 **Active learner** — TryHackMe (Penetration Testing pathways)

---

## Site Architecture

```
index.html          # Entire site — self-contained, zero dependencies
│
├── Nav             # Fixed terminal-style navigation
├── Hero            # whoami prompt + role summary
├── About           # Bio, current stack, daily tools
├── Skills          # Three-column: SecOps / Cloud & Tools / IT & Scripting
├── Projects        # Five project cards with technique highlights
├── Experience      # TeckNova IT Solutions internship + Mercy Place
├── Education       # Master's + Bachelor's degrees
└── Contact         # All channels + resume link
```

**Design decisions:**
- Zero external JS frameworks — vanilla HTML/CSS only
- Photo embedded as base64 — fully self-contained single file
- `DM Mono` for display type (terminal feel) + `Inter` for body (readability)
- `#00e87a` terminal green used sparingly — nav brand, section numbers, highlights only
- Responsive down to mobile, `prefers-reduced-motion` respected

---

## Run Locally

No build step. No package manager. Just open it.

```bash
git clone https://github.com/shinoshamit25-afk/shinoshamit25-afk.github.io.git
cd shinoshamit25-afk.github.io
open index.html        # macOS
# or just drag index.html into any browser
```

---

## Contact

| Channel | Link |
|---------|------|
| Email | [shinoshamitau@outlook.com](mailto:shinoshamitau@outlook.com) |
| LinkedIn | [linkedin.com/in/shino-shamit](https://www.linkedin.com/in/shino-shamit/) |
| GitHub | [github.com/shinoshamit25-afk](https://github.com/shinoshamit25-afk) |

Open to **SOC analyst, detection engineering, IT support, and junior pentesting roles** across Australia — remote or on-site.

---

<sub>Built without a template. Deployed on GitHub Pages. Signal is monitored.</sub>
