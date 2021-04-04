# Documents

<h3> [Docker](/docker)</h3>

### Useful commands

> For windows OS, use powersheell to execute below commands.

### Run container
```
docker run [image-name]:[version]
```
> -d - to run the container in detached mode
> -p [host-port]:[container-mode] - to run a container on specific port

### Check logs for a container
```
docker logs [container-id]
```
> -f - to tail the logs

#### Search for an image on docker registery
```
docker search [image-name]
```

#### List containers
```
docker container ls
docker container ls -a
```

#### List local images
```
docker images
```

#### Remove local image
```
docker image remove [image-id]
```

#### Lookup image history
```
docker image history [image-id]
```

### Download an image
> If version is not specified in the command, docker will download an image associated with 'latest' tag
```
docker pull [image-name]:[version]
```

