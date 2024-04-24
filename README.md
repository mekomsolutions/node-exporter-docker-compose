A simple project to host the Prometheus Node Exporter to be manually deployed on non-managed hosts.
## Deployment

### Prerequisites
* Docker and Docker compose
* A user with sudo privileges
* git

### To Deploy

```
sudo su
```

```
cd /opt && git clone https://github.com/mekomsolutions/node-exporter-docker-compose
```

```
cd node-exporter-docker-compose && docker compose up -d
```




