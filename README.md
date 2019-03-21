# docker-alpine-hello

[![Build Status](https://travis-ci.org/kt3k/docker-alpine-hello.svg?branch=master)](https://travis-ci.org/kt3k/docker-alpine-hello)

> hello from alpine container

```console
$ docker build . -t hello
Sending build context to Docker daemon     64kB
Step 1/2 : FROM alpine:3.9.2
 ---> 5cb3aa00f899
Step 2/2 : CMD echo hello
 ---> Using cache
 ---> 20871933113d
Successfully built 20871933113d
Successfully tagged hello:latest
$ docker run hello
hello
```
