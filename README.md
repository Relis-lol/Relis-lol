<div align="center">

# 👋 Hi, I'm Björn (Relis)

### Junior Cloud & Platform Operations

Linux-first IT career changer building practical systems with Docker, Python,
PostgreSQL, automation, monitoring and Azure fundamentals.

[![Portfolio](https://img.shields.io/badge/Professional_Portfolio-View_Live-2ea44f?style=for-the-badge&logo=githubpages&logoColor=white)](https://relis-lol.github.io/)

![Linux](https://img.shields.io/badge/Linux-Ubuntu_Server-E95420?logo=ubuntu&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-Compose-2496ED?logo=docker&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-16-336791?logo=postgresql&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-Fundamentals-0078D4?logo=microsoftazure&logoColor=white)
![Monitoring](https://img.shields.io/badge/Focus-Monitoring_%26_Automation-555555)

</div>

---

## About Me

I build complete, understandable systems rather than isolated coding
exercises.

My projects combine Linux administration, containerized services, backend
applications, databases, scheduled workers, monitoring, alerting, backups,
security controls and technical documentation.

I am currently preparing for my first professional role in:

- Cloud and Platform Operations
- Linux and Infrastructure Operations
- Junior DevOps
- Application and System Operations

My technical foundation is Linux, supported by practical work with Docker,
Python, PostgreSQL, Bash, networking and Azure fundamentals.

---

# Featured Project

## 🌐 EVE Trade Intelligence Platform

**Live, maintained and publicly accessible self-hosted data platform**

[![Live Platform](https://img.shields.io/badge/Live_Platform-eve--tradelooper.com-2ea44f?style=flat-square)](https://eve-tradelooper.com/)
[![Technical Repository](https://img.shields.io/badge/GitHub-Architecture_%26_Documentation-181717?style=flat-square&logo=github)](https://github.com/Relis-lol/homelab-hybrid-cloud-platform)

A self-hosted analysis and intelligence platform for EVE Online, built and
operated on my own Linux infrastructure.

The platform combines approximately 20 market, industry, navigation,
intelligence and PvE tools with a technical wiki and automated data pipelines.
It runs without user accounts, advertising or personal user tracking.

### Current production scale

- Approximately **7.5 million database rows written per day**
- **124.3 million live rows** in PostgreSQL
- **70 GB database** across **81 tables**
- Approximately **9,650 orchestrated import runs per day**
- **14 automated pipelines**
- **7 integrated external data sources**
- Approximately **30 external API endpoint integrations**
- Public production deployment live since **July 2026**

### Architecture

- Ubuntu Server
- Docker Compose
- FastAPI backend
- PostgreSQL 16
- Vanilla JavaScript frontend
- nginx reverse proxy
- Modular Python worker architecture
- Background killboard and RedisQ daemons
- Cloudflare DNS, proxying and TLS
- Azure Arc and Azure Monitor integration

### Automation and operations

- Incremental, rate-limit-aware API synchronization
- Scheduled market, map, news and intelligence pipelines
- `flock` protection against overlapping worker runs
- Automatic service recovery after host restarts
- Batch-based data retention and pruning
- Health checks and Discord alerting
- Daily off-volume PostgreSQL backups
- Automatic backup fallback after storage failure
- ESP32 hardware status dashboard

### Security and reliability

- HTTPS with Cloudflare origin certificates
- nginx reverse-proxy isolation
- Internal services restricted to Docker networks
- SSH-key authentication
- UFW and Fail2ban
- Environment-based credentials
- Token-protected write endpoints
- Request rate limiting
- Resource and backup-health monitoring
- Documented incident reviews and operational lessons learned

### Performance

- Approximately **80 ms** measured homepage response over HTTPS
- Approximately **1 ms** warm internal `/health` response
- Static frontend delivery through nginx
- Precomputed database snapshots for frequently requested data

➡️ **Repository and technical documentation:**  
https://github.com/Relis-lol/homelab-hybrid-cloud-platform

---

# Additional Projects

## 🚚 DispoHub

Open-source dispatch, driver and fleet-management system for small transport
companies, built with FastAPI, PostgreSQL, Docker, role-based permissions,
WebSocket chat, CSRF protection, multilingual driver interfaces and more than
148 automated tests.

➡️ https://github.com/Relis-lol/dispohub

---

## 👾 Cryptid Pet / Cryptid Arcade

Hardware and software project that turns an older Android smartphone into a
dedicated Tamagotchi-style device using HTML5, vanilla JavaScript, Android
WebView, local persistence, dynamic rendering and hardware sensor input.

➡️ https://github.com/Relis-lol/cryptid-pet

---

## 🛠️ Twitch Drops Fix for Chrome

Small Windows batch launcher that starts Twitch in a dedicated Chrome profile
with background throttling disabled, allowing Drops watch time to continue
tracking while the browser is not in the foreground.

➡️ https://github.com/Relis-lol/twitch-drops-fix-chrome

---

## 📚 Audible SQL Tracker

Personal SQL project for relational data modelling, structured purchase-history
storage and repeatable analytics queries using an independently maintained
Audible dataset.

➡️ https://github.com/Relis-lol/audible-sql-tracker

---

## 🤖 Bitburner Automation System

Archived JavaScript automation framework exploring distributed task
scheduling, dynamic resource allocation and autonomous coordination across
multiple nodes inside the Bitburner programming game.

➡️ https://github.com/Relis-lol/bitburner-automation-system

---

## Certification

### Microsoft Certified: Azure Fundamentals — AZ-900

Foundational knowledge of cloud concepts, Azure architecture, core services,
security, governance, management and pricing.

---

## Current Focus

- Deepening Linux administration skills
- Bash and Python automation
- Container deployment and operations
- Monitoring, logging and incident analysis
- Networking and infrastructure fundamentals
- Azure administration fundamentals
- Building a second production-focused portfolio project

---

<div align="center">

### Portfolio

https://relis-lol.github.io/

</div>
