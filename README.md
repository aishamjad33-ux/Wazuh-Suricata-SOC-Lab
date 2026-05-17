# 🛡️ SOC Detection Lab — Wazuh SIEM + Suricata IDS

![Platform](https://img.shields.io/badge/Platform-Rocky%20Linux%209.3-blue)
![Suricata](https://img.shields.io/badge/Suricata-8.0.4-orange)
![Wazuh](https://img.shields.io/badge/Wazuh-v4.14.4-red)
![Alerts](https://img.shields.io/badge/Alerts%20Generated-197-green)
![Status](https://img.shields.io/badge/Lab%20Status-Complete-brightgreen)

> **End-to-end SOC detection pipeline** integrating Suricata IDS with Wazuh SIEM.

**Prepared by:** Ayesha | Information Security Analyst
**Organization:** Vital Medicure Labs

![Table of Contents](1.jpeg)

## Lab Overview

This project demonstrates a complete **Security Operations Center (SOC) detection pipeline** built from open-source tools. Suricata 8.0 acts as the network IDS sensor on Rocky Linux, forwarding all alerts via `eve.json` to Wazuh SIEM. Two real attack scenarios were executed — Nmap stealth port scan and XSS web attack — both detected in real time.

### What Was Demonstrated
- ✅ Network-layer threat detection (Nmap SYN stealth scan → 195 alerts)
- ✅ Application-layer threat detection (XSS injection → 2 alerts)
- ✅ End-to-end SIEM integration via eve.json log forwarding
- ✅ Real-time alert visibility in Wazuh Discover dashboard
- ✅ Emerging Threats ruleset covering 50+ attack categories
