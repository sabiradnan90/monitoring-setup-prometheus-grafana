# Monitoring Setup with Prometheus, Grafana, Node Exporter & cAdvisor

This repository contains:
- 📑 Word report documenting the full setup
- ⚙️ Prometheus configuration (`prometheus.yml`)
- 📦 cAdvisor and Node Exporter setup details
- 📈 Grafana alert rules and email integration

## Alerts Implemented
- High CPU usage (>70%)
- Low memory (<20%)
- Container not running (1 min)

## How to Use
1. Deploy Prometheus with the included config
2. Run Node Exporter & cAdvisor
3. Add Prometheus as a Grafana datasource
4. Import alert rules & configure email notifications
