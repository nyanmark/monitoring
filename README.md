## Monitoring Docker Compose
#### Version 1.3
#### Using Grafana, Prometheus and Loki

### Change Log
#### Version 1.0 - Created Compose File
#### Version 1.1 - Added Consul for KV store and Redis for caching Loki
#### Version 1.2 - Environment variables
#### Version 1.3 - Added Alert Manager

### To Do
#### Alert Manager

### Usage
#### apt install haveged
#### docker plugin install grafana/loki-docker-driver:latest --alias loki --grant-all-permissions
#### git clone this repo
#### mv example_env .env
#### set your own values
