## Use case

Docker stack I have deployed in my homelab server (with Ubuntu 18.04) to monitor various hardware and software resources.
Basically it runs grafana with prometheus for metrics collection and and promtail/loki for logs collection.

### Prometheus scrapers
- Node exporter (various system stats like CPU usage, memory, disk, network, etc.)
- Sensors exporter (temp sensors and fan speeds)
- GPU exporter (monitoring Nvidia GPU)
- cAdvisor (monitor docker containers usage)

### Loki tasks
- Nginx reverse proxy logs monitoring

### Instructions
- Create system users on host systems 
