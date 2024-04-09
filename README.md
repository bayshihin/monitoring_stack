# Grafana based monitoring stack

Prometheus, Node Exporter, Loki v2.9.5 and Promtail v.2.9.5 included. Compactor enabled, grafana data mounted.

All you need to do is clone the repository and run:
```
docker volume create grafana-data
```
And then:
```
docker compose up -d
```

Enjoy!
