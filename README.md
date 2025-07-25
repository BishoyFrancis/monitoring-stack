# 🚀 Monitoring Stack — Prometheus, Grafana, and Alertmanager

![License](https://img.shields.io/badge/license-MIT-blue.svg)  
**Author:** [BishoyFrancis](https://github.com/BishoyFrancis)  
**Repo:** `monitoring-stack`

---

## 📸 Overview

This project is a production-ready **monitoring and alerting stack** built using:
- **Prometheus** for metrics collection
- **Grafana** for powerful visual dashboards
- **Alertmanager** for alert routing (Slack/email/Telegram)

> 🐳 Powered by Docker Compose — ideal for local development and small-scale deployments.

---

## 🎯 Features

✅ Easy Docker-based deployment  
✅ Pre-configured Grafana dashboards  
✅ Alertmanager integration with sample alerts  
✅ Clean, modular config structure  
✅ Ready to plug into any service!

---

## 🛠️ Stack Components

| Component     | Purpose                              |
|---------------|--------------------------------------|
| Prometheus    | Metrics collection & scraping        |
| Node Exporter | Server-level metrics exporter        |
| Grafana       | Metrics visualization & dashboards   |
| Alertmanager  | Alerts routing & notifications       |

---

## 🚀 Getting Started

### 🔧 Requirements
- Docker
- Docker Compose

### 🧪 Run the Stack
```bash
git clone https://github.com/BishoyFrancis/monitoring-stack.git
cd monitoring-stack
docker-compose up -d
```
---

## 🛠️ Access the Tools

| Tool          | URL                      | Default Credentials       |
|---------------|---------------------------|---------------------------|
| Grafana       | [http://localhost:3000](http://localhost:3000) | `admin` / `admin`         |
| Prometheus    | [http://localhost:9090](http://localhost:9090) | -                         |
| Alertmanager  | [http://localhost:9093](http://localhost:9093) | -                         |

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
└── exporters/
└── node-exporter/


---

## 📊 Sample Dashboards & Alerts

### 🖥️ Grafana Dashboards
- CPU, Memory, and Disk Usage
- Docker Container Health

### 🚨 Alertmanager Alerts
- High CPU usage
- Node down
- Disk usage > 90%

_(Customize and expand based on your needs!)_

---

## 🧠 Learning Objectives

This project was built with the goal of:

- Practicing real-world **DevOps observability**
- Understanding how monitoring systems integrate and operate
- Creating a **portfolio-ready** monitoring infrastructure

---

## 📚 Future Improvements

- ➕ Add Blackbox Exporter for endpoint probing
- 📦 Add Loki for centralized log collection
- ☸️ Add Kubernetes manifests for production deployment
- 📬 Integrate remote alerting channels (Slack, Email, etc.)

---

## 📘 License

This project is licensed under the **MIT License**.

---

> Crafted with ❤️ by [BishoyFrancis](https://github.com/BishoyFrancis)
