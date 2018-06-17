# Prometheus-Grafana-Docker-stack

This is a Docker Compose stack for Prometheus/Grafana + Alertmanager mailing.

There is 3 volumes mounted: 

- Prometheus configuration 
- Grafana Dashboards and Datasources
- Alertmanager pre-configured alerting with gmail smtp server.

Just replace by your own the yml configuration files.
Grafana is set to load your json dashboards you just have to put in /grafana/provisioning/dashboards/

## Installation

Just clone it to your path.

## Start and stop

To start the services in background:

docker-compose up -d 

To stop the services:

docker-compose down


