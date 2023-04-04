## Monitoring Docker Compose
### Version 1.5
#### Using Grafana, Prometheus and Loki

### Change Log
#### Version 1.0 - Created Compose File
#### Version 1.1 - Added Consul for KV store and Redis for caching Loki
#### Version 1.2 - Environment variables
#### Version 1.3 - Added Alert Manager
#### Version 1.4 - Grafana Provisioning
#### Version 1.5 - Cadvisor container monitoring and Container Time Zone

### To Do
#### Loki authentication and Read Write splitting

### Usage
#### apt install haveged
#### docker plugin install grafana/loki-docker-driver:latest --alias loki --grant-all-permissions
#### git clone https://github.com/nyanmark/monitoring
#### mv example_env .env
#### set your own values
#### edit alert.yaml for your own telegram bot or whatever reciever you want

### Disclaimer
#### Some of these dashboards are not mine links to their creator's should be present in the json file if they included them.