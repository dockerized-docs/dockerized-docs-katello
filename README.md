# dockerized-docs-katello

# What is it?#
Dockerzied katello.org site + katello documentation for offline use.

# Image description #
- Base image: `ruby:latest`.
- The most current katello.org `master` branch is cloned.
- Jekyll is installed using bundle.

# How to use this image #

```console
$ docker run -d genadipost/dockerized-docs-katello

```

You can test it by visiting http://container-ip:8080
