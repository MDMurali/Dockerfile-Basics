# Memcached
#
# VERSION       1.0

# use the ubuntu base image provided by Docker
FROM ubuntu:12.04

# make sure the package repository is up to date
RUN echo "deb http://archive.ubuntu.com/ubuntu precise main universe" > /etc/apt/sources.list
RUN apt-get update

# install memcached
RUN apt-get install -y memcached
