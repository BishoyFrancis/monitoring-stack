# 📈 Monitoring Stack

A plug-and-play observability stack using **Prometheus**, **Grafana**, **Alertmanager**, and **Blackbox Exporter** — perfect for learning, development, and showcasing your DevOps skills.

---

## 🚀 Stack Overview

- **Prometheus** – Metrics collection & querying
- **Grafana** – Dashboards & visualization
- **Alertmanager** – Alerts & notifications
- **Node Exporter** – System metrics from your host machine
- **Blackbox Exporter** – Endpoint and uptime probing (HTTP, TCP, ICMP, etc.)

---

## 🛠️ Access the Tools

| Tool               | URL                                  | Default Credentials       |
|--------------------|---------------------------------------|---------------------------|
| Grafana            | [http://localhost:3000](http://localhost:3000) | `admin` / `admin`         |
| Prometheus         | [http://localhost:9090](http://localhost:9090) | -                         |
| Alertmanager       | [http://localhost:9093](http://localhost:9093) | -                         |
| Blackbox Exporter  | [http://localhost:9115](http://localhost:9115) |

---

## 📂 Project Structure

monitoring-stack/
├── docker-compose.yml
├── prometheus/
│ └── prometheus.yml
├── grafana/
│ └── dashboards/
├── alertmanager/
│ └── alertmanager.yml
├── exporters/
│ ├── node-exporter/
│ └── blackbox-exporter/


---

## 📊 Sample Dashboards & Alerts

### 🖥️ Grafana Dashboards
- CPU, Memory, and Disk Usage
- Docker Container Health
- Endpoint Latency / HTTP Probes (via Blackbox Exporter)

### 🚨 Alertmanager Alerts
- High CPU usage
- Node down
- Disk usage > 90%
- Endpoint down / Unreachable (Blackbox alerts)

_(Customize and expand based on your needs!)_

---

## 🧠 Learning Objectives

This project was built with the goal of:

- Practicing real-world **DevOps observability**
- Understanding how monitoring systems integrate and operate
- Creating a **portfolio-ready** monitoring infrastructure

---

## 📚 Future Improvements

- 📦 Add Loki for centralized log collection
- ☸️ Add Kubernetes manifests for production deployment
- 📬 Integrate remote alerting channels (Slack, Email, etc.)

---

## 📘 License

This project is licensed under the **MIT License**.

---

> Crafted with ❤️ by [BishoyFrancis](https://github.com/BishoyFrancis)
