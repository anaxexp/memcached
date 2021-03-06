# Memcached Docker Container Image

[![Build Status](https://travis-ci.org/anaxexp/memcached.svg?branch=master)](https://travis-ci.org/anaxexp/memcached)
[![Docker Pulls](https://img.shields.io/docker/pulls/anaxexperience/memcached.svg)](https://hub.docker.com/r/anaxexperience/memcached)
[![Docker Stars](https://img.shields.io/docker/stars/anaxexperience/memcached.svg)](https://hub.docker.com/r/anaxexperience/memcached)
[![Docker Layers](https://images.microbadger.com/badges/image/anaxexperience/memcached.svg)](https://microbadger.com/images/anaxexperience/memcached)

## Docker Images

❗For better reliability we release images with stability tags (`anaxexperience/memcached:1-X.X.X`) which correspond to [git tags](https://github.com/anaxexp/memcached/releases). We strongly recommend using images only with stability tags. 

Overview:

* All images are based on Alpine Linux
* Base image: [_/memcached](https://hub.docker.com/r/_/memcached)
* [Travis CI builds](https://travis-ci.org/anaxexp/memcached) 
* [Docker Hub](https://hub.docker.com/r/anaxexp/memcached)

[_(Dockerfile)_]: https://github.com/anaxexp/memcached/tree/master/Dockerfile

Supported tags and respective `Dockerfile` links:

* `1.5`, `1`, `latest` [_(Dockerfile)_]

## Orchestration Actions

Usage:
```
make COMMAND [params ...]
 
commands:
    check-ready host max_try wait_seconds delay_seconds
    flushall host
    
default params values:
    host localhost
    max_try 1
    wait_seconds 1
    delay_seconds 0
```

## Deployment

Deploy Memcached to your server via [![AnaxExp](https://www.google.com/s2/favicons?domain=anaxexp.io) AnaxExp](https://anaxexp.io).

