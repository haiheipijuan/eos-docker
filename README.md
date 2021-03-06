# eos-docker

[![Build Status](https://travis-ci.org/nanmu42/eos-docker.svg?branch=master)](https://travis-ci.org/nanmu42/eos-docker)

EOS docker image for mainnet production.

[Docker image](https://hub.docker.com/r/nanmu42/eos/) is built and pushed to Docker Hub by Travis CI directly.

# Usage

```bash
# clone
git clone https://github.com/nanmu42/eos-docker.git
cd eos-docker

# modify config.ini if you need
nano config.ini

# run!
docker volume create --name=nodeos-data-volume
docker volume create --name=keosd-data-volume
docker-compose up -d
```

# Supported Version

see [here](https://github.com/nanmu42/eos-docker/tags).
