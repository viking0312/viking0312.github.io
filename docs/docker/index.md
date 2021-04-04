## Docker

### Useful commands

> For windows OS, use powershell to execute below commands.

#### Check stats
```
docker stats
```

#### Check events
```
docker events
```

#### Check top processes runnning within a container
```
docker top [container-id]
```

#### Run container
```
docker run [image-name]:[version]
```
> -d - to run a container in detached mode

> -p [host-port]:[container-mode] - to run a container on specific port

> --restart=[always/no] - to run container by default when docker restarts

#### Check logs for a container
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

#### Pause and unpause a container
```
docker container pause [container-id]
docker container unpause [container-id]
```

#### Inspect a container
```
docker container inspect [container-id]
```

#### Stop a container
```
doker container stop [container-id]
```

#### Kill a container forcefully
```
docker container kill [container-id]
```

#### Remove all stopped container
```
docker container prune
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

#### Download an image
> If version is not specified in the command, docker will download an image associated with 'latest' tag
```
docker pull [image-name]:[version]
```

#### Inpect an image
```
docker image inspect [imge-id]
```
