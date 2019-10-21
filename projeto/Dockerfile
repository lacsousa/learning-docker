# Poderia ter outros nomes como: node.dockerfile, se vc tivesse vários Dockerfiles
FROM node:latest
MAINTAINER Luciano Cordeiro
COPY . /var/www
WORKDIR /var/www
RUN npm install
ENTRYPOINT npm start
EXPOSE 3000
