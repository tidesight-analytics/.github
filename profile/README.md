# Tidesight 🌊

**Self-hosted, privacy-focused web analytics that keeps every raw hit.**

[![Website & Demo](https://img.shields.io/badge/Live%20Demo-Tidesight-brightgreen?style=for-the-badge)](https://tidesight-analytics.github.io/demo/#/overview?site=demo)
[![Website](https://img.shields.io/badge/Website-tidesight--analytics.github.io-blue?style=for-the-badge)](https://tidesight-analytics.github.io/)
[![GitHub](https://img.shields.io/badge/GitHub-Repository-darkblue?style=for-the-badge&logo=github)](https://github.com/tidesight-analytics/tidesight-analytics.github.io)

---

### What is Tidesight?

Most web analytics platforms either aggregate your data into summaries and discard the raw hits, or require heavy infrastructure (Docker, Node, PostgreSQL, ClickHouse).

Tidesight is designed to be self-hosted on inexpensive shared hosting (such as Dreamhost, cPanel, or standard VPS) using only **Python's standard library**, **SQLite**, and **cron**:

- **Every Raw Hit Preserved:** Pageviews, custom events, performance metrics, and client errors are stored raw so you never lose historical granularity.
- **Rich Insights:** Full dashboard with realtime visitors, conversion goals, geographic distribution, UTM campaign tracking, Core Web Vitals, and browser error tracking.
- **Lightweight Tracker:** Fast, asynchronous JavaScript tracker under 20 KB gzip with zero external runtime dependencies.
- **Self-Hosted Simplicity:** No database servers or Node runtime required. Deploy in minutes via FastCGI/WSGI on any host with Python 3.9+.

### 🔗 Quick Links

- **Documentation & Deployment Guide:** [Deployment on Dreamhost and standard shared hosting](https://github.com/tidesight-analytics/tidesight-analytics.github.io/blob/main/docs/deploy-dreamhost.md)
- **Interactive Live Demo:** [tidesight-analytics.github.io/demo/](https://tidesight-analytics.github.io/demo/)
- **Project Repository:** [tidesight-analytics/tidesight-analytics.github.io](https://github.com/tidesight-analytics/tidesight-analytics.github.io)

---

<sub>An open-source project created and maintained by [@mayerwin](https://github.com/mayerwin).</sub>
