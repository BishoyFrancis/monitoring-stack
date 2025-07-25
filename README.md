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

📊 Access the Tools
Grafana → http://localhost:3000
Username: admin | Password: admin

Prometheus → http://localhost:9090

Alertmanager → http://localhost:9093

📂 Project Structure
bash
Copy
Edit
monitoring-stack/
├── docker-compose.yml
├── prometheus/
│   └── prometheus.yml
├── grafana/
│   └── dashboards/
├── alertmanager/
│   └── alertmanager.yml
└── exporters/
    └── node-exporter/
📈 Sample Dashboards & Alerts
🖥️ Grafana
CPU, Memory, Disk Usage

Docker Container Health

🚨 Alerts
High CPU usage

Node down

Disk > 90%

(Customize and expand based on your needs!)

🧠 Learning Objectives
This project was built with the goal of:

Practicing real-world DevOps observability

Understanding how monitoring systems work together

Creating a portfolio-ready infrastructure setup

📚 Future Improvements
 Add Blackbox Exporter

 Add Loki for logs

 Add Kubernetes manifests

 Enable remote alerting channels (Slack, Email, etc.)

📘 License
This project is licensed under the MIT License.

Crafted with ❤️ by BishoyFrancis