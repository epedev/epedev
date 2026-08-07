<h1 align="center">epedev</h1>

<p align="center">
  <strong>Offensive Security Researcher — Web App Security | Recon | Threat Intelligence</strong>
</p>

<p align="center">
  <a href="https://epedev.github.io">portfolio</a> ·
  <a href="https://github.com/epedev">github</a>
</p>

---

## About

Self-directed offensive security researcher based in Addis Ababa. Focused on
web application security, reconnaissance, and decoy infrastructure. Working
toward INSA and Ethio-CERT.

Bug bounty hunting on Bugcrowd, homelab-driven infra work, and building
privacy-first AI tooling on my own data instead of third-party services.

---

## Flagship Project — Honeypot Intelligence Platform

Decoy infrastructure and threat-classification pipeline built to collect and
categorize live attack traffic at a scale relevant to CERT-level operations.

**What it does**

* Flask decoy on Azure with bait routes (fake admin login, `.env`,
  `.git/config`, IDOR-shaped API)
* Structured JSON logging, rsync'd to a homelab node for ingestion
* Postgres ingestion pipeline with dedup logic
* Threat categorization extended via SQL passes — PHPUnit eval-stdin RCE,
  ThinkPHP invokefunction, CGI-bin traversal, GeoServer/Hikvision/D-Link
  CVE probes, MCP/SSE fingerprinting, and more
* Four-panel Grafana dashboard for attack trend visualization
* Dead-man's-switch alerting on ingestion staleness, wired to Discord

**Stack**

* Flask
* Postgres
* Docker
* Grafana
* systemd
* psycopg2

---

## Currently Learning

* Advanced web application security
* Reconnaissance methodologies
* Threat intelligence analysis
* Security automation with Python

---

## Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=bash,linux,python,js,nextjs,nodejs,mongodb,mysql,git" />
</p>

### Security Tools

* Burp Suite
* Nmap
* Wireshark
* Linux CLI

---

## GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=epedev&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=epedev&theme=tokyonight&hide_border=true" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=epedev&layout=compact&theme=tokyonight&hide_border=true" />
</p>
