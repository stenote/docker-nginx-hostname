[![stenote/nginx-hostname](https://shields.beevelop.com/docker/image/image-size/stenote/nginx-hostname/latest.svg)]()
[![stenote/nginx-hostname](https://shields.beevelop.com/docker/image/layers/stenote/nginx-hostname/latest.svg)]()


# docker-nginx-hostname

## overview

Show conatiner's hostname

## Usage

### cluster

```
docker service create --name=cluster-web -p80:80 --replicas=4 stenote/nginx-hostname
```

### local

```
docker run -d -p80:80 --name=web stenote/nginx-hostname
```
