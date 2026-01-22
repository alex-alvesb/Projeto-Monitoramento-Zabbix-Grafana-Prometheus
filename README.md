# 📊 Projeto de Monitoramento com Zabbix, Grafana e Prometheus

Este repositório apresenta a implementação de um **ambiente completo de observabilidade**, utilizando **Docker Compose** em uma VM Debian para monitorar um **host Windows**, integrando métricas, logs e dashboards em tempo real.

---

## 🧱 Arquitetura do Projeto

- **VM Debian (Monitoramento)**
  - Zabbix Server
  - Grafana
  - Prometheus
  - Loki
  - Promtail
- **Host Windows (Monitorado)**
  - Zabbix Agent
  - Windows Exporter (Prometheus)

📌 Comunicação realizada via rede local entre a VM de monitoramento e o host Windows.

> 📷 Diagramas e imagens podem ser encontrados na pasta `docs/`.

---

## 🔧 Tecnologias Utilizadas

- Docker & Docker Compose
- Zabbix
- Grafana
- Prometheus
- Loki
- Promtail
- Windows Exporter
- Debian Linux
- Windows

---

## 📊 Dashboards Grafana

Todos os dashboards estão versionados em JSON para fácil reutilização:

- **Grafana + Zabbix**
  - Visão geral do host Windows
- **Grafana + Prometheus**
  - Windows Exporter Dashboard (compatível com v0.31+)

📁 Localização:
```text
grafana/dashboards/
