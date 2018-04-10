## [Base command](https://docs.docker.com/engine/reference/commandline/docker/)

```bash
# Download a base image
docker pull base

# Run an interactive shell in the base image, allocate a tty, attach stdin and stdout
docker run -i -t base /bin/sh

# Start one or more containers
docker start

# Stop one or more running containers
docker stop

# list running containers
docker ps

# List your containers
docker images
```
