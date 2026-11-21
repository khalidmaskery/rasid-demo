# Rasid (راصد) — ASMaaS Interactive Demo

Single-file interactive demo of **Rasid**, an External Attack Surface Management as a Service (ASMaaS) platform for Omani and GCC enterprises.

**Live demo:** https://khalidmaskery.github.io/rasid-demo/

## Views
1. Executive Overview — risk score gauge, KPIs, severity breakdown, perimeter alerts
2. Attack Path Graph — critical path highlight and tap-to-inspect nodes
3. Asset Inventory — searchable and filterable subdomains, IPs, ports, WAF/CDN, SSL status
4. Findings & Triage — CVSS, CVE/CWE, MITRE ATT&CK, status toggles, bilingual remediation
5. Live Demo Scan — simulated subfinder → dnsx → httpx → nuclei run that updates the dashboard
6. Executive Report — printable CISO summary (Print / Save PDF)

EN | عربي toggle with full RTL/LTR layout. Mobile-first.

## Run locally
Open `index.html` in any modern browser. No build step or backend.

> All data is simulated for demonstration (`oman-logistics-demo.om`). No real systems were scanned.
