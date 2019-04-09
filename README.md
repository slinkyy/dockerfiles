# Dockerfiles

## Install
```
sudo apt-get install docker.io
sudo usermod -aG docker $USER
```

## Applicable to all images:
```
git clone <this-repository>
cd <docker-image-to-build>
docker build .
```

### Tinkerpop
```
docker run --name tinkerpop -ti -p 8182:8182 -v /data:/data tinkerpop:3.3.3
```
