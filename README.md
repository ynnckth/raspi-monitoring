# Monitoring

*Dockerized Prometheus & Grafana monitoring stack*

Run:

> `$ docker-compose up -d`

- Prometheus: http://localhost:9090
- Grafana: http://localhost:3000

#### Configure Grafana

- Add prometheus data source (url = http://prometheus:9090)
- Import [node exporter dashboard template](https://grafana.com/grafana/dashboards/1860) and select prometheus as data source
