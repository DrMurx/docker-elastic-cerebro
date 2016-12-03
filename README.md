# lmenezes/cerebro in Docker

This is Docker image with lmenezes/cerebro which is a replacement for lmenezes/kopf for elastic stack v5.

- GitHub: https://github.com/ludekvesely/docker-elastic-cerebro
- Docker Hub: https://hub.docker.com/r/ludekvesely/elasticsearch-cerebro

Cerebro is an open source(MIT License) elasticsearch web admin tool. See more in [official repository](https://github.com/lmenezes/cerebro)

### Configuration

- exposed port: `9000`
- env vars: `ELASTICSEARCH_HOST=http://localhost:9200`
