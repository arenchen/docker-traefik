# Traefik 2

## Start
```
# If the network does not exist
docker network create --driver bridge network-dev || true

# If the volume does not exist
docker volume create --driver local --opt device=~/DockerVolumes vol

# Start
docker-compose up -d
```