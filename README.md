# Docker image for [Docmosis Tornado](https://www.docmosis.com/products/tornado.html)

## Dockerfile links
* 2.4, [Dockerfile](https://github.com/kunalrao/docker-docmosistornado/raw/2.4/Dockerfile)

## How to run?
docker run -ti -p 8090:8090 kunalrao/docmosis-tornado:2.4

### run with Windows Docker and mount local share
docker run -ti -p 8090:8090 -v //c//docmosis//mount://mnt// kunalrao/docmosis-tornado:2.4
```
Source Templates From = /mnt/[your folder]/templates
Working Area  = /mnt/[your folder]/workspace
```
