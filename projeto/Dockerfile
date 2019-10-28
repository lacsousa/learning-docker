# Poderia ter outros nomes como: node.dockerfile, se vc tivesse vários Dockerfiles
FROM node:latest
MAINTAINER Luciano Cordeiro
ENV NODE_ENV=production
ENV PORT=3000
COPY . /var/www
WORKDIR /var/www
RUN npm install
ENTRYPOINT npm start
EXPOSE $PORT
