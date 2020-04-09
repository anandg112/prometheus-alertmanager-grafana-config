# prometheus-alertmanager-grafana-config
Config files for Prometheus, Alert Manager and Grafana setup


### Sample PromQL commands

`avg by (instance) (irate(node_cpu_seconds_total{mode="user"}[30s]))*100`
