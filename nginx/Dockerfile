FROM ubuntu:14.04
MAINTAINER JoJo
RUN apt-get update
RUN apt-get install -y nginx
RUN echo 'Hi, Autobuild by github' > /usr/share/nginx/html/index.html
EXPOSE 80