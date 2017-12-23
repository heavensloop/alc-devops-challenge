FROM bitnami/node
MAINTAINER Popsana Barida <popsyjunior@gmail.com>

ENV TERM xterm

#Copy the source file..
COPY src/ /app

#Install Dependencies
RUN cd /app && npm install

#Start the Application
RUN cd /app && npm start