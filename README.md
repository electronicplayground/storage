# storage
Azurite, databases, etc.

## Secrets
```bash
printf <secret> | docker secret create my_secret -
echo <secret> | docker secret create my_secret -
```

## Network
```bash
docker network create --driver overlay --attachable storage
```