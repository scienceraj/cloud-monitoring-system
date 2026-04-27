# 🚀 Real-Time Cloud Infrastructure Monitoring System

## 📌 Overview
This project is a real-time cloud monitoring system that collects system metrics, visualizes them through dashboards, generates alerts, and performs centralized log analysis.

It is built using modern DevOps tools such as **Prometheus, Grafana, Alertmanager, and ELK Stack**.

---

## 🎯 Features

- 📊 Real-time monitoring (CPU, Memory, Disk, Network)
- 🚨 Automated alerting system
- 📧 Email notifications (FIRING & RESOLVED)
- 📈 Interactive Grafana dashboards
- 📂 Centralized log monitoring using ELK Stack
- 🐳 Docker-based deployment

---

## 🛠️ Technologies Used

- Prometheus
- Grafana
- Alertmanager
- Elasticsearch
- Logstash
- Kibana
- Docker & Docker Compose
- Ubuntu (VMware)

---

## 🏗️ System Architecture

![Architecture](your-architecture-image.png)

👉 Replace this with your architecture diagram screenshot.

---

## ⚙️ Project Structure
cloud-monitoring/
├── docker-compose.yml
├── prometheus/
│ ├── prometheus.yml
│ └── alert.rules.yml
├── alertmanager/
│ └── alertmanager.yml
├── logstash/
│ └── pipeline/
│ └── logstash.conf


---

## 🚀 Setup Instructions

### 1. Install Docker
```bash
sudo apt update
sudo apt install docker.io -y
2. Install Docker Compose
sudo apt install docker-compose -y
3. Run Project
docker-compose up -d

##🌐 Access Services
Service	URL
Grafana		http://localhost:3000

Prometheus	http://localhost:9090

Alertmanager	http://localhost:9093

Kibana	http://localhost:5601

🧪 Testing
Unit Testing ✔
Integration Testing ✔
Stress Testing ✔
ELK Stack Testing ✔
📈 Results
Real-time monitoring achieved
Alerts triggered within seconds
Logs processed efficiently
System stable under load
🔮 Future Scope
Cloud deployment (AWS/Azure)
Kubernetes monitoring
AI-based anomaly detection
Mobile dashboard
👨‍💻 Author

Shubham Raj
MCA Final Year Student

⭐ Conclusion

This project demonstrates how modern monitoring tools can be integrated to build a scalable, real-time cloud monitoring system.
