# Hello World

This repository is a guide with a set of good practices when writting Dockerfiles.

Using a **Node.js** application as example, this guide will be a journey from a very basic Dockerfile to make it production ready, describing some of the best practices and common pitfalls that you are likely to encounter when developing Dockerfiles.

## Before we start

On [this blog post](https://engineering.bitnami.com/articles/best-practices-writing-a-dockerfile.html) you'll find detailed information about each of the steps we'll do to improve the Dockerfile. Please use it to follow this tutorial.

[Another interesting blog](https://github.com/juan131/dockerfile-best-practices) is a guide with a set of good practices when writting Dockerfiles

To run this:


```
docker build . -t express-image:0.0.1
docker run --rm -p 80:80 -d express-image:0.0.1
curl http://127.0.0.1:80
```
