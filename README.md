# docker-aws-node

[![Docker Stars](https://img.shields.io/docker/stars/jimdo/aws-node.svg?maxAge=600)](https://hub.docker.com/r/jimdo/aws-node/) [![Docker Pulls](https://img.shields.io/docker/pulls/jimdo/aws-node.svg?maxAge=600)](https://hub.docker.com/r/jimdo/aws-node/)

### Content

 * `aws-cli/1.15.8`
 * `Node 9.11.1`
 * `Docker version 18.03.0-ce, build 0520e24`

### Usage

```Dockerfile
# Dockerfile

FROM jimdo/aws-node
```

### Contribute

```bash
# Clone repository

$ > git clone git@github.com:Jimdo/docker-aws-node.git
$ > cd docker-aws-node

# Build container

$ > docker build . 

# Start bash

$ > docker run -it --entrypoint /bin/bash <container-id>
```
