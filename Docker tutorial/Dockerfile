Dockerfile


apt-get install --no-install-recommends -y vim-tiny


Example 1:

Dockerfile to install vim and clean up the cache

FROM ubuntu:latest

RUN apt-get -y update

RUN apt-get install --no-install-recommends -y vim-tiny

Example 2:

FROM ubuntu:latest

RUN apt-get -y update

RUN apt-get install -y net-tools

RUN apt-get install -y tree

RUN apt-get install --no-install-recommends -y vim-tiny

RUN mkdir -p /usr/allen/hellokity

RUN touch /usr/allen/hellokity/Dockerfile

RUN echo 'Welcome to the world of nginx' > /usr/allen/hellokity/Dockerfile




