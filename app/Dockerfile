FROM node:latest
MAINTAINER Popsana Barida <popsyjunior@gmail.com>

RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app

#Copy the source file..
COPY src/ /usr/src/app

#Install Dependencies
RUN cd /usr/src/app && npm install

#Install Jasmine for tests..
#RUN cd /usr/src/app && npm install jasmine