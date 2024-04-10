# Grafana based monitoring stack

Grafana (v10.4.0), Prometheus (v2.50.1), Node Exporter (v1.7.0), Loki (v2.9.5) and Promtail (v2.9.5) included. Compactor enabled, grafana data mounted.

All you need to do is clone the repository and run:
```
docker volume create grafana-data
```
And then:
```
docker compose up -d
```

Enjoy!
