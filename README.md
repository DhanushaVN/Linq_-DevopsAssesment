# Linq_-DevopsAssesment
# Node Exporter Monitoring Stack with Prometheus and Grafana

This project sets up a complete monitoring solution using Prometheus, Node Exporter, and Grafana to monitor system metrics with a custom dashboard.

## Prerequisites

- Docker installed on your system
- Docker Compose installed
- Ports 9090, 9100, and 3000 available on your host machine

## Installation

1. Clone this repository
2. Run: `docker-compose up -d`
3. Access the services:
   - Prometheus: http://localhost:9090
   - Grafana: http://localhost:3000 (admin/admin)

## Dashboard Features

- CPU Usage monitoring
- Memory Usage tracking
- Disk space visualization
- Network traffic analysis
- System load metrics

## Security Note

For production use, change the default Grafana credentials and consider adding authentication.
