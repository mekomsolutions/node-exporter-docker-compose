A simple project to host the Prometheus Node Exporter to be manually deployed on non-managed hosts.

## Deployment

### Prerequisites
* Docker and Docker Compose
* Git
* A user with sudo privileges

### To Deploy

```bash
sudo su
```
```bash
cd /opt && git clone https://github.com/mekomsolutions/node-exporter-docker-compose
```
```bash
cd node-exporter-docker-compose && docker compose up -d
```
