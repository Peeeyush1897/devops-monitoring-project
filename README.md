
##  Project Overview
This project demonstrates a complete monitoring solution using Prometheus and Grafana to track system and application metrics in real time.

## 🛠 Tech Stack
- Prometheus
- Grafana
- Docker
- Docker Compose

## ⚙️ Setup Instructions

### 1. Clone Repository
git clone https://github.com/YOUR_USERNAME/devops-monitoring-project.git

### 2. Run Project
docker compose up -d

### 3. Access Services
- Prometheus → http://localhost:9090
- Grafana → http://localhost:3000

##  Grafana Login
- Username: admin
- Password: admin

##  Features
- Real-time monitoring
- Dashboard visualization
- Service health tracking

##  Dashboard Example
- Service Status using PromQL query: `up`

## Use Case
Used for monitoring DevOps pipelines, servers, and applications.

## Future Enhancements
- Node Exporter (CPU, RAM, Disk monitoring)
- Alertmanager (alerts)
- AWS deployment
