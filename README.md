# baka-craft

Minecraft + Monitoring stack

## Setup

- Provide global `whitelist.json` and `ops.json` under `/srv/minecraft`
- Clone repo
- Run with `docker-compose up -d`

## Accessing Grafana Dashboard

Navigate to <http://localhost:3000> and log with "admin"/"admin". Password will be changed upon first login.

A dashboard called ["MC Monitor"](http://localhost:3000/d/PpzSgJAnk/mc-monitor?orgId=1) is provisioned and can be accessed in the [dashboards section](http://localhost:3000/dashboards). That dashboard uses the Prometheus [datasource](http://localhost:3000/datasources) that was provisioned.
