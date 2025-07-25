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

# 📊 Access the Tools
| Tool         | URL                      | Credentials       |
|--------------|--------------------------|-------------------|
| Grafana      | http://localhost:3000    | admin / admin     |
| Prometheus   | http://localhost:9090    | No auth required  |
| Alertmanager | http://localhost:9093    | No auth required  |

<pre><code>```bash monitoring-stack/ ├── docker-compose.yml ├── prometheus/ │ └── prometheus.yml ├── grafana/ │ └── dashboards/ ├── alertmanager/ │ └── config.yml ``` </code></pre>