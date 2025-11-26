# 🚀 Grafana + Prometheus + Node Exporter Monitoring Setup (RHEL 9.x)

This repository provides a complete guide to deploy a monitoring stack using **Prometheus, Grafana, and Node Exporter** on **RHEL 9 / Rocky Linux 9 / AlmaLinux 9**.

---

## 📌 Architecture
[Linux Servers] → Node Exporter → Prometheus → Grafana

| Component | Purpose | Default Port |
|----------|----------|--------------|
| Node Exporter | Collects system metrics | `9100` |
| Prometheus | Stores metrics | `9090` |
| Grafana | Dashboard visualization | `3000` |
