FROM bitnami/node
MAINTAINER Popsana Barida <popsyjunior@gmail.com>

ENV TERM xterm

#Copy the source file..
COPY src/ /app

#Install Dependencies
RUN cd /app && npm install

#Install Jasmine for tests..
RUN cd /app && npm install jasmine