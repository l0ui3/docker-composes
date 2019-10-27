# Monitoring

A monitoring tool-chain with `Prometheus`, `Grafana`, `Node Exporter`, `cAdvisor`

## Usage

First, edit `docker-compose.yml`

```
GF_SERVER_ROOT_URL=http://yourdomain.com
```

Now you can just fire up the compose command.

```bash
docker-compose up -d
```

Login your grafana page at http://yourdomain.com:3000 with credential `admin/admin`

## Exposed services

- Grafana `:3000`
- Prometheus `:9090`
- Node-Exporter `:9100`
- cAdvisor `:8080`

