Fully automated solution, with a single vagrant up command the whole environment is being provisioned.
Tech stack: 
- Vagrant
- Terraform
- Ansible
- Puppet
- Docker
- Kafka
- Grafana
- Prometheus
- Apache Web Server
- MySQL

Docker Machine runs on Debian 11, Web and DB machines run on Centos Stream 8.

The Kafka monitoring will be available at http://192.168.99.100:3000 - Grafana is used for visualization of the metrics.
Kafka Exporter -  http://192.168.99.100:9308/metrics
Prometheus UI - http://192.168.99.100:9090
Metrics from the Producer - Consumer app - http://192.168.99.100:8888/metrics
Frontend of the Producer - Consumer app - http://192.168.99.100:8080
Web App 1 - http://192.168.99.101:8001/
Web App 2 - http://192.168.99.101:8002/

