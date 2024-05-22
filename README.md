## Description

Monitoring stack for XCP-ng hosts that runs a simple python script and scrapes the RRD stats to a prometheus instance. 
Run docker-compose up to start the stack after defining all the required information in the ENV file. 

Scrapes prometheus endpoints and displays the metrics using Grafana. The metrics are persisted in InfluxDB shipped with Telegraf. 

### Grafana
A Grafana dashboard is [available here](https://grafana.com/grafana/dashboards/16588) (id 16588), which graphs most of the critical metrics gathered by this exporter.

### [Pics]
![monitoring](https://github.com/AlexTzk/xen-xcp-ng-grafana-prometheus-stack/assets/138780223/760d2291-e89d-4b56-8ca8-51ccfcba7de7)

