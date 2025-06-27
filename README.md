# elk-lab-templates
A collection of configuration templates for setting up and testing the ELK stack (Elasticsearch, Logstash, Kibana, and Filebeat) in a containerized lab environment. Includes sample YAML files, Logstash pipelines, Filebeat inputs, and other useful resources for experimenting with and learning the ELK stack.
# ELK Lab Templates

A collection of configuration templates for setting up a test environment with the ELK stack: **Elasticsearch**, **Logstash**, **Kibana**, and **Filebeat**.

This repository is designed for learning, experimenting, and quickly launching a containerized ELK lab environment.

---

## 📦 Contents

- `docker-compose.yml` – container setup
- `logstash.conf` – example Logstash pipeline
- `filebeat.yml` – Filebeat configuration
- `elasticsearch.yml`, `kibana.yml` – optional settings
- `volumes/` – volume structure for persistent data
- `examples/` – sample input files and test scenarios

---

## 🚀 Quick Start

```bash
git clone https://github.com/nachszon/elk-lab-templates.git
cd elk-lab-templates
docker-compose up

Requirements

    Docker & Docker Compose

    RAM: minimum 4–8 GB for full stack

    Ensure ports 9200, 5601, etc. are available

📚 Purpose

This repository serves as a base for testing and learning the ELK stack. Feel free to use, modify, and extend these templates to suit your needs.

