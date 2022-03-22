# infrastructure-home


## TODO
- Instructions for installing docker and docker-compose on pi4 64-bit


## Run Elasticsearch & Kibana on PI4 64-bit

### Install Docker Compose
TODO

### Fetch Compose YAML

```bash
wget https://raw.githubusercontent.com/ngourley/infrastructure-home/main/elastic-compose.yaml
```

### Start stack
#### Initialize with docker-compose specifying configuration, and in a detached state
```bash
docker-compose -f elastic-compose.yaml up -d
```
