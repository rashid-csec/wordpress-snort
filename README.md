# WordPress IDS/IPS Security Lab

> **Author**: Rashid  
> **Location**: Dubai, UAE  
> **Date**: June 2025
> # WordPress Snort Security Lab by Rashid

This public GitHub repository demonstrates a WordPress security lab integrating Snort IDS, Fail2Ban IPS, ELK Stack, and Splunk on Ubuntu.


A complete cybersecurity project integrating WordPress with Snort IDS, Fail2Ban IPS, Splunk, and the ELK Stack (Elasticsearch, Logstash, Kibana, Filebeat) for real-time log monitoring and attack detection on an Ubuntu server.

---

## 🧠 Project Overview

This project simulates a real-world web server hosting a WordPress site and demonstrates how to secure it using open-source tools. It includes intrusion detection using **Snort**, log forwarding using **Filebeat**, and real-time visualization via **Splunk** and **ELK**. It also implements **Fail2Ban** to automatically ban malicious IPs based on alert patterns.

---

## 🎯 Objectives

- Deploy and configure a secure WordPress environment on Ubuntu.
- Detect intrusion attempts such as SSH brute-force, SQL Injection, and XSS.
- Forward and visualize logs using ELK and Splunk.
- Ban offending IPs automatically using Fail2Ban.
- Simulate attacks to test detection and response systems.

---

## ⚙️ Tools & Technologies Used

| Tool          | Role                                 |
|---------------|--------------------------------------|
| WordPress     | CMS hosted on Apache                 |
| Apache2       | Web server                           |
| MySQL         | Database backend                     |
| Snort         | Intrusion Detection System (IDS)     |
| Fail2Ban      | Intrusion Prevention System (IPS)    |
| ELK Stack     | Log Monitoring & Visualization       |
| - Elasticsearch | Log storage/search engine        |
| - Logstash      | Log ingestion/processing         |
| - Kibana        | Dashboard for ELK visualization  |
| - Filebeat      | Log shipper for ELK              |
| Splunk        | Additional log visualization         |
| Ubuntu 24.04  | Base OS                              |

---

