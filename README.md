# Grafana based monitoring stack

Prometheus, Node Exporter, Loki and Promtail included. Compactor enabled, grafana data mounted.

All you need to do is clone the repository and run:
```
docker volume create grafana-data
```
And then:
```
docker compose up -d
```

Enjoy!
